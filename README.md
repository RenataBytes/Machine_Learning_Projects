# **Marketing Spend Optimization using Machine Learning in Python**

# **Introduction**

A company specializing in B2C sales (product: Data Science and Data Engineering related courses) spends significant money on marketing campaigns across various channels such as social media, email, and search advertising. More information on marketing sources can be found in the data column “Marketing Source”. The marketing team faces challenges in optimizing the marketing budget allocation across these channels to maximize revenue and return on investment (ROI).<br><br>
This project aims to develop a data-driven approach to optimize the marketing budget allocation across various channels to maximize revenue and ROI. By using machine learning algorithms, the marketing team can make informed decisions about allocating the marketing budget based on predicted revenue and ROI.

### **Business Impact of Marketing Budget Optimization**


**Increase product conversions**: Marketing Budget Optimization leads to righ user targeting through right channels/assets which leads to better conversions.



**Increase revenue**: Increased conversions(as mentioned in point above) will lead to more revenue or buyer engagement. For example, if the company is able to target a user who is more active on Instagram, chances are more that he/she will click on the Ad and add the product to cart. So overall probability of an order increases and hence the revenue.



**Improve budget allocation**: Over budgeting on non-efficient channels lead to waste of marketing money without getting enough revenue.

**Improve Customer Acquisition Cost**: Customer Acquisition Cost(CAC) improves if right targeting channels are used for a customer often leading to better repeat rates as well.


## **Approach**


We are treating this problem as an supervised learning problem. So every data point will have a target variable for the model to learn the dependencies and predict on the unknown.


In real life, this model would tell the business whether a user is likely to engage with the ad or not and that would in turn help the company to allocate budgets accordingly.


Given our assumptions about the data, we will build a prediction model based on the historical data. Simplifying, here's the logic of what we'll build:


1. We'll build a model to identify if a customer will be interested in the lead;
2. We'll use various tree based model and compare their performance on interest prediction;
3. We will then choose the most successful model to use in production;

* Exploratory Data Analysis (EDA):
  * Understand the features and their relationships with target variables
  * Check for missing or invalid values and their imputation


* Data Preprocessing:
  * Encode the variables using label encoding
  * Split the dataset into training and testing sets

* Model Building and Testing:
  * Random Forest
  * Light Gradient Boosting
  * Extreme Gradient Boosting


<details>
    <summary>Click here to view more</summary>

# **Execution Instructions**

### **Installation and Setup for IPYNB**

For the best experience, please stay connected to the internet while executing this Project



#### **Installing Jupyter with pip**
If pip is installed on your local machine, you can install Jupyter.

Here are the steps:
* Open the command prompt (Windows) or terminal (Mac/Linux).
* Install Jupyter with pip by running the following command `pip install jupyter`
* Launch Jupyter Notebook by running the following command `jupyter notebook`

#### **Installing Jupyter with Conda**

* Download and install Anaconda from the official website: https://www.anaconda.com/products/individual.
* Open the Anaconda Navigator App and launch Jupyter Notebook
* Running IPYNB in Jupyter Notebook
* Open Terminal / Command Prompt and Navigate to the notebooks directory using cd
* Launch Jupyter Notebook by running the following command jupyter notebook
* This will open a browser window displaying the Jupyter interface.
* Click on the IPYNB file you want to open.
* To execute all the cells in the notebook, click on the "Cell" menu and choose "Run all".
* Alternatively, you can execute each cell individually by clicking on the "Play" button next to the cell.



# Executing the project via Modular Code
* Install the dependencies using the command, navigate to the **Marketing Spend Optimization using Machine Learning in Python** directory where the requirements.txt file exists, and run ***pip install -r requirements.txt*** in the terminal/CMD.


