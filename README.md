# Hotel Booking Exploratory Data Analysis
## Obective:
I have Hotel Bookin dataset.The main objective of this project is explore the given dataset and find useful conclusion about general trends in hotel booking and discover how these factors affect on hospitality business.
## Dataset:
The iven dataset have information of city and resort hotel. This dataset have 11390 rows and 32 coulumns. The columns from the dataset is as follows:

**Hotel:** Type of hotel(City or Resort)

**is_cancelled:** If the booking was cancelled(1) or not(0)

**lead_time:** Number of days before the actual arrival of the guests
**arrival_date_year:** Year of arrival date
**arrival_date_month:** Month of arrival date
**arrival_date_week_number:** Week number of year for arrival date
**arrival_date_day_of_month:** Day of arrival date
**stays_in_weekend_nights:** Number of weekend nights(Saturday or Sunday) spent at the hotel by the guests.
**stays_in_weel_nights:** Number of weeknights(Monday to Friday) spent at the hotel by the guests.
**adults:** Number of adults among the guests
**children:** Number of children
**babies:** Number of babies
**meal:** Type of meal booked
**country:** country of the guests
**market_segment:** Designation of market segment
**distribution_channel:** Name of booking distribution channel
**is_repeated_guest:** If the booking was from a repeated guest(1) or not(0)
**previous_cancellation:** Number of previous bookings that were cancelled by the customer prior to the current booking
**previous_bookings_not_cancelled:** Number of previous bookins not cancelled by the customer prior to the current bookin
**reserved_room_type:** Code from room type reserved
**assigned_room_type:** Code of room type assigned
**booking_changes:** Number of changes made to the booking
**deposit_type:** Type of deposite made by the guest
**agent:** ID of travel agent who made the booking
**comapny:** ID of the company that made the booking
**days_in_waiting_list:** Number of the days the booking was in the waiting list
**customer_type:** Type of customer, assuming one of four categories
**adr:** Average daily rate
**required_car_parking_spaces:** Number of car parking spaces required bt the customer
**total_of_special_requesrs:** Number of special requests made by the customer
**reservation_statuse:** Reservation status(Canceled, check-out or no-show)
**reservation_status_date:** Date at which the last reservation status was updated
## Data cleaning and manipulation:
## **Duplicate values**
Dataset have 31994 duplicate values. so these duplicate values are removedfrom dataset using.drop_dupliactes(). After droping duplicate value shape of the dataset become 87396 rows and 32 columns.
## **Missing values/null values**
Given dataset have 4 columns company, aent, country and children missing values so these values are replace by usin .fillna() function.
## **Adittion of new columns**
Total_people and Total_stay these two columns are added in given dataset
Some rows are removed from columns adults, children and babies.
