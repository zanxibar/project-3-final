# (Ford GoBike System Data Exploration)
## by  Som Patrick


## Dataset

There are 183412 bikes in the dataset with 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip'). Some data points were removed from the analysis due to inconsistencies or missing information


## Summary of Findings
These are all the summary of all my findings from my exploration:

Univariate exploration 

* Out of the total number of people(174952), 130500 are males , 40805 are females and 3647 are Other.i.e consider themselves as neigher male nor female

* There are basically two type of users: Subscriber and Customer. Below are the types of users and their respective values:

Subscriber : 158386; Customer : 16566
There are more Subscribers than Customers. Subscribers make up a total percentage of 90.53% while Customers are a total of 9.47%.

* Very few people shared their bike during all the trip about 17346 of them whiles the majority did not which makes up a total of 157606 people.

* The minimum trip took about 61 seconds, average trip took about 704 seconds and the maximum trip took about 84548 seconds.

* Over 3500 people started their trip from Market St at 10th St,San Francisco Caltrain Station 2  (Townsend St at 4th St) had  3408 people starting their trip from there, 2952 also started from Berry St at 4th St,Montgomery St BART Station (Market St at 2nd St) had 2711 people starting their trip from there,and lastly, 2620 people started from Powell St BART Station (Market St at 4th St) 

Bivariate exploration 

* Out of a total number of 40805 females, 4623 of them are customers and 36182 are subscribers.Also 11493 and 119007 are males customers and subscribers respectively. Lastly, 3647 people are categorized as other genders, with 450 of them being customers and 3197 being subscribers.

* Most of them among the various genders did not share their bike during all the trip.More males did not share as compared to females and 'other' gender. Moreover, those who shared their bike are very few with males making up a number of 13104(the majority), followed by females making up a total of 3594 with the least being those identified as 'other' with a total number of 648.


* A total of 3649 people started their trip from Market St at 10th St among which 876 are females , 2700 are males,and 73 of them identify as other gender.

* A total of 3408 people started their trip from San Francisco Caltrain Station 2 (Townsend St at 4th St) among which 718 are females , 2652 are males,and 38 of them identify as other gender.

* A total of 2952 people started their trip from Berry St at 4th St among which 815 are females ,2095 are males,and 42 of them identify as other gender.

* A total of 2711 people started their trip from Montgomery St BART Station (Market St at 2nd St) among which 473 are females ,2170 are males,and 68 of them identify as other gender

* A total of 2620 people started their trip from Montgomery St BART Station (Market St at 2nd St) among which 567 are females ,2009 are males,and 44 of them identify as other gender


Multivariate Exploration 

* A large number of males(both subscribers and customers) bike trips are accumulated around 0 second and the 20000 seconds threshold similarly as the females.For both males and females, the longest trip was taken by a subscriber. Howerver, for the other gender, the longest trip was taken by a customer.

* The median age for those who shared their bike during all the trip are fairly above those that didn't.
The shape of the distribution (wide in the middle) indicates that most of the values are highly concentrated around the median.
Also, the interquartile range for the year is roughly between 1980 and 2000 for those who didn't share their bikes during all the trip.


## Key Insights for Presentation

For the presentation, I focused on these: 

* Composition of the various genders in the dataset
Out of the total number of people(174952), 130500 are males , 40805 are females and 3647 are Other.i.e consider themselves as neigher male nor female.   

* Types of users of the biking service.
I wanted to find out the different types of users of the biking service. There are two types of users: Subscribers and Customers. A larger number of the were subscribers.

* The various genders and their corresponding user types
Out of a total number of 40805 females, 4623 of them are customers and 36182 are subscribers.Also 11493 and 119007 are males customers and subscribers respectively. Lastly, 3647 people are categorized as other genders, with 450 of them being customers and 3197 being subscribers.
