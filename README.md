Customer Segmentation App


This is a web application built using Streamlit that performs customer segmentation using K-Means clustering. The app allows users to upload a CSV file containing customer data and dynamically select the number of clusters. Based on the clusters, the app will send personalized emails to customers based on their groupings.

Features
 - CSV Upload: Users can upload a CSV file with customer data, which is then processed for segmentation.
 - Clustering with K-Means: Users can select the number of clusters via a dropdown menu to segment customers into different groups.
 - Email Notifications: Personalized email notifications can be sent to customers based on the cluster they belong to.
 - Visualization: The app provides visual feedback, such as graphs, to represent the clusters formed.

   
Input Data
The CSV file that you upload should contain the following columns:
 - BALANCE
 - BALANCE_FREQUENCY
 - PURCHASES
 - ONEOFF_PURCHASES
 - INSTALLMENTS_PURCHASES
 - CASH_ADVANCE
 - PURCHASES_FREQUENCY
 - ONEOFF_PURCHASES_FREQUENCY
 - PURCHASES_INSTALLMENTS_FREQUENCY
 - CASH_ADVANCE_FREQUENCY
 - CASH_ADVANCE_TRX
 - PURCHASES_TRX
 - CREDIT_LIMIT
 - PAYMENTS
 - MINIMUM_PAYMENTS
 - PRC_FULL_PAYMENT
 - TENURE
 - email

   
Make sure that the file has these columns for proper functionality.
