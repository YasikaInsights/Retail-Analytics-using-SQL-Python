# Python Project: Retail-Analytics

# Process :

# First Process:
To analyze marketing trend right data and accurate records plays a vital role. Understanding customers behavior, needs, style of purchase helps in marketing strategies and target audience.
Customer, Product and Transaction data can be used to track customer history and future purchasing and can identify most repeated customers and sales by Customers ID’s(Unique identification) with purchasing records.
Customer segmentation based on demographics, customer behavior and business requirements can offer customized services to provider by their satisfaction.
To ensure that marketing efforts are backed by certain trends rather than assumptions analyzing marketing data can have benefits for data-driven decision making, segmentation and marketing, campaigns, budget allocation, real-time monitoring and improve customer experience.
This SQL analysis can be a great turn over for ROI can lead to higher conversion rates and customer retention.
Predictive analytics can boost businesses to focus on future trends by optimizing stock levels and can reduce wastage.

# Second Prcoess:
The process begins with data extraction and transformation, ensuring consistency and accuracy. It then progresses through statistical analysis, time-dependent data modeling, and visualization techniques to understand key retail patterns. The creation of DEPVAR (Total Amount per Transaction) and statistical aggregation allows for a deeper analysis of sales trends and consumer behavior.
By following this structured approach, businesses can enhance marketing strategies, improve decision-making, and optimize product offerings based on data-driven insights

# Third Porcess:
In this analysis, we aim to predict the Total Amount per Transaction (referred to as DEPVAR) based on a dataset of marketing transactions. This dataset contains information about product quantities, prices, and other relevant features that can influence the total amount spent by a customer.
Understanding how different variables affect DEPVAR is critical for effective data-driven marketing strategies. By identifying the best predictor for DEPVAR, we can develop a more accurate model that allows businesses to forecast total transaction amounts, optimize pricing strategies, and improve marketing efforts.
This analysis follows a structured approach, combining Exploratory Data Analysis (EDA) to understand the distribution and relationships between variables, with a Linear Regression model to predict DEPVAR based on the most impactful independent variable.
Key Objectives:
To explore and understand the dataset through EDA techniques.
To identify outliers and important relationships between variables.
To predict DEPVAR using Linear Regression and evaluate model accuracy.
To develop actionable insights for marketing and business decision-making.
The outcome of this analysis will assist in improving predictive capabilities, enabling more informed decisions based on transaction data.

# Fourth Prcoess:
The primary objective of this project is to develop a robust Multiple Linear Regression model that predicts DEPVAR based on various demographic, behavioral, and transactional factors captured in the marketing dataset. Before building the predictive model, extensive Exploratory Data Analysis (EDA) was conducted, which included computing quartile distributions, identifying left and right outliers, and evaluating correlations among numeric variables using a heatmap. Cross-tabulation analyses were performed for categorical features to understand the relationship between independent variables and DEPVAR.
To ensure the quality of predictors, techniques such as Variance Inflation Factor (VIF) analysis and Backward Elimination were used to address multicollinearity and refine the model by selecting statistically significant features. The final model was trained and tested using a standard data split and was evaluated based on key metrics such as Root Mean Squared Error (RMSE) and R-squared (R²) to assess its performance and reliability.
Visualization of the actual versus predicted DEPVAR values further validates the model’s accuracy. Overall, this project highlights the systematic process of data-driven model development, providing actionable insights into the factors influencing customer spending, which can be leveraged for more targeted marketing strategies.
 
<img width="793" height="566" alt="image" src="https://github.com/user-attachments/assets/9364ac7e-abcd-48d8-b32b-53b2f9fe044f" />
<img width="795" height="572" alt="image" src="https://github.com/user-attachments/assets/5716a7d3-673e-4650-ae21-4394d12e7459" />
<img width="755" height="573" alt="image" src="https://github.com/user-attachments/assets/55fd8bef-264d-4d95-a241-d01a07daa5b7" />
<img width="735" height="567" alt="image" src="https://github.com/user-attachments/assets/61bc64e1-8272-44b9-8d71-3b3348b9b3a7" />
<img width="757" height="555" alt="image" src="https://github.com/user-attachments/assets/9c92a2cf-8f5a-463a-81e0-db36ef1d243b" />
<img width="792" height="570" alt="image" src="https://github.com/user-attachments/assets/e0262a36-c3cc-48db-9fad-8fcdf85cff14" />
<img width="798" height="577" alt="image" src="https://github.com/user-attachments/assets/5f39ae04-8717-4a16-a0be-5b783e084af3" />
<img width="1196" height="651" alt="image" src="https://github.com/user-attachments/assets/15163504-9989-477e-bbbf-247a99379fa3" />

# Visualization of the model performance: Scatter plot and trend line :
<img width="822" height="578" alt="image" src="https://github.com/user-attachments/assets/335b8ab4-b42c-4a5b-84e1-484e93073881" />

# Exploratory Data Analysis: Distribution of each independent variable based on DEPVAR :
<img width="1192" height="780" alt="image" src="https://github.com/user-attachments/assets/c97079d6-7260-40c2-b2c9-2932ab867b81" />

# PairPlot Analysis:
<img width="1192" height="780" alt="image" src="https://github.com/user-attachments/assets/0981801a-ff51-4f80-8609-12e3a3384da6" />

# Multiple Linear Regression
<img width="1024" height="965" alt="image" src="https://github.com/user-attachments/assets/212d4ced-3e03-4149-be76-21b6c7b1162f" />
<img width="1148" height="1028" alt="image" src="https://github.com/user-attachments/assets/18e89db5-84bc-4961-99a5-203d6fa710df" />
<img width="975" height="527" alt="image" src="https://github.com/user-attachments/assets/0a860cd0-ce05-4f4f-b745-fdd0fd018335" />
<img width="975" height="527" alt="image" src="https://github.com/user-attachments/assets/bfa82122-0745-407e-a6c0-219c04e01511" />
<img width="1232" height="492" alt="image" src="https://github.com/user-attachments/assets/b30df0db-ad72-42c6-a7dc-09b480bc2c95" />
# Final Multilinear plot
<img width="1232" height="492" alt="image" src="https://github.com/user-attachments/assets/a74235bf-8791-4029-ae4d-6125c76ae974" />
