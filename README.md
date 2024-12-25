# Google Play Store Apps Analysis

**Introduction:**
This data analysis project focuses on exploring and understanding the Google Play Store Apps dataset. The dataset is loaded into a Pandas DataFrame using Python, and various data analysis tasks are performed to gain insights into the characteristics of the apps available on the Google Play Store.

**Dataset Overview:**
The dataset consists of 10,841 entries and 13 columns, each representing different attributes of the apps. These attributes include the app name, category, rating, number of reviews, size, number of installs, type (free or paid), price, content rating, genres, last updated information, current version, and Android version compatibility.

**Basic Data Exploration:**
The initial steps involve displaying the top 5 and last 3 rows of the dataset to get a glimpse of the data. Additionally, the shape of the dataset is explored, revealing that it contains 10,841 rows and 13 columns.

**Dataset Information:**
The `info()` function is used to obtain information about the dataset, including the total number of non-null entries, data types of each column, and memory usage. This information aids in understanding the structure of the dataset and identifying any missing values.

**Descriptive Statistics:**
Descriptive statistics, such as mean, count, and other summary statistics, are generated using the `describe()` function. This provides an overall statistical overview of the numerical columns in the dataset.

**Specific Data Analysis Tasks:**
   - The dataset is filtered to find the total number of app titles containing the term "Astrology."
   - The average app rating is calculated.
   - The total number of unique app categories is determined.
   - The app category receiving the highest average ratings is identified.
   - The total number of apps with a 5-star rating is calculated.
   - The average value of reviews is computed, considering a case where reviews are represented in millions.
   - The total number of free and paid apps is counted.
   - The app with the maximum number of reviews is identified.
   - The top 5 apps with the highest number of reviews are displayed.
   - The average rating of free and paid apps is calculated.
   - The top 5 apps with the maximum number of installs are displayed.

**Conclusion:**
Through this data analysis project, we gain valuable insights into the Google Play Store Apps dataset. We explore various aspects such as app categories, ratings, reviews, and installs. These findings can be beneficial for app developers, marketers, and analysts aiming to understand trends and patterns in the Google Play Store ecosystem.
