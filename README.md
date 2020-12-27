
# Determine the right number of dishes to prepare for food distributions

Final project for the Building AI course

## Summary
This solution aims to determine the right number of dishes to prepare for food distribution while ensuring that all beneficiaries will have enough to eat and minimizing food waste.


## Background
When distributing food to people in need, it is very difficult to estimate the correct number of dishes to prepare. Indeed, the number of parameters to be taken into account is very important. In addition, human behavior is rarely linear. Sometimes 300 people can wait for distribution in the cold and rain. And sometimes there are only 10 people despite the weather being very nice.

To avoid not having enough, we always take more than necessary: ​​result, at the end of the distribution, we have to throw dozens, or even hundreds of meals in the trash.

Meals are expensive, and they are financed by donations from citizens. It is therefore important to reduce food waste in order to use these savings in purchasing equipment and improving meals.

This same problem can be found in company canteens. Indeed, with the Covid-19, many companies use teleworking and the number of employees on site varies enormously from day to day.

* problem 1: estimating the minimum number of meals to prepare
* problem 2: reduction of food waste.

## How is it used?
This solution must be based on previous food distributions and take into account many phenomena such as the weather, the day of the week, the season, the number of people during the previous distribution, and many others.

The tool will take the form of a website in which associations that so wish can enter their information from the day before, such as the number of meals distributed, the number of beneficiaries, the date, the duration, etc.
The site will then suggest a number of meals to prepare and a confidence index. The model will have to constantly update itself and try to improve its performance.

The algorithm and the tool are under construction.

## Data sources and AI methods
Today, each association has its own register with information on the food distributions it carries out. More often than not, this data is written on sheets or books of accounts. The first step will therefore consist in digitizing this data, standardizing it and storing it in a secure and dedicated database. In France, there is a dedicated organization. It will be a very long and tedious job because there is thousands of data to report.

These data will have to be processed using an RNN neural network to take into account the past and the non-linear aspect of the phenomena.

## Challenges
This project will never be able to predict a correct number of meals if special and unforeseen events occur, for example: an accident, an important football match, a confinement ... These events, if they occur, will have a significant effect on the number of beneficiaries present during food distributions.

It will also be necessary to pay attention to data integrity and non-disclosure. Indeed, it will be necessary to be very careful to anonymize the data. In addition, some associations will not want to share their data, for example: a migrant assistance association could fear that this data will be used by the police or customs services.

## What next?
This project could be rolled out in company canteens or schools when the workforce is subject to vary a lot, especially in this period of Covid-19

Another possibility of improvement would be to add a by chance to take into account unforeseen events.


## Acknowledgments
* elementsofai.com
