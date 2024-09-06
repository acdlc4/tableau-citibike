# tableau-citibike

### Background
In a virtual context, the task at hand is to use Tableau and other data analysis tools to 'generate regular reports for city officials looking to publicize and improve the city program.'

### Analysis

![2023 Bar Graph]()
#### 2023 Monthly Ride Count vs. Average Daily Temperature:
    Provide more bikes during the months of April through November
The viz shows the volume of rides initiated by month set against the average monthly temperature in NYC.  As seen in the viz, the volume of Citi Bike usage gradually increases from a low in February 2023 through peak monthly usage in August 2023, with an overall increase during that period of 2.26M/month which is a 133% increase.  During that same period, the average monthly temperature rises by 34.1°F.

![Stations Map]()
#### - Starting Stations Use - Feb23 vs Aug23
    Consolidate open bike stations during the colder months, like February, and use the low census period for bike and station maintenance

The viz maps out all of the individual Citi Bike locations for the months of February 2023 (month of lowest Citi Bike use) and August 2023 (month of highest use).  This viz allows the user to select between the two months via a toggle on the top right of the page to map the most used stations for those months.  The viz also provides a listing of the top ten most popular stations for each month, which completely changes as no stations in each top ten exists in the other.  This is due to the differences in average temperatures and riders searching for the available bikes closer to their start points and the fact that Lyft consolidates stations being used due to lower overall use (Aug23 stations = 1450 vs. Feb23 stations = 519).

![Hourly Ride Count by Bike Type]()
#### - August 2023 Ride Count by Hour by Bike Type
    Use the AM hours to redistribute and maintain bicycles to make sure bikes are available for the daily PM rush
This visualization provides the hourly rider use for the month of August 2023 along with bike type use.  From this, we can see highest overall use from 8AM through 9PM and from the pie chart provided, only 30.2% of ride starts begin in the morning hours (i.e. 12AM - 12PM).  In addition to the preference of starting rides after 12PM, the viz provides information that outlines rider preference of bike types (classic vs. electric) overall and per hour.  As is seen, overall use shows a minimal preference for electric bikes over the classic bikes by 2.6%, which is not significant.  The preference for electric bikes largely seen during the hours of 7PM up to 8AM.

##
### Vizualization Location
- https://public.tableau.com/app/profile/adrian.de.la.cruz/viz/citibike_17249716605930/Story

### Data Sources
#### Citi Bike Summary
- https://citibikenyc.com/system-data

#### Citi Bike Direct Source
- https://s3.amazonaws.com/tripdata/index.html

#### NYC Weather Data
- https://weather.visualcrossing.com/VisualCrossingWebServices/rest/services/retrievebulkdataset?&key=5PMLT687G7E4UUPDFWHGBS65E&taskId=fddeeb92e1b44b29110cea886ac37872&zip=false

##
### Any questions?

Feel free to send a message to acdlc4@gmail.com with any questions / comments. Inspiration and credit for any code used is from work done during my attendance in the 2024 Northwestern University Data Analysis Bootcamp class sessions.
