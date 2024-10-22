
# Optimum Price Analysis for Sellers

## Overview

Optimum Price Analysis for Sellers is a web application designed to assist regional vendors and product launchers in setting optimal prices for their products using advanced machine learning algorithms. The application analyzes reviews, ratings, and pricing to predict the best pricing strategies and provides insights into sentiment patterns. This tool offers real-time recommendations to enhance sales performance and customer satisfaction.

## Features

- **Data Input and Management**: 
  - User-friendly interface for sellers to input product details such as title, category, price, ratings, and reviews.
  - Secure storage of data using MongoDB.

- **Data Processing**: 
  - Preprocessing to handle missing values, normalize data, and extract key features.
  - Feature extraction includes quantitative (ratings, review counts) and qualitative (review text) attributes.

- **Machine Learning Models**: 
  - Ridge Regression for price prediction, providing high accuracy and reliability.
  - Natural Language Processing (NLP) for sentiment analysis of customer reviews.

- **Real-time Recommendations**: 
  - Provides dynamic, data-driven pricing recommendations.
  - Notifies users of significant changes in recommended prices.

- **User Interface**:
  - Angular-based interactive dashboard for managing products and viewing pricing recommendations.
  - Visual gallery displaying best-selling products to help sellers improve product presentation.

- **Reporting and Analytics**:
  - Tracks key performance indicators (KPIs) like sales volume, average rating, and customer sentiment.
  - Generates detailed reports on product performance and pricing trends.

- **Security and Compliance**:
  - Ensures secure storage and transmission of data.
  - Adheres to data protection and privacy regulations.

## How to Run the Application

### Backend Setup

1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/palakdesai4501/optiPrice.git
    ```

2. **Navigate to the Project Directory**:
   ```bash
   cd optiPrice
   ```

3. **Install Backend Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Backend Server**:
   ```bash
   python app.py
   ```

### Frontend (Angular) Setup

1. **Navigate to the Frontend Directory**:
    ```bash
    cd src
    ```

2. **Install Angular Dependencies**:
    ```bash
    npm install
    ```

3. **Run the Angular Development Server**:
    ```bash
    ng serve
    ```

4. **Access the Application**:
    Open your browser and go to `http://localhost:4200` to access the app.

## Technologies Used

- **Frontend**: Angular
- **Backend**: Python, Flask
- **Database**: MongoDB
- **Machine Learning**: Python (Scikit-Learn, NLP Libraries)
- **Additional Tools**: SQL for database management

## Skills Demonstrated in This Project

- **Linear Regression and Ridge Regression Models**: 
  - Developed and optimized a linear regression model using Python and SQL to analyze 2.1 million Amazon product records and predict optimal prices.

- **Real-time Data Visualization**: 
  - Connected back-end databases to a dynamic Angular front-end interface, enabling real-time data visualization similar to connecting data lakes to Tableau.

- **Data Analytics and Feature Extraction**: 
  - Applied advanced data analytics techniques to extract meaningful patterns from large datasets, allowing vendors to make data-driven decisions and optimize pricing strategies.

## Future Enhancements

- Integrate data sources like social media sentiment analysis and competitor pricing.
- Explore advanced machine learning techniques such as Random Forest and Gradient Boosting Machines.
- Implement real-time data processing for dynamic pricing strategy adjustments.
- Enhance scalability and performance optimization for larger datasets and more users.
- Incorporate user feedback mechanisms to improve the model and user experience.

![WhatsApp Image 2024-10-22 at 13 31 02_348f66fc](https://github.com/user-attachments/assets/fe3b6f97-252a-4fc7-9fdd-0380d931949c)
![WhatsApp Image 2024-10-22 at 13 32 12_8100b7e5](https://github.com/user-attachments/assets/f0bc4ce7-118d-4f6e-8591-f2e2459058a5)


