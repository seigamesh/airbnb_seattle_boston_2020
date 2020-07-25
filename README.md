# airbnb_seattle_boston_2020
## by Seishu Miki


## 1. Dataset

The data is data of Airbnb house in Seattle and Boston which I downloaded from: http://insideairbnb.com/get-the-data.html. 
In this project, I use the the information of hosts and rooms of Airbnb in the locations in 2020 in order to answer three questions.

## 2. Questions
- What is the important element for hosts/rooms to be booked maltiple times?
- Waht is the price range of hosts/rooms booked maltiple times?
- What are the features of host/rooms with higher review score?

## Answering Questions

I investigated the dataset from Ford GoBike. The purpose of the investigation to answer the three questions above.

Question 1 - Answer
I used clustering to answer the question. Comparing 6 groups I made with the clusitering, I found that important elements for hosts/rooms to be booked maltiple times are high review socre and high response rate.
It is expected results, since we can guess host/room with high review score will give a sense of security to users, and high response rate simply contributes to good service. 

Question 2 - Answer
To answer the question 2, I simply made a histgram and calculated the percentage of price range. 
75% of average price of hosts/rooms booked multiple times is lower than $172. Also, 72% of room price is between ＄40 and ＄170.
This number implies can add another insight on the answer for the question 1. Since  there is no specific popular price range, price cannot be a direct element to lead users to book the room again.  

Question 3 - Answer
I analyzed data of rooms with high review score of 95. 
First feature is high responce rate. Over 90% of hosts who proved rooms with high review scores responsed over 90% of messages.
Sencond one is room type. 73% of roomtypes of them is  Entire home/apt and 26% is private room. Shared room and hotel room are not usual for room types with high review score.
