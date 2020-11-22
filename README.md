Project 2
MARKETING DEPARTMENT
* Marketing is crucial for the growth and sustainability of any business.
* Maketers can help build the compnayh's brand engaged customers grow revenue and increase sales
* One of the Key pain point for marketers is know their customers and identifiy their needs
* By understanding the customer marketing campaign is the tailored for their specific needs
* If the data about the customers is available data science can be applied to perform market sigmentation.
* In this case study you are working as a consultant to a bank in the NewYork city. The bank has extensive data about their customers for the past six months, the marketing team at the bank wanted to launch a targeted Ad marketing campaign by deviding the customers into at least threee distinctive groups.


#TASK#1 UNDERSTAND THE PROBLEM STATEMENT AND BUSINESS CASE

1. **GROWTH**: Marketers empower business growth by reaching new customers.
2. **EDUCATION**: Marketers educate and communicate value proposition to customers.
3. **DRIVE SALES**:  Marketers drvie sales and traffic to products/Services.
4. **ENGAGEMENT**: Marketers engage customers and understand their needs.


### **Data Set Details Based on CSV File:** 

* **CUST_ID**: Identification of CrditCard Holder.
* **BALANCE**: Balance Amount Left in customer's account to make purchase.
* **BALANCE_FREQUENCY**: How frequently the balance is updated, score between 0 and 1 (1 = frequntly updated, 0 = not frequently updated).
* **PURCHASES**: Amount of purchases made from account.
* **ONEOFF_PURCHASES**:Maximum purchase amount done in one-go.
* **INSTALLMENTS_PURCHASES**:Amount of purchases done in installment. 
* **CASH_ADVANCE**: Case in advance given by the user.
* **PURCHASES_FREQUENCY**: How frequently the purchases are being made, score between 0 and 1 (1 = Frequently purchased, 0 = not frequently purchased).
* **ONEOFF_PURCHASES_FREQUENCY**:How frequently purchases in installments are being done( 1 =  frequently done, 0 = not frequently done)
* **PURCHASES_INSTALLMENTS_FREQUENCY**: How freqnetly purchases in installments are being done ( 1= frequently done, 0 = not frequently done)
* **CASH_ADVANCE_FREQUENCY**: How freqently the cash in advanced being paid.
* **CASH_ADVANCE_TRX**: Number of Transactions made with "Cash in Advance" 
* **PURCHASES_TRX**: Number of purchases transations made.
* **CREDIT_LIMIT**: Limit of CreditCard for user. 
* **PAYMENTS**: Amount of Payment done by the user. 
* **MINIMUM_PAYMENTS**: Minimum amount of payments made by user. 
* **PRC_FULL_PAYMENT**: Percent of full payment paid by user. 
* **TENURE**: Tensure of CreditCard service for user. 

### **Visualization Process**
* **Distplot combines the matplotlib.hist function with Seaborn kdeplot()**
* **KDE plot represents the "Kernal Density Estimate"**
* **KDE is used for visualizing the Probability Density of a Continuous Variable**
* **KDE demonstrates the Probability density at different values in a continuous variable.**

**Analysis:**
* Mean of balance is 1500
* BALANCE_FREQUENCY for most customers is updated frequently 1
* For 'PURCHASES_FREQUENCY' there are two distinct group of customers
* For "ONEOFF_PURCHASES_FREQUENCY" and "PURCHASES_INSTALLMENTS_FREQUENCY" most user don't do one of the purchase or installment purches frequently.
* Very small number of customers pay their balance in full "PRC_FULL_PAYMENT" 
* Credit limit average is around ~$4500
* Most customers are 11 years tensure

###**TASK #4: UNDERSTAND THE THEORY AND INTUITON BEHIND K-MEANS**

###TASK #5: **FIND THE OPTIMAL NUMBER OF CLUSTERS USING ELBOW METHOD**

- The elbow method is a heuristic method of interpretation and validation of consistency within cluster analysis designed to help find the appropriate number of clusters in a dataset. 
- If the line chart looks like an arm, then the "elbow" on the arm is the value of k that is the best.
- Source: 
  - https://en.wikipedia.org/wiki/Elbow_method_(clustering)
  - https://www.geeksforgeeks.org/elbow-method-for-optimal-value-of-k-in-kmeans/
  
  
### TASK#6 APPLY K-MEANS METHOD 
* **Part-I**: 

### TASK#7: APPLY PRINCIPAL COMPONENT ANALYSIS AND VISUALIZE THE RESULTS


#### TASK#8: UNDERSTAND THE THEORY AND INTUITION BEHIND AUTOENCODERS


### TASK #9: APPLY AUTOENCODERS (PERFORM DIMENSIONALITY REDUCTION USING AUTOENCODERS)



Code and Resources Used:

Python Version: 3.7 Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium, flask, json, pickle Sources: https://towardsdatascience.com/confusion-matrix-for-your-multi-class-machine-learning-model-ff9aa3bf7826

https://opendatascience.com/how-does-the-random-forest-algorithm-work-in-machine-learning/

Google Colab

https://towardsdatascience.com/

https://www.udemy.com/
