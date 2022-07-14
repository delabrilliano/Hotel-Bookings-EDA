# **Hotel Bookings EDA**


![image](https://raw.githubusercontent.com/delabrilliano/Hotel-Bookings-EDA/main/image/Hotel%20Bookings.png)


*Created by* : [Erike](https://github.com/Nasyahh), Delabrilliano, [Reyhan](https://github.com/reyhanalif)

<hr>

## **Context**

The tourism industry is one of the industries that are most affected by the Covid-19 pandemic, specifically, the hotel industry. With travel restrictions, according to research conducted by Mckinsey in 2020, the rate of hotel bookings has been deeply decreased, it makes investors of the industry very pessimistic.

To deal with this, hotel owners need to operate their operations efficiently to increase revenue so they can 'survive' from this pandemic. Therefore, we will carry out Exploratory Data Analysis with the 'Hotel Booking Demand' database to find out what can be improved from a hotel operation.


<hr>

## **Insights from EDA**:

- **Insights 1:**
    - 47% of guests stay at City Hotel for less than the average length of stay. (Only 1-3 days)
    - Only 19% of guests at City Hotel stayed for longer stay.
    - Customers who stay at Resort Hotels have the same tendency between those who stay within 1-3 days and more than 4 days/long stay

- **Insights 2:**
    - In City Hotel, guest who stayed until Check-Out in 2015 were 7624, in 2016 22553, and in 2017 were 15743. There was an increase in number of guests on 2015-2016 as many as 14929 visitors or as much as 195%. But the numbers has decreased in 2017 as many as 7080 visitors or 31% from the previous year.

    - In Resort Hotel, guest who stayed until Check-Out in 2015 were 6077, in 2016 13423, and in 2017 were 9066. There was an increase in number of guest on 2015-2016 as many as 7346 visitors or as much as 120%. But the numbers has decreased in 2017 as many as 4357 visitors or 32% from the previous year.

- **Insights 3**:

    - In 2015 there was an increase in City Hotel guests between July-September and a decrease in November, while Resort Hotel visitors during July-December did not experience much fluctuation.
    - In 2016 there was an increase in City Hotel guests from January to June, although there was a decline in July, but the numbers of guest experienced a bounce back in August and peaked in October, then decreased again until the end of the year. Resort Hotels also experienced an upward and downward trend that is not much different each months. The numbers peaked in October, but its numbers is only half from numbers of guest from City Hotel.
    - In 2017 there was an increase in City Hotel visitors between January-May and a decrease in June-August, while Resort Hotels at the same time received visitors which number did not change much for each month.

- **Insights 4:**

    - Orders with the deposit type of 'No Deposit' are the most common type of deposit with a percentage of 87.65% of the total order amount.

    - Based on the bivariate analysis above, from the total of all bookings at the hotel, orders without a deposit have the highest cancellation rate, amounting to 24.87%.

- **Insights 5:**

    - The most booked hotel type is city hotel with a percentage of 66.45% of all bookings.

    - From the results of the bivariate analysis above, it can be seen that the cancellation rate at city hotels is almost 3 times that of Resort Hotels.

    - From the multivariate analysis above, it can be seen that the highest cancellation rate comes from order for City Hotel type hotels with no deposit.

- **Insights 6:**

    - Most hotel bookings made through Online Travel Agents, amounted to 47.3% of the total bookings made.

    - From the results of the bivariate analysis above, it can be seen that the highest cancellation rate comes from Online TA with the percentage of 17.37%.

    - From the results of the multivariate analysis above, it can be seen that the highest cancellation rate comes from Online TA with the 'No Deposit' type of deposit.

- **Insights 7:**

    - From the results of the Chi-Square Test, it was found that the p value < 0.05, which means that the variables of deposit and cancellation types are dependent on each other.

- **Insights 8:**

    - 94.62% of guests whose rooms have changed from those booked do not cancel their bookings.

    - Meanwhile, only 5.38% of guests whose rooms have changed from those booked cancel their orders

- **Insights 9:**

    - Bookings made by new guests are much higher, which are 115,580 compared to bookings by repeated guests, which are 3,810.

    - Bookings made by new guests at City Hotel have a much higher number of 77,298 compared to 38,282 resort hotels.

    - The number of bookings made by repeated guests at City Hotels is not much different from Resort Hotels, with city hotels with 2,032 repeated guests and resort hotels with 1,778 repeated guests.

    - In total, the number of new guests orders has a much higher percentage of 96.81% compared to repeat guests of 3.19%


- **Insights 10:**

    - The number of adult guests at the city hotel is 146,838, almost double the number of resort hotels which have a total of 74,798.

    - The number of children guests at the city hotel is 7,248, more than the resort hotel which has 5,155.

    - The number of baby guests at the city hotel is 392, less than the resort hotel which has 557.

<hr>

## **Analysis**

**- Business Question 1-3:**

- City Hotel, which is located in Lisbon, Portugal, has a lot of historical and cultural tourism potential, so City Hotel has many enthusiasts plus it is easy for foreign tourists to come through the international airport. Resort Hotel is located in the Algarve in the south of Portugal, which has beach views and the atmosphere of a quiet coastal village and port city with a long history.
- Both hotels types have an increasing and decreasing trend of visitors. February-June coincides with summer which is the high season for the hotels and July-October which coincides with autumn, and cultural festivals in Portugal.

**- Business Question 4-7:**

- From several bivariate-multivariate analysis results that have been carried out, bookings with 'No Deposit' always have the highest cancellation rate. Especially 'No Deposit' on City Hotel bookings, and 'No Deposit' on bookings through Online Travel Agents.

- With Chi-Squared analysis, it was found that the deposit type variable and the cancellation variable, are correlated.

**- Business Question 8-10:**

- Cancellation of orders when there is a change in room type due to the room being booked is not available, has a relatively smaller cancellation number compared to guests who do not cancel their order, which is 5.38%. This means that most guests even if they get a room change from what they have booked, most of them did not cancel their booking.

- From the comparison of the number of new guest bookings and repeat guest bookings, it was found that the percentage of new guest bookings was much larger than repeated guests which was only 3.19%. Based on the journal entitled "Why Customers Don't Revisit in Tourism and Hospitality Industry?" by Jing-Rong Chang, the reason guests do not rebook can be due to the accessibility of the hotel's less strategic location, prices that do not match the facilities, cleanliness of the hotel, and negative reviews on the internet.

- Data on the number of hotel guests by age category shows that adult guests at City Hotel have almost 2x the number of Resort Hotels. Although the number of adult guests of the two hotels has a significant difference, the data on the number of guests in the Children and Infant categories has a difference that is not much different. City Hotel has more guests in the Child age category than Resort Hotel, but Resort Hotel has more guests in the infant age category than City Hotel. This means that the proportion of guests with children and babies at Resort Hotels is greater than City Hotel.

<hr>

## **Business Recommendation**

**- Business Question 1-3:**

- The analyzed length of stay data is in accordance with the journal of 'Lisbon and Porto Hotel Market Research & Forecast Report' written by Joaquim Chambel which states that the average hotel visitor stayed between 1-3 days. The trend of increasing visitors can be an optimistic view by increasing the supply of rooms and improving the quality of hotels to accommodate the growth of tourism in Portugal.

- There is an increasing trend of visitors in February-June which coincide with summer in Portugal, which according to the research of 'Season and Weather Effects on Travel-Related Mood and Travel Satisfaction' by Margareta Friman et al. Sunny weather that supports outdoor activities will increase the mood and satisfication of traveling. Based on these findings, the hotel's `Marketing Division` can adjust the marketing method for the summer season. According to Nancy Huang, Senior Marketing Director, as quoted from her article on pegasus.com, summer is the best time to offer a package and outdoor activities such as collaborating with tourist attractions in the area. In addition to these promotions, the hotel can also use social media to show what the summer activities will look like in the summer holidays.

- The trend of increasing visitors in July-October coincides with autumn season in Portugal. According to Lamia Darwish's writing entitled 'Best Time To Visit Portugal', Portugal tourism experienced a high-demand in this period. This is due to the warmer weather, the grape harvest, the quieter beaches, and the cultural festivals held every year on Portugal. The `Guest Relations Division` can make improvisations in line with the study 'Outdoor Tourism in the North of Portugal from the Perspective of Tourist Entertainment Companies' which states that hotels can offer outdoor activities such as walking tours and take advantage of less hot and sunny weather.

**- Business Question 4-7:**

- Based on a study conducted in 2019 by Fernández, Vall-Llosera, and Moya entitled "ANALYSIS OF OTA IMPACT ON HOTEL RESERVATIONS", the study found that hotel bookings through Online Travel Agents (OTA) account for up to 93.2% of total hotel bookings. This is in line with the dataset that we use, where the largest hotel bookings come from OTAs (47%). Based on this, the `Marketing Division` of the hotel can focus on promotion and marketing through OTA channels in order to reach the widest market. Plus, based on data from PhocusWright (a research company focused on the Travel industry), 60% of travelers will visit OTAs when doing research for options when they travel. By doing marketing through OTA, a hotel will be able to become a 'stand-out' option when founded by potential visitors on OTA.
    
- The 'No Deposit' deposit type always has the highest order cancellation rate. In contrast, 'refundable' and 'non-refundable' deposit types always have lower cancellation rates. In addition, after conducting a chi-squared test between the deposit types and order cancellation variables, it was found that the two variables were related. This is in line with a study conducted by Chayanon Tongmunkorn (2021) where he found that the type of deposit is one of the most influential variables on the customer's decision to cancel an order. Based on a study by Chen, Schwartz, and Vargas (2011), hotels can optimize their revenue system by varying their booking cancellation policies, such as the use of deposits, cancellation deadlines, and attractive offers. Based on this, the `executive office` division, which is in charge of managing all hotel operations, can implement a discount if a customer makes a reservation with a 'refundable' deposit type and gives discounts + other offers for customers who choose a 'non-refundable' deposit type. In addition, the hotel can also provide strict cancellation deadlines for bookings of the 'no deposit' type.

**- Business Question 8-10:**

- To attract a guest to come back, hotel cleanliness must always be considered. The `Houeskeeper` Department can make strict cleaning schedules and controlled reports to ensure hotel cleanliness is maintained. And then the `Department of Sales & Marketing` which is responsible for managing the hotel website must be able to identify negative customer comments on the internet and respond to them quickly and carefully. A less strategic location can also be anticipated by providing a shuttle bus that is connected to tourist attractions or public transportation, this can be prepared by the `Front Office Department` of the hotels.

- Resort Hotels are widely chosen by guests who have children and babies. According to **Mags Huggins** who has worked in the tourism industry for more than 20 years, hotels need to find ways to differentiate themselves to attract guests. Many hotels have successfully marketed themselves with one of the fastest growing segments being families segments. To attract the number of guests who come, the `Housekeeper` Department as the manager of the hotel's public area, in coordination with the `Financial Department` can add facilities for children's playgrounds. And the `Sales & Marketing Department` which takes care of public relations can make eventual events such as cooking classes for kids and magic shows. Then the `Food & Beverage Department` which manages hotel F&B's can make an attractive breakfast menu choices for children. The `Department of Sales & Marketing` which is in charge of managing the hotel website can also display lots of pictures of children having fun as well as reviews from parents who bring children on the hotel website pages.

<hr>

_**Get in Touch:**_

| [Linkedin](https://www.linkedin.com/in/delabrilliano-ismail-05758715a/) | [Github](https://github.com/delabrilliano) | [Tableau](https://public.tableau.com/app/profile/delabrilliano.ismail)
<hr>
