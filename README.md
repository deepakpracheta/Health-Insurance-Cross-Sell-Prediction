# HEALTH INSURANCE CROSS SELL PREDICTION

Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.  

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee. 

For example, you may pay a premium of Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if, God forbid, you fall ill and need to be hospitalised in that year, the insurance provider company will bear the cost of hospitalisation etc. for upto Rs. 200,000. Now if you are wondering how can company bear such high hospitalisation cost when it charges a premium of only Rs. 5000/-, that is where the concept of probabilities comes in picture. For example, like you, there may be 100 customers who would be paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalised that year and not everyone. This way everyone shares the risk of everyone else.  

Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer. 

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue. 

Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.
Health Insurance Cross Sell Prediction
AlmaBetter Verfied Project - AlmaBetter School
image

-----------------------------------------------------

## **💾 Table of Content**

Introduction

Abstract

Dataset Information

Problem Statement

Approach

Conclusion

-----------------------------------------------------

### **📖 Introduction:**

Insurance is a contract, represented by a policy, in which an individual or entity receives financial protection or reimbursement against losses from an insurance company.

This EDA will use Python libraries, matplotlib, and Seaborn to examine the Subscribed health insurance customers dataset through visualizations and graphs.

The dataset is of Subscribed Health insurance customers from insurance companies, contains information such as Age, Gender, Driving Licence, Region Etc.

Machine learning has a wide range of applications in our organization. Prediction and analysis has long been the most well-known application of machine learning, which fuels our sale prediction.

We're also utilizing machine learning to assist in designing our Sale strategies and Campaign programmes by identifying traits that lead to successful content.

We utilize it to help Company's to rapidly expand their reach to customers with appropriate data driven decisions.

We can also employ machine learning to improve Service and Customer retention, Target oriented promotions.

Our major goal in this project is to identify Customers who are interested in purchasing vehcle insurance based on subscribed health insurance data of the company.


-----------------------------------------------------

### **📖 Abstract:**

The objective was to anticipate Customers who are interested in purchasing vehcle insurance.

Exploratory Data Analysis is done on the dataset to get the insights from the information however the principal invalid qualities are taken care of. Likewise, some hypothesis testing was additionally performed from the experiences from EDA.

After that Response variable is our objective variable must be highlighted where Analysis activities are performed on it and after that visualization has done for it to understand hidden insights.

From that point forward, all that was left was to track down the important factors and feature encoding and fit our models by creating various features, and further, the model is assessed utilizing the metrics.

-----------------------------------------------------

### **📖 Dataset information:**

1. id: Unique ID for the customer

2. Gender: Gender of the customer

3. Age:  Age of the customer

4. Driving_License 0: Customer does not have DL, 1: Customer already has DL

5. Region_Code: Unique code for the region of the customer

6. Previously_Insured: 1: Customer already has Vehicle Insurance, 0: Customer doesn't have Vehicle Insurance

7. Vehicle Age:  Age of the Vehicle

8. Vehicle_Damage :1: Customer got his/her vehicle damaged in the past. 0: Customer didn't get his/her vehicle damaged in the past.

9. Annual_Premium: The amount customer needs to pay as premium in the year

10. PolicySalesChannel:  Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

11. Vintage: Number of Days, Customer has been associated with the company

12. Response:  1: Customer is interested, 0: Customer is not interested


Number of instances: 381109

Number of attributes: 12


-----------------------------------------------------

### **📖 Problem Statement:**

This dataset consists information Subscribed Health insurance customers from insurance company.

The dataset is provided by the insurance company.

They are expanding their services to vehicle insurance from Health insurance.

The task was to predict and build the model to understand the factors and customers who are interested in vehicle insurance.

It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating the factors affecting the purchase and insights from the data, will help companie to identify strategies and expand there reach to customer.

-----------------------------------------------------

### **📖Approach:**


We will divide this project into three steps for reproductive analysis.

As the first step we will be analyzing, cleaning the dataset which was provided and dropping some unnecessary column.

In the second step we are handling outliers as well as finding the distribution type of all numerical features and try to understand the skew-ness of them.

In the third step we will draw some insights after fetching all the details from all features like Age distribution, vehicle damage status and policy premium. After that we will do Feature selection and Engineering. In FE we will be using f_classification and correlation both method for Removing Some unnecessary column as well as we will do some encoding for categorical features also.

In the Fourth step we will split our data into train and test set and due to unbalance nature of our data we will use some balancing techniques on train set and after that we prepare our data for feeding  to our models for training and analyze the results of all models by comparing with each other. We will select best model among these and proceed with them further.

In the last step we will do hyper-parameter tuning for our topmost model and will see how our model behaves with different parameters. After getting best parameter for our top models we will go for feature importance method and draw the weightage of all features for our top model.

Based on above steps we will find the best model which can be good enough for predicting Response of policyholders. By using these model we can increase our marketing conversion drastically and help to move forward towards cross-selling our vehicle insurance to our policyholders. In long term cross-selling can helps customers to feel satisfied, Build loyalty and Increase earning also because if cross-selling increases customer satisfaction, you’ll save money by spending less time and resources on customer acquisition.

### **📖 Conclusion:**

Our main goal in this project was to determine different factors based on response, which we have done.

After fitting different models, we did hyperparameter tunig for better results.

which we evaluated using the different evaluation metrics.

Comparing the ROC curve we concluded that the Random Forest model performs better..

#### **Key points:**

1. Customers of age between 30 to 60 are more likely to buy insurance.

2. Customers with Vehicle_Damage are likely to buy insurance.

3. Customers with Driving License have higher chance of buying Insurance.

4. The variable such as Age, Previously_insured,Annual_premium are more affecting the target variable.

5. We can see that LGBM model preform better for this dataset.

-----------------------------------------------------
