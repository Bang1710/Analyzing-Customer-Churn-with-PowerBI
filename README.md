# 📝 Analyzing Customer Churn in Power BI
## I. Description
For subscription-based businesses, reducing customer churn is a top priority. In this Power BI case study, you'll investigate a dataset from an example telecom company called Databel and analyze their churn rates. Analyzing churn doesn’t just mean knowing what the churn rate is: it’s also about figuring out why customers are churning at the rate they are, and how to reduce churn. You'll answer these questions by creating measures and calculated columns, while simultaneously creating eye-catching report pages.

## II. Dataset
### > Table ```Customer Status```

| Field          | Description                                      |
| -------------- | ------------------------------------------------ |
| Customer ID    | The unique ID that identifies a customer         |
| Churn Label    | Contains "Yes" or "No" to indicate churn status   |
| Churn Reason   | The reason why the customer ended the contract    |
| Churn Category | Groups multiple churn reasons for analysis       |

### > Table ```Demographics```

| Field        | Description                                       |
| ------------ | ------------------------------------------------- |
| Gender       | The gender of the customer (Male/Female/Prefer not to say) |
| Under 30     | Indicates if the customer is under 30 (Yes/No)    |
| Senior       | Indicates if the customer is 65 or above (Yes/No) |
| Age          | The age of the customer                            |

### > Table ```Contract Information```

| Field                  | Description                                          |
| ---------------------  | ---------------------------------------------------- |
| Contract Type          | Contains "Month-to-Month", "One Year" or "Two Year"  |
| Payment Method         | Preferred payment method of the customer             |
| State                  | The code of the state where the customer lives       |
| Phone Number           | Phone number of the customer                         |
| Group                  | Indicates if the customer is part of a group contract (Yes/No) |
| Number of Customers in Group | Number of customers part of the group          |

### > Table ```Subscription Types & Charges```

| Field                     | Description                                           |
| ------------------------- | ----------------------------------------------------- |
| Account Length            | The number of months the customer has been with Databel |
| Local Calls               | Amount of local (within the US) calls from the customer |
| Intl Calls                | Amount of international (outside the US) calls from the customer |
| Intl Mins                 | The number of minutes spent calling internationally. Intl Active: Indicates if the customer called internationally with a "Yes" or "No" |
| Intl Plan                 | Indicates if the customer has a premium plan to call internationally for free with "Yes" or "No. This premium is reflected in the amount of the monthly charge. |
| Extra Intl Charges        | Contains the extra charges for international calls for customers who are not on an international plan |
| Customer Service Calls    | The number of calls made to customer service           |
| Avg Monthly GB Download   | Contains the average monthly download volume in gigabytes |
| Unlimited Data Plan       | Indicates if the customer has free unlimited download capacity with "Yes" or "No". This premium is reflected in the amount of the monthly charge |
| Extra Data Charges        | Contains the extra charges for data downloads for customers who are not on an unlimited plan |
| Monthly Charges           | Average of all Monthly Charges to the customer         |
| Total Charges             | Sum of all monthly charges                             |

## III. Data analysis flow in Power BI
### 1. Data Check
+ Check for duplicate or missing values
+ Do a sense check with other internal data sources
### 2. Explore Data
+ Ask yourself the right questions
+ Build your first visualizations
### 3. Analyze & Visualize Data
+ Choose the right visualization to convey a message
+ Perform more advanced analysis
### 4. Dashboarding
+ Combine visualizations in one or more dashboards
### 5. Communicate Insights
+ Communicate your insights to stakeholders
## IV. The Problem
### 1. Solving customer churn
+ A fictitious dataset about churn from a Telecom provider (Databel)
+ Your task: discover why customers are churning
### 2. Defining churn
The churn rate, also known as the rate of attrition or customer churn, is the rate at which customers stop doing business with an entity.
+ Leaky bucket problem
+ Keeping customers is easier than getting new customers
+ Reducing churn is a priority for many companies

## V. Insights discovered so far
+ The churn rate for Databel is ~27%.
+ ~45% of the reasons why customers churn is related to competitors.
+ The churn rate in California is abnormally high (>60%).

## VI. Dashboard
![Dashboard part 01](https://github.com/Bang1710/Analyzing-Customer-Churn-with-PowerBI/blob/main/Dashboard/DB1.png)
![Dashboard part 02](https://github.com/Bang1710/Analyzing-Customer-Churn-with-PowerBI/blob/main/Dashboard/DB2.png)
![Dashboard part 03](https://github.com/Bang1710/Analyzing-Customer-Churn-with-PowerBI/blob/main/Dashboard/DB3.png)
