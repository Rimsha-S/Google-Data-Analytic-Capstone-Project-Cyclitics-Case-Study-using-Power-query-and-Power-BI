# Google-Data-Analytic-Capstone-Project-Cyclitics-Case-Study-using-Power-query-and-Power-BI

## Introduction 

This is the case study as a part of Google Data Analytics professional certificate course offered on Coursera. In order to practice my Power BI skills, I decided to use Power query and  Power BI for the complete data analysis process (Ask, Prepare, Process, Analyze, Share and Act).


## Scenario

Imagine you are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.


#### Characters and teams 

● Cyclistic: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day. 

● Lily Moreno: The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels. 

● Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. You joined this team six months ago and have been busy learning about Cyclistic’s mission and business goals — as well as how you, as a junior data analyst, can help Cyclistic achieve them. 

● Cyclistic executive team: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program


### About the company

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs. Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.


### Steps involved :

The Six Steps Approach

![image](https://user-images.githubusercontent.com/105121789/213728893-e4b07d4b-fca7-45fd-82bc-812ee265a0e3.png)

#### Ask

“How can Cyclistic ensure speedy success by converting casual riders into annual membership subscriptions?”
The finance department has indicated that the annual subscribers (members) are more profitable than casual riders. Also, Moreno, the director of marketing, doubling as my manager foresees members as key to driving growth. Therefore, she has set a clear goal to design marketing strategies aimed at converting casual riders into annual members.
In order to fulfill the task, the marketing team needs to analyze Cyclistics historical data to identify trends. Leading to the following business question: “How do annual members and casual riders use Cyclistic bikes differently?”


#### Prepare

The data is sourced from CSV files downloaded from coursera under the license. It is 12 months of CSV files organized from January 2021 to December 2021. For the purpose of the project, the CSV files are stored in a local drive.
Let’s explore the credibility of the data using ROCCC:
Reliable (R)- the data is fictitious only for the purpose of this case study 
Original (O)- Original data source with licenses agreement 
Comprehensive(C)- Missing important information needed
Current (C)- Data is current and regularly updated every month.
Cited (C )- Yes.
Missing information on customer demographics and price points.


#### Process

Power BI: Power Query + Power Pivot
a. Data Cleansing and Transformation
To Extract, Transform and Load (ETL), I used the Power Query Editor.
Getting data into Power BI by uploading the folder containing the 12 CSV files. The files are then combined into a single file named bikeshare_data and some necessary data cleaning and transformation are performed. Below is a snapshot of the cleaning steps:

![image](https://user-images.githubusercontent.com/105121789/213730502-6000f546-fc5e-4dac-8f98-fee5d0706cd5.png)

b. Data Expression Analysis (DAX)
Performing some basic calculations (Measures and Columns) aggregation

#### Analyze/Share

##### Power View
Now, that the data is cleaned and aggregated, it is time to find insights through visuals. The Power View function is used for data visualization and creating pivot tables.

##### Insights:

##### Ride Distribution

![image](https://user-images.githubusercontent.com/105121789/213731091-a2dc21a2-45b1-4d25-be1d-1f6aa0592d79.png)

As we can see, members are about 10% more than casual riders. In figures, members are approximately 2.5 million and casual riders 2 million in number.

##### Distribution By Rider and Bike Type

![image](https://user-images.githubusercontent.com/105121789/213731689-34a5f38d-945a-414c-a892-4bdeac1342c9.png)

Classic bike type is most preferred, followed by electric and docked bike is less used. For both classic and electric bikes, members ride more often than casual riders. Surprisingly, members do not use the docked bike at all.


##### Average Ride length by Rider type

![image](https://user-images.githubusercontent.com/105121789/213731896-47f8c36f-ea0e-4b3f-95ab-0d2cc7c9f60a.png)

We can see that the average ride length of casual users are 18.7 and that of member users are 12.2.

##### Trends Analysis:

Now, we will look at trip performance per month, day of week

![image](https://user-images.githubusercontent.com/105121789/213732922-fc1b6991-3afc-40d7-9871-1675cca199c8.png)

From the line graphs above, it is evident that casual members prefer riding bikes between late spring to the end of summer and refrain from biking in the winter months (Jan/Feb), likely due to the worse weather conditions. Annual members prefer the spring/summer months as well; however, their ridership levels are more consistent and steady over the year compared to a sharp peak point for casual riders.
It can be observed that there is more riding happening on the weekends (Friday, Saturday, and Sunday). Properly most riders (member/casual) ride for leisure during the weekends.


### Dashboard

![image](https://user-images.githubusercontent.com/105121789/213733398-442be08d-3459-4640-9271-14a189d609ac.png)


### Conclusions

Classic bike is the most frequently used bike by both member and casual riders.

Casual riders prefer to ride a lot between late spring till the end of summer season.

Trips are high in the weekends compared to the week days, especially for casual riders.


### Recommendations

Management should implement strategies to improve the use of other bike types such docked and electric bikes. Campaigns should not target converting causal riders to members, but also the need to increase the used of all bikes.

As casual riders turn to ride frequently in the spring and peaking in the summer, the campaign must be intensified during this period. This would enhance well target campaign with the potential of high conversions.

Weekends are busy as (casual) riders probably use bikes for leisure purposes, targeting them on the weekend would be a great advantage to convert them into members.

Benefits of the membership subscription should be given to casual memebrs as some casual riders might not be aware of the benefits associated with the monthly subscription package.
