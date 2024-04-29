# Linear Regression Model on E-Commerce Clients
------


This project aims to identify the primary factors influencing a customer's annual expenditure with the E-commerce company.  

In this project we work with a dataset [available on Kaggle](https://www.kaggle.com/iyadavvaibhav/ecommerce-customer-device-usage/notebooks). The data includes information about customers of an e-commerce website, including the following:
- Avg. Session Length: Average session of in-store style advice sessions.
- Time on App: Average time spent on App in minutes
- Time on Website: Average time spent on Website in minutes
- Length of Membership: How many years the customer has been a member.

In this project, we suppose that the company is trying figure out which of their services and platforms has a significant impact on increasing their yearly memberships. They are trying to decide on which platforms and services they should focus on in order to drive their sales and revenue. We are here to help them make a data-driven decision  


--------
# Model Accuracy = 98.3%  
-------  
# Findings:-  
From the coefficients obtained through linear regression analysis, we can draw several conclusions about the relationship between the features and the target variable (Yearly Amount Spent) in the context of the E-commerce website:

* Length of Membership has the strongest positive impact: With a coefficient of 61.595628, it indicates that for each additional year a customer remains a member, there is an increase of approximately $61.60 in the yearly amount spent on the website. This suggests that customer loyalty plays a significant role in driving spending.  

* Time on App also has a strong positive impact: The coefficient of 38.732596 suggests that for each additional minute spent on the app, there is an increase of approximately $38.73 in the yearly amount spent. This implies that the app is effective in engaging customers and encouraging them to spend more.  

* Avg. Session Length has a moderate positive impact: With a coefficient of 25.760993, it suggests that longer average session lengths for in-store style advice sessions lead to an increase in yearly spending. This indicates that providing quality in-store advice sessions can positively influence customer spending behavior.  

* Time on Website has the weakest impact: The coefficient of 0.431734 indicates that the impact of time spent on the website on yearly spending is relatively low compared to the other features. This could suggest that the website may not be as effective as the app in driving sales or engaging customers. Another reason might be that website users are getting converted to app-users because of the convinience and ecosystem of an app based service. 

Overall, the model suggests that customer engagement through the app and fostering long-term loyalty are key drivers of spending on the E-commerce platform. The company may want to focus on enhancing the app experience and implementing strategies to retain and reward loyal customers to maximize revenue. Additionally, the company should analyse its website performance on a more granular level in order to increase its effectiveness. The website is always going to be a valuable asset and the company should take every measure to maintain it and adopt new features and services to match the current market standards.
