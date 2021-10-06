# CMPE-255 Data Cleaning Assignment


**Name: Sarjak Patel  </br>
SJSU ID:- 015945046**

Dataset :- https://www.kaggle.com/austinreese/craigslist-carstrucks-data

About Dataset: </br> 

Craigslist is the world's largest collection of used vehicles for sale. This data is scraped every few months, it contains most all relevant information that Craigslist provides on car sales including columns like price, condition, manufacturer, latitude/longitude, and 21 other categories.

Rows : 426880 </br>
Columns : 26

Columns in the dataset :
 - id
 - url
 - region
 - region_url
 - price
 - year
 - manufacturer
 - model
 - condition
 - cylinders
 - fuel
 - odometer
 - title_status
 - transmission
 - VIN
 - drive
 - size
 - type
 - paint_color
 - image_url
 - description
 - county
 - state
 - lat
 - long
 - posting_date


Here, I have handled all the null values that are present in the dataset using "mean", "mode", "forward fill" methods also dropped some.

I have also handled the outliers and remove them as well.

Also, I have done **Exploratory Data Analysis(EDA)** and from which you can derive some conclusions from the dataset.

Also, I have trained a **RandomForestRegressor model** over a trainning data which accurately predict 88% of the test data.




- **Data Cleaning in OpenRefine:**

I have atttached a PDF document containing the screenshots of each step of Data Cleaning performed in OpenRefine and it also contains its description and steps wherever needed.
