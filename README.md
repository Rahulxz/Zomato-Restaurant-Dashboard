# Zomato-Restaurant-Dashboard

The Zomato restaurants dataset is a collection of information about various restaurants listed on the Zomato platform. It typically includes details like the restaurant's name, location (country and city), types of cuisines offered, average cost for two people, and customer ratings. This data helps analyze trends in restaurant popularity, dining preferences, and overall performance across different regions.
Understanding the data structure is crucial because it informs how you clean, transform, and ultimately visualize the information. While the exact columns and their names may vary based on the data source, the following breakdown illustrates a common schema used in many Zomato analysis projects.

************************************************************************************************************************************************

**Dataset Link** 
https://docs.google.com/spreadsheets/d/1GJ_G5R_3Y9vaDDa7k3jw04eFPveUhDDI/edit?usp=sharing&ouid=103329149026583857575&rtpof=true&sd=true

**************************************************************************************************************************************************

**Sample Dataset Structure**

**Restaurant ID**
Description: A unique identifier for each restaurant.
Example: 12345

Usage: Primary key for referencing each restaurant record.

**Restaurant Name**
Description: The official name of the restaurant.
Example: “The Great Indian Diner”

Usage: Display in visuals (tables, charts) and for labeling.

**Country**
Description: The country where the restaurant is located.
Example: “India,” “Australia,” “USA”

Usage: Grouping and filtering (slicers), especially if you want to see data by region.

**City**
Description: The city where the restaurant is located.
Example: “New Delhi,” “Sydney,” “New York”

Usage: Used for bar charts, slicers, and city-level analysis.

**Address (optional)**
Description: The full address of the restaurant.
Example: “123 Main Street, Connaught Place”

Usage: Sometimes used in maps or for further geospatial analysis.

**Locality (optional)**
Description: A more granular neighborhood or locality within the city.
Example: “Connaught Place”

Usage: Similar to City, but more detailed. Can be used in maps or sub-region analysis.

**Latitude / Longitude (optional)**
Description: Geographic coordinates of the restaurant.
Example: 28.6325 (Latitude), 77.2186 (Longitude)

Usage: For mapping visualizations (e.g., Power BI Maps).

**Cuisines**
Description: One or multiple cuisines offered by the restaurant.
Example: “Italian, Chinese,” “North Indian, Mughlai”

Usage: Often used to see which cuisines are most popular or to filter restaurants by cuisine type.

**Average Cost for Two**
Description: The average cost of a meal for two people at the restaurant (often in local currency).
Example: 800 (Indian Rupees)

Usage: Comparisons between restaurants’ price points; correlation with ratings.

**Currency (optional)**
Description: The currency in which the average cost is specified.
Example: “Indian Rupee (INR),” “Dollar (USD)”

Usage: If you have a global dataset, you can convert or filter by currency.

**Has Table Booking**
Description: Indicates whether the restaurant allows table bookings (Yes/No or True/False).
Usage: Visualize the proportion of restaurants offering table reservations.

**Has Online Delivery**
Description: Indicates whether the restaurant offers online delivery (Yes/No or True/False).
Usage: Visualize how many restaurants provide delivery; filter the dataset for online delivery analysis.

**Aggregate Rating (Average Rating)**
Description: The restaurant’s average rating (often on a scale from 1.0 to 5.0).
Usage: Key metric for quality; used in KPI cards, bar charts, correlation with cost, etc.

**Rating Text (optional)**
Description: A textual representation of the rating (e.g., “Excellent,” “Good,” “Average”).
Example: “Excellent” for 4.5+

Usage: Adds context to the numeric rating; can be used for grouping.
**Votes**
Description: Number of votes or reviews the restaurant has received.
Usage: Another KPI metric to show popularity; can correlate with rating or cost.
Other Possible Fields

**Review Count**: Total number of reviews.

**Opening Hours:** Hours of operation.

*****************************************************************************************************

**Quick Checklist**

**Data Import**
 Correct file format and location
 
 Data columns verified
 
**Data Cleaning**
 
 Removed duplicates
 
 Set correct data types
 
 Renamed columns for clarity
 
**KPIs**

 Created Card visuals for main metrics
 
**Visualizations**

 Bar/Column chart for City or Country
 
 Combination chart for Cuisine count vs. Rating
 
 Donut charts for Table Booking, Online Delivery
 
 (Optional) Scatter chart for Cost vs. Rating
 
**Slicers/Filters:**
 Country, City, Cuisine
 
**Formatting**
 Dashboard title and text boxes
 Consistent color theme and layout

**Insights**
 Identify patterns, top/bottom metrics, correlations
