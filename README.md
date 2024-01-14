### Capstone-project-1
### Hotel Booking Exploratory Data Analysis

#### Obective:
I have Hotel Booking dataset.The main objective of this project is explore the given dataset and find useful conclusion about general trends in hotel booking and discover how these factors affect on hospitality business.

#### Dataset 
* Hotel: Type of hotel(City or Resort)
  
*is_cancelled: If the booking was cancelled(1) or not(0)

*lead_time: Number of days before elapsed between the entering date of booking into the PMS and arrival date.

*arrival_date_year: Year of arrival date

*arrival_date_month: Month of arrival date

*arrival_date_week_number: Week number of year for arrival date

*arrival_date_day_of_month: Day of arrival date

*stays_in_weekend_nights: Number of weekend nights(Saturday or Sunday) spent at the hotel.

*stays_in_week_nights: Number of weeknights(Monday to Friday)the guest stayed or booked to stay at the hotel.

*adults: Number of adults .

*children: Number of children

*babies: Number of babies

*meal: Type of meal booked

*country: country code

*market_segment:which segment the customer belongs to

*distribution_channel: how the customer accessed the stay corporate booking /direct/TA.TO

*is_repeated_guest: If the booking was from a repeated guest(1) or not(0)

*previous_cancellation: Number of previous bookings that were cancelled by the *customer prior to the current booking

*previous_bookings_not_cancelled: Number of previous bookins not cancelled by *the customer prior to the current bookin

*reserved_room_type: Code from room type reserved

*assigned_room_type: Code of room type assigned

*booking_changes: Number of changes made to the booking

*deposit_type: Type of deposite made by the guest

*agent: ID of travel agent who made the booking

*comapny: ID of the company that made the booking

*days_in_waiting_list: Number of the days the booking was in the waiting list

*customer_type: Type of customer, assuming one of four categories

*adr: Average daily rate

*required_car_parking_spaces: Number of car parking spaces required bt the customer

*total_of_special_requesrs: Number of special requests made by the customer

*reservation_statuse: Reservation status(Canceled, check-out or no-show)

### Data cleaning and manipulation:
### Duplicate values

Dataset have 31994 duplicate values. so these duplicate values are removedfrom dataset using.drop_dupliactes(). 
After droping duplicate value shape of the dataset become 87396 rows and 32 columns.

### Missing values/null values

Given dataset have 4 columns company, agent, country and children missing values 
so these values are replace by usin .fillna() function.

### Adittion of new columns
Total_people and Total_stay these two columns are added in given dataset Some rows 
are removed from columns adults, children and babies.

### EDA:
 For the datavisualization following charts are used:

Pie chart

Barplot

Countplot

Heatmap

#### Univariate analysis:
In univariate analysis following questions are tried to solve:

Which type of hotel is mostly prefered by the guests?
Which agent made the most bookings?
What is the percentage of repeated guests?
What is the most preferred room type by the customers?
What type of food is mostly prefered by the guests?
In which month most of the bookings happened?
Which distribution channel is mostly used for hotel booking?
which year had highest bookings?

#### Bivariate and Multivariate analysis:

In bivariate and multivariate analysis following questions are tried to solve:
which hotel has longer waiting time?
Which distribution channel contributed more to adr in order to increase the income?
What is optimal stay length in both types of hotel?
Relationship between the repeated guests and previous bookings not canceled?
Relationship between ADR and total number of people?

### Conclusion
1) City hotel is mostly preferred hotel by guests.

2) Agent no. 9 made the most bookings.

3) Percentage of repeated guest is less which is 3.91%.

4) Room type A is mostly preferred room type.

5) Mostly preferred food type is BBtype food.

6) August month has most bookings and after august july has most bookings.

7) TA/TO distribution channel is mostly used .

8) 2016 year had highest bookings and bookings were 42391.

9) City hotel has higher waiting time means city hotel is busier hotel.

10) GDS distribution channel contributed most inADR in city hotel but no contribution in resoert hotel.

11)arrival_date_year and arrival_date_week_number columns has negative correlation which is -0.51.

12)stays_in_week_nights and total_stay has positive correlation which is 0.95.













