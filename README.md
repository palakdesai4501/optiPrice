# Optimum Price Analysis for Sellers

## Overview

Optimum Price Analysis for Sellers is a web application designed to assist regional vendors and product launchers in setting optimal prices for their products using advanced machine learning algorithms. The application analyzes the number of reviews, ratings, and pricing to predict the best pricing strategies and provides insights into sentiment patterns. This tool offers real-time recommendations to enhance sales performance and customer satisfaction.

## Features

- **Data Input and Management**: 
  - User-friendly interface for sellers to input product details such as title, category, price, ratings, and reviews.
  - Secure storage of data using MongoDB.

- **Data Processing**: 
  - Data preprocessing to handle missing values, normalize data, and extract features.
  - Feature extraction includes both quantitative (ratings, review counts) and qualitative (review text) attributes.

- **Machine Learning Models**: 
  - Uses Ridge Regression for price prediction, which provides better accuracy and reliability than linear regression.
  - Implements Natural Language Processing (NLP) techniques for sentiment analysis of customer reviews.

- **Real-time Recommendations**: 
  - Provides dynamic, data-driven pricing recommendations.
  - Notifies users of significant changes in recommended prices.

- **User Interface**:
  - Interactive dashboard built with Angular for managing products and viewing recommendations.
  - Visual gallery displaying best-selling products to help sellers improve product presentation and positioning.

- **Reporting and Analytics**:
  - Tracks key performance indicators (KPIs) such as sales volume, average rating, and customer sentiment.
  - Generates detailed reports on product performance and pricing trends.

- **Security and Compliance**:
  - Ensures secure storage and transmission of data.
  - Adheres to data protection and privacy regulations.

## How to Run the Application

### Backend Setup

1. **Clone the Repository**: 
    ```bash
    git clone

2. **Navigate to the Project Directory**:
   ```bash
   cd optiPrice

3. **Install Backend Dependencies**:
  - Ensure you have Python and pip installed, then run:
    ```bash
    pip install -r requirements.txt
    
4. **Run the Backend Server**:
   ```bash
   python app.py

### Frontend (Angular) Setup

1. **Navigate to the Frontend Directory**:
- After cloning the repository, navigate to the Angular project directory:
  ```bash
  cd src

2. **Install Angular Dependencies**:
- Ensure you have Node.js and npm installed, then run:
  ```bash
  npm install

3. **Run the Angular Development Server**:
    ```bash
    ng serve

4. **Access the Application**:
Open your web browser and go to `http://localhost:4200` to use the application.

## Technologies Used

- **Frontend**: Angular
- **Backend**: Python, Flask
- **Database**: MongoDB
- **Machine Learning**: Python (Scikit-Learn, NLP Libraries)

## Future Enhancements

- Incorporate additional data sources such as social media sentiment analysis and competitor pricing.
- Explore advanced machine learning techniques such as Random Forest and Gradient Boosting Machines.
- Implement real-time data processing to allow vendors to adjust pricing strategies dynamically.
- Enhance scalability and performance optimization for handling larger datasets and more users.
- Integrate user feedback mechanisms to refine the model and improve user experience.




