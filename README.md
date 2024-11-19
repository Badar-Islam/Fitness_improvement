# Customer Profiling of Aerofit Trade Mill

## **Business Problem**
The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.

**Product Portfolio:**

- The KP281 is an entry-level treadmill that sells for $1,500.

- The KP481 is for mid-level runners that sell for $1,750.

- The KP781 treadmill is having advanced features that sell for $2,500

## Objective:

We will use count of users, probabilities, conditional probabilities to evaluate the users and create a customer profile for each product

## Column Profiling:

|Feature |	Description|
|--------|-------------|
|Product |	Product Purchased: KP281, KP481, or KP781|
|Age |	Age of buyer in years|
|Gender |	Gender of buyer (Male/Female)|
|Education |	Education of buyer in years|
|MaritalStatus |	MaritalStatus of buyer (Single or partnered)|
|Usage |	The average number of times the buyer plans to use the treadmill each week|
|Income |	Annual income of the buyer (in $)|
|Fitness |	Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape|
|Miles |	The average number of miles the buyer expects to walk/run each week|

## Concepts Used:
- Uni-Variate Analysis
- Bi-Variate Analysis
- Marginal Probability
- Conditional Probability

## Task Performed:
- Loaded the dataset and performed basic EDA to understand its characterstics and structure.
- Performed data Cleaning like missing value handling, checking for duplicate values, fixing Structural Errors, handling outliers etc.
- Performed non graphical analysis such as descriptive analysis, frequency distribution, correlation analysis etc.
- Visualizations :
    - Uni-Variate Analysis (distribution plots of all the continuous variable(s) barplots/countplots of all the categorical variables)
    - Bivariate (Relationships between important variables such as gender and product)
- For continuous variable(s): Distplot, countplot, histogram for univariate analysis
- For categorical variable(s): Boxplot
- For correlation: Heatmaps, Pairplots
- Performed Cross-tabulation of Product against all other features, based on observation created the profile.
