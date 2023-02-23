# :airplane: MavenAirlinesChallenge



## :books: About the Data

- The dataset contains data on nearly **130K** airline passengers about their demographics like Gender and Age, their flight details like Class and Distance and their satisfaction scores on different facilities provided by the airline like cleanliness, comfort, Wi-Fi, etc. 
- There are satisfaction scores on a total of **14 factors** and an overall verdict on whether they are satisfied or neutral/dissatisfied.
- The Satisfaction score is based on a scale of 1 to 5, with 1 being the lowest level of satisfaction and 5 being the highest. 0 means Not Applicable. 



## :dart: Business Goal

***Recommend a data-driven strategy to increase customer satisfaction rate***

## :mag: Exploration and Analysis


After gaining an initial understanding of the dataset and the problem statement, I've some guiding questions in mind to begin the analysis. These questions take us in the right direction to solve the issue in hand. I try to answer these questions through vizualisations on Tableau.

**1. What percentage of the passengers are overall satisfied with the Airline?**

![Screenshot 2023-02-20 184457](https://user-images.githubusercontent.com/96012488/220118806-86628b61-9b1d-4144-a51c-071ba6bbb3f8.png)

- As we can see above, only **43%** of the passengers are satisfied with the airline. The majority **57%** are either neutral or dissatisfied.


**2. Which customer segments are dissatisfied with the Airline? (Based on Gender, Age, Customer Type, Type of Travel, Class and Flight Distance)**

- **Gender**

|Female|Male|
|----|----|
|![Screenshot 2023-02-20 215701](https://user-images.githubusercontent.com/96012488/220158831-128968c8-e9ad-4d5b-9002-afd0dd0da981.png)|![Screenshot 2023-02-20 215644](https://user-images.githubusercontent.com/96012488/220158879-adf03fda-e756-40cc-8087-30f3e943f3a1.png)|

:arrow_right: Thus, the percentage of female passengers dissatisfied with the airline is almost the same as that of males.

#

![Screenshot 2023-02-20 223515](https://user-images.githubusercontent.com/96012488/220166293-0d5d82ff-b68e-4956-8f14-f8c8ac9dcd13.png)

#

- **Age group**

![Screenshot 2023-02-20 222425](https://user-images.githubusercontent.com/96012488/220164270-ccf34886-ec74-437a-b1cc-fad94ffbfa50.png) 


:arrow_right: Age group 31-59 has the highest percentage of satisfied customers i.e. 53% which is greater than the overall percentage of satisfied customers.

:arrow_right: *Under 18* and *60 & above* have a very high percentage of dissatisfied customers i.e. 83% and 79% respectively. 

#

- **Customer Type**

![Screenshot 2023-02-21 180324](https://user-images.githubusercontent.com/96012488/220346088-13e72d11-6162-4217-9aae-5f16b8214432.png)

:arrow_right: 76% of the *First time* passengers are dissatisfied with the airline, whereas 52% of the Returning passengers are dissatisfied.

#

- **Type of Travel**

![Screenshot 2023-02-21 181134](https://user-images.githubusercontent.com/96012488/220347618-1d513099-40ec-40fe-95c8-a3465971df54.png)

:arrow_right: A humongous 90% of the passengers travelling for *Personal purposes* are dissatisfied with the airline. Whereas, the dissatisfaction rate is 42% in the case of passengers travelling for Business.

#

- **Class**

![Screenshot 2023-02-21 181816](https://user-images.githubusercontent.com/96012488/220348861-c3a5a84f-2e04-4dd7-b40b-a49b830ab156.png)

:arrow_right: 81% of the *Economy* class passengers are dissatisfied. In the Business class, the rate is only 32%.

#

- **Flight Distance**

Flight Distance or Flight Length can be categorised into 3 groups: short-haul, medium-haul and long-haul.

-	Short-haul: Less than 1000 miles
-	Medium-haul: Between 1000 and 2000 miles
- Long-haul: More than 2000 miles

![Screenshot 2023-02-21 182210](https://user-images.githubusercontent.com/96012488/220349675-2d827b0e-3021-447c-bdcb-ef7f58e85f3d.png)

:arrow_right: 67% of the passengers of *Short-haul* flights and 52% of *Medium-haul* flights are dissatisfied. Whereas, the rate is only 30% in the case of long-haul flights.

:arrow_right: Thus, Passengers travelling for shorter distances are more  dissatisfied compared to longer distances.



**3. Which factors are the passengers most satisfied with? Which factors are they most dissatisfied with?**

![Likert scale ](https://user-images.githubusercontent.com/96012488/220844833-ffc803d6-ead8-4603-9bcc-33210db93418.png)

This is a Likert Scale Chart, which shows the percentage of passengers having the given level of satisfaction with a given factor. The yellow circles show the average ratings for each of these factors. So, as we can infer from the values of average ratings

- People are quite satisfied with 2 factors - In-flight service and Baggage handling, as their average ratings are highest.
- People are really not satisfied with 3 factors - In-Flight Wi-Fi service, Online Booking and Gate Location, as these factors have the lowest average ratings.

**4. What is the profile of a repeating customer?**

Figure out a visualisation for this, something like likert scale




## :bulb: Key Takeaways

The major takeaways from the analysis are

**Overall Satisfaction Rate**

- Only *43%* of the passengers are satisfied with the airline.

**Major Dissatisfied Customer Segments**

-	**Age:** 83% in Under 18, 73% in 60 & above and 64% in 18-30 age groups are neutral or dissatisfied.
-	**Customer Type:** 76% of First-Time Passengers are neutral or dissatisfied. Also, 52% of the Returning passengers are neutral or dissatisfied.
-	**Type of Travel:** 90% of the passengers travelling for Personal purposes are neutral or dissatisfied.
-	**Class:** 81% of Economy Class passengers and 76% of Economy Plus class passengers are neutral or dissatisfied.
-	**Flight Distance:** 67% of the short-haul flights and 54% of the medium-haul flights passengers are neutral or dissatisfied.

**Major Contributors to Customer Satisfaction and Dissatisfaction**

-	3 factors – *In-flight Wi-Fi service*, *Online Booking* and *Gate Location* have very low ratings.
-	2 factors – *Baggage Handling* and *In-flight service* have high ratings.

**Repeating Customer Profile**

-	Repeating Customer Profile: Passengers belonging to the *age group 31-59*, travelling for *Business purposes* 








## :book: Recommendations




