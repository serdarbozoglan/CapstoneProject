## FLIGHT CANCELLATION PREDICTION
   
## The Problem

Predicting Cancellation of Domestic Flights in the USA. Flight cancellation is a rare event but a big concern for many people/organization. Because if you have a flight, most probably all other your plans will be based on your arrival to the destination. Assume you have a holiday plan in LA, you booked your hotel, you rented your car, you made a reservation for an activity etc. But when you arrive the EWX airport you released that your flight is cancelled. Then you have to alter all your plans due to this unexpexted rare event . It is needless to say you would have taken necessary precautions if you had known your flight’s cancellation in advance. Definitely there are many factors which may result in those cancellations such as origin and destination airport location, airline company, time of flight etc. In this study we will propose a model to predict flight cancellations for US domestic flights at 20 most used airports in the USA.

## Who Might Care :

a. Travellers : Flight cancellations have a huge impact on whoever will have a flight trip, so travellers definitely can care cancellations.

b. Travel Planners : Some organization companies like tourism agency make plan for their organizations. For instance they sell cultural/historical or holiday travel package. If their flight cancelled then they may have encounter big problems. In this context, they also care about flight cancellation prediction.

c. Online Booking Companies : Booking.com, Kayak.com, Skyscanner.com are top online flight ticket selling companies. Cancelled flights will defintely affect their business negatively. If they known in advace/ predict cancellations they can inform their customers to take precaution against the problem which may stem from flight cancellation.

d. Airline Companies : Airline companies may suffer from cancellation very much. If they have relatively higher cancellation rates they may have a customer churn problem. In order to avoid this problem they aslo care it.

e. Hotels : Even hotels, espacially located nearby airports (destination) may be affected by cancelled flights. They may show interest on predicting cancelled flighs.

All those shareholders may be affected because of flight cancellations. To minimize the negative effect of cancellation by predicting those cancellations we will build some ML algortihms.

## Data Set :

a. The data has been obtained from the "Bureau of Transportation Statisitcs" (https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236&DB_Short_Name=On-Time.) which allows to download the flight data monthly at a time. This data contains information about flights and their on-time performance, including date of flight, carrier company, origin and destination airports, flight duration, flight distance, delay, cancellation, diversion etc.

b. The dataset has 2798209 observations/rows as well as 110 features/columns.

c. The data seems raw. It has too many missing values in addition to some outliers.

d. The data is not fictitious but real, and belongs to first half of 2017.

e. Target Feature is 'Cancelled'. Since it takes 1 for cancelled flights and 0 for non-cancelled flights, so it is binary.

f. Although the flight cancellations may results from bad weather conditions as well, in this study weather conditions will not be in our scope.

## Machine Learning Aspect

1. We have labeled data and target fetaure is a binary variable so this is a classification problem.

2. We will use Logistic Regression, K-NN Neighbor, Random Forest, Adaboost and Gradient Bosoting algorithms to solve the problem

3. My dependent feature will be Cancelled column and take 1 for cancelled flights and 0 for non-cancelled flights

4. My independet features will be Origin Airport [Origin], Destination Airport [Dest], Scheduled Flight Time [CRSElaspedTime], Taxi Out (total time on gateway before taking off) Duration [TaxiOut], what part of the month the flight will occur (first 2 weeks or latter 2 weeks) [PartOfMonth], when the flights occur (weekdays or weekends) [PartOfWeek] and what part of the day (night, daytime or morning hours) [PartOfDay] would the flight happen, Departure Delay Minutes [DepDelayMinutes] and Airline Company [Carrier] in my model.

5. I will use 80% of my data as train set and 20% or my data as test set and I will split my data at the very beginnig of my study. All data cleansing preocess and EDA Analysis will be implement on train data set. Test data set will be manipulated with regard to train data set before ML implementation and later it will be used only in ML algorithms to evaluate how our ML models' performance.
