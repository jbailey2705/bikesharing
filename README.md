# NYC Citibike

## Purpose
 1. Import cvs data into Tableau. 
 2. Create & style worksheets display dashboards, & stories in Tableau.
 3. Use Tableau worksheets to show data in a prfessional manner to show buisiness partners and potential clients.
 4. Portary data from the Citie spreadsheet accurately using dashboards in Tableau.
 
## Overview of the statistical analysis:
Des Moines requested a business proposal on Citibike tripdata. NYC Citibike data from August 2019 was reviewed by looking at geographical data as well as data disaggregated by user types and genders to determine if it would be a good investment for Des Moines. Other data points include:
 - usage durations
 - peak usage times
 - key target market

## Link to Tableau Story:

[Citibike Analysis Story](https://public.tableau.com/app/profile/johnny.bailey/viz/CitibikeAnalysis_16680462622690/CitibikeAnalysis?publish=yes)

## Data Cleaning:
The initial data was cleaned using Jupyter Notebook, changing the trip duration data to a datetime field. 

![Screenshot 2022-11-09 at 4 36 14 PM](https://user-images.githubusercontent.com/109354592/200957154-88235c15-bfc0-49e3-b652-a16bf1f3e461.png)
![Screenshot 2022-11-09 at 4 36 47 PM](https://user-images.githubusercontent.com/109354592/200957157-4d29a358-1b21-43ea-a676-850dfd0c400d.png)

## NYC Citibikes Analysis:
For NYC, there were some trips outside the city center. Future analysis will need to be included to provide an overall geographical view.

1. [Check out Times for All Users](https://public.tableau.com/app/profile/johnny.bailey/viz/CheckouttimesbyAllUsers/CheckouttimesbyAllUsers?publish=yes)
Citibikes usage reached a top of 3k minutes per user as shown in the graph.

![Checkout times by All Users](https://user-images.githubusercontent.com/109354592/200974548-6fa0975a-6243-4787-a718-2174e389b5df.png)

2. [Checkout Times by Gender](https://public.tableau.com/app/profile/johnny.bailey/viz/CheckouttimesbyGender_16680422710320/CheckouttimesbyGender?publish=yes)
As the data shows Male users are significantly higher users of the bikes than other users. 

![Checkout times by Gender](https://user-images.githubusercontent.com/109354592/200975306-d8587691-aace-4a1b-97d6-c1cfb9485fd0.png)

3. [Trips by Weekday per Hour](https://public.tableau.com/app/profile/johnny.bailey/viz/TripsbyWeekdayperHour_16680424543900/TripsbyWeekdayperHour?publish=yes)
Peak hours include 6-10am & 5-8pm through the week, while on the weekends peak hours are from 5am through 10pm.

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/109354592/200975791-82a1a1fa-3daa-4a02-89e7-2183b86ed01f.png)

4. [Trips by Gender (Weekday per Hour)](https://public.tableau.com/app/profile/johnny.bailey/viz/TripsbyGenderWeekdayperHour_16680429352030/TripsbyGenderWeekdayperHour?publish=yes)
During the peak hours, males are higher users than other genders.

![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/109354592/200976649-3d113b94-916f-472d-b0b5-dcdfbf3b0e48.png)

5. [Trips by Gender and User Type (Weekday per Hour)](https://public.tableau.com/app/profile/johnny.bailey/viz/UserTripsbyGenderWeekdayperHourDashboard/UserTripsbyGenderWeekdayperHourDashboard?publish=yes)
Based on the Trips by Gender data, Male subscribers used the bikes more than the female subscribers. Additional study may help show why male subscribers use the service more than female subscribers. We can also ask "what, can we do to cater to our female subscribers in the future. 

![User Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/109354592/200978298-22c16d1e-ecb0-44d5-a7ce-7bc6c4a808f3.png)

## Summary

Bikeshare services are very popular in busy areas of the city, where the area is densely packed with real estate, and parking is scares in the area. The male subscribers make up the larger users of the service. More questions and surveys should be sent out to our female subscribers to see what can be done to improve the number of female subscribers in using the services provided.

Other data points we could look at for further analyisi include:
- When is the best time to perform needed bike repairs
- Rush hour time windows, displaying the flow of traffic around the city/neighborhoods, peak hours
- average trip duration by gender, birth year to analyize male, female, and un-gendered riders as they age
