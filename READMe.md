SUMMARY

In this repository, you will find this READMe file, a jupyter notebook, and a dataset file.

The jupyter notebook is authored by Kelly Lieu, grad student of UC Berkeley Artificial Intelligence
and Machine Learning class of 2024-2025. The purpose of this assignment (Module 5) is for 
students to use real-world data to apply concepts learned from class, such as plotting, statistical summaries, and visualization using Python.

DATA

The datasource is from UCI Machine Learning repository and data is collected by survey from Amazon Mechanical Turk. The dataset provides information about drivers who receive coupons on their cellphone while driving. Examples of coupons offered are, discounts a coffee house, bar, restaurants nearby, carry out, etc. The data also provides attributes about the driver, such as age, marital status, occupation, education, and frequency of visiting each destination. Other attributes in the data provides information about whether the drivers accepted the coupons, temperature, time, type of passenger, etc.

FINDINGS

The jupyter notebook will walk us through all of the Python code, including comments, written to transform data, filter and manipulate data in order to calculate the rate of acceptance of coupons based on different combinations of criteria, particularly bar coupons. 
Findings include: 
* 56.84% of total 12,684 total observations accepted coupons.
* The most accepted coupons is for Coffee House, followed by restaurants less than 20 minutes away, and then Carry out & Take away.
* The temperature when most coupons are accepted is at 80 degrees.
The observations are then narrowed down by bar coupons. 
* The total number of bar coupons offered is 2017 out of 12,684 total observations.
* In all coupons accepted, 6.52% were bar coupons.
* In bar coupons offered, 41% were accepted.
* In bar coupons offered, 1818 observations are people who go to the bar 3 or less times a month.
* In bar coupons offered, 33.41% of bar coupons were accepted by people who went to the bar 3 or less times a month.
* In bar coupons offered, 66.58% were accepted by people who went to the bar 4 or more times a month. This indicates that people who went to the bar more than 4 times a month were significantly more likely to accept a bar coupon.
* In bar coupons offered, there are 1513 people over 25 years old.
* In bar coupons offered, 292 drivers over 25 years old, who go to bar more than once, accepted coupons.
* 85.52% of bar coupons were accepted by people who were not over age 25 AND went to the bar 1 or more times a month. This indicates that younger people who went to the bar more than once a month were significantly more likely to accept a bar coupon.
* 19.48% of bar coupons were accepted by people who went to the bar 1 or more times a month AND did not have kids as passengers AND did not have an occupation in the farming, fishing, or forestry.
* 27.31% of bar coupons were accepted by people who:
    EITHER go to bars more than once a month, had passengers that are not kids, and not widowed
    OR go to bars more than once a month and are under the age of 30
    OR go to cheap restaurants more than 4 times a month and income is less than $50K.