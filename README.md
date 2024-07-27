**Project Description**

As an analyst at Crankshaft List, I am tasked with analyzing vehicle advertisements to determine factors influencing vehicle prices. I will:

1. Open and Review Data: Study the dataset at /datasets/vehicles_us.csv.
2. Data Preprocessing: Handle missing values, convert data types as needed, and add new columns for ad date details, vehicle age, and average mileage.
3. Data Enrichment: Convert the condition column to a numeric scale.
4. Exploratory Data Analysis:
   - Create histograms for parameters like price and mileage, analyze outliers, and filter the data accordingly.
   - Examine ad duration and identify trends.
   - Analyze ad count and average price by vehicle type, focusing on the top two types.
   - Determine key factors affecting vehicle prices, using boxplots for categorical variables and scatterplots for others.
5. Write a Comprehensive Conclusion: Document findings and insights in a Jupyter Notebook.

**Data Description**
The dataset contains the following columns:

    price
    model_year
    model
    condition
    cylinders
    fuel — gas, diesel, etc.
    odometer — vehicle mileage at the time of the ad
    transmission
    paint_color
    is_4wd — whether the vehicle has 4-wheel drive (Boolean)
    date_posted — date when the ad was posted
    days_listed — number of days the ad was listed until removal
