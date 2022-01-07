# BikeShareDC

# Defining the Problem and Project Goal
Owner of bike rental shop  give me this data and want build app to use and optimize Machine Learning models that effectively predict the number of rentals bikes that will be used in any given 1 hour time-period, using available information about that time/day.

### Price Comparison
**- Per-minute rate for bikes**
* casual  0.15 USD/ minute
* registered 0.10 USD/ minute<br>


**- Unlock fee for classic bikes**
* casual  1 USD 
* registered 0 USD <br>

**Reference**
https://www.capitalbikeshare.com/pricing/day-passes

## Data Fields

1. **datetime** - hourly date + timestamp  
2. **season** -  1 = spring, 2 = summer, 3 = fall, 4 = winter 
3. **holiday** - whether the day is considered a holiday
4. **workingday** - whether the day is neither a weekend nor holiday

5. **weather**.<br>
     <b>1</b>: Clear, Few clouds, Partly cloudy, Partly cloudy<br>
     <b>2</b>: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist<br>
     <b>3</b>: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds<br>
     <b>4</b>: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog <br>
    
6. **temp** - temperature in Celsius
7. **atemp** - "feels like" temperature in Celsius
8. **humidity** - relative humidity
9. **windspeed** - wind speed
10. **casual** - number of non-registered user rentals initiated
11. **registered** - number of registered user rentals initiated
12. **count** - number of total rentals
## We want analyze this  Data to answer  below questions :

**Questions**
1. Calculate Profit  ( Assuming the customer only rented the bike for one hour and the hourly rental price is correct )
    - Each registered user rent bike for 6 USD/hour. 
    - Each casual user rent for 9 USD/hour plus 1 USD for unlock bike.
    - Taxis 6.5%  https://mrsc.org/Home/Explore-Topics/Finance/Revenues/Sales-and-Use-Taxes.aspx
    - Maintenance 1200 USD/year
2. Distribution total rentals & profit
3. Profit for each day
4. which season that more registeration & profit.
5. which weather condition that has more registeration & profit.
6. Correlation between profit & bikes count with all features
7. Rentals during rush hours (7-9 am & 3-5 pm).
8. Registered or casual is more ?
9. Is Schools days (9-12) & (2-6) effect in  profit?
10. Which months the highest profit and rental bikes ?
