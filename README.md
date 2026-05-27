# UC Berkeley ML-AI-Cert
# Assignment 5.1 - Will the customer accept the coupon?

## Project files
- [Notebook: Assignment5_1_Notebook_PB.ipynb](Assignment5_1_Notebook_PB.ipynb)

### Problem presented
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).

## Summary of findings
In preparing this report we first eliminated columns that had incomplete information, and then eliminated some rows (less than 5%) which also were missing data.

The main conclusions of our analysis are that we have found interesting insights regarding which customers accept certain types of coupons.  This allows us to make specific recommendations as to which campaigns our stakeholders should prepare, based on our model.

As an example of the findings we include this figure showing the coupon acceptance matrix comparing the types of coupons issued and the distance from the current location of the driver to where to obtain the benefit.
![alt text](\images\image.png)