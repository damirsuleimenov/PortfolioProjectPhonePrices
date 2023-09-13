<h1>Data Analysis Portfolio Project 1. Mobile Phone Prices</h1>

<h2>Using a Kaggle dataset for Data cleaning, Feature engineering, Exploratory data analysis and exporting it to Power BI to create a dashboard.</h2>

**Skills used:**

+ Pandas
+ Numpy
+ Matplotlib
+ Seaborn
+ Power BI

Link to the Kaggle dataset: https://www.kaggle.com/datasets/rkiattisak/mobile-phone-price

This dataset contains information on the prices of several mobile phones from different brands. It includes details such as the storage capacity, RAM, screen size, camera specifications, battery capacity, and price of each device.

The raw dataset looks as follows:

<img src="dataset_raw.JPG" alt="image" width="300" height="auto">

1. Checking for missing values, duplicates, datatypes of the features and shape of the dataset.
2. Applying Feature Engineering on the features. One of the instances looks as follows:

<img src="feature_engineering.JPG" alt="image" width="300" height="auto">

Using regex, I extracted each camera and distributed them into new columns. Where there were fewer than 4 cameras, empty values were filled with "NaN."

3. The final appearance of the cleaned dataset:

<img src="dataset_clean.JPG" alt="image" width="300" height="auto">

4. Conducting EDA:

<div style="display: flex; justify-content: space-between;">
    <img src="p1.JPG" alt="Image 1" width="45%" height = "300">
    <img src="p5.JPG" alt="Image 2" width="45%" height = "300">
</div>

<div style="display: flex; justify-content: space-between;">
    <img src="p2.JPG" alt="Image 1" width="45%" height = "100">
    <img src="p4.JPG" alt="Image 2" width="45%" height = "100">
</div>

<div style="display: flex; justify-content: space-between;">
    <img src="p3.JPG" alt="Image 1" width="45%" height = "300">
    <img src="p6.JPG" alt="Image 2" width="45%" height = "300">
</div>

