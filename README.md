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

### **Customer Profile:**

* **Product - KP281:**

  * **Age:** Popular among young between **22 - 33 years** range.
  * **Gender:** Mostly preferred by **Females**  (**52% of all females** brought this Product whereas 38% of all males brought this product)
  * **Marital Status:** **Both** alike
  * **Fitness Level:** People with poor and average fitness (**fitness<=3**) prefer more but overall have a good control across all fitness level.
  * **Usage Level:** Average Number of **Usage <= 4** per week.
  * **Income Range:** Low, Medium and High income people (**30000<=income<= 58000**)
  * **Education:** 14-16 years mostly
  * **Miles:** popular among people who prefer to run less than 80 miles per week(**running < 80 miles**).

* **Product - KP481:**

  * **Age:** Popular among young between **24 - 33 years** range
  * **Gender:** Almost similar popularity distribution in **both** genders.
  * **Marital Status:** **both** alike
  * **Fitness Level:**  People with poor and average fitness (**fitness<=3**) prefer using this.
  * **Usage Level:** Average Number of **Usage <= 3** per week.
  * **Income Range:** Low, Medium and High income people (**30000<=income<= 58000**)
  * **Education:** 14-16 years mostly
  * **Miles:** popular among people who prefer to run less than 120 miles per week(**running < 120 miles**).

* **Product - KP781:**

  * **Age:** Popular among young between **25 - 30 years** range
  * **Gender:** Males prefer more than Females
  * **Marital Status:** **both** alike
  * **Fitness Level:** People with High fitness level like **fitness==5**
  * **Usage Level:** Average Number of **Usage >= 4** per week.
  * **Income Range:** High and Very High income people (**income>60000**)
  * **Education:** 16-18 years mostly
  * **Miles:** popular among people who prefer to run more than 120 miles per week(**running > 120 miles**).
