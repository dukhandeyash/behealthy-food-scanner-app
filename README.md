# behealthy-food-scanner-app

## Overview

This mobile application is designed for health-conscious users who want quick and easy access to nutritional information of food products. The app allows users to scan barcodes on food items and retrieve detailed product information, including sugar content, allergens, and other nutrients. It also provides personalized warnings based on users' medical conditions, helping them make healthier choices. 

## Key Features

- **User Authentication**: Secure login and registration using Firebase Authentication.
- **Real-Time Barcode Scanning**: Scan food product barcodes in real-time using ML Kit to retrieve nutritional information.
- **Nutritional Information Display**: Displays detailed nutritional content sourced from OpenFoodFacts, including sugar content and other key nutrients.
- **Personalized Warnings**: Alerts for users with medical conditions (e.g., diabetes) when scanned products exceed safe nutritional limits.
- **Medical Condition Integration**: Allows users to select a medical condition (e.g., diabetes) and receive tailored warnings when a product is unsuitable.
- **Product History**: Users can view their previously scanned items on the Home screen for easy reference.
- **Data-Driven Insights**: Provides additional information on allergens and other dietary data to help users make informed decisions.

## Technologies Used

- **Firebase Authentication**: Secure user authentication and data storage.
- **ML Kit**: For real-time barcode scanning and image analysis.
- **OpenFoodFacts API**: To retrieve nutritional data and product information.
- **Firebase Firestore**: For securely storing user data and scanned product details.
- **JSON Parsing**: For handling API responses and displaying nutritional information.

## How It Works

1. **User Authentication**: Users can register and log in to the app using Firebase Authentication.
2. **Barcode Scanning**: The app uses ML Kit to scan barcodes and retrieve product information from OpenFoodFacts.
3. **Display Nutritional Information**: After scanning, the app displays the product's nutritional data, including sugar content, allergens, and other nutrients.
4. **Personalized Warnings**: Users with medical conditions (e.g., diabetes) will receive warnings if a scanned product exceeds safe nutritional limits.
5. **Data Storage and Retrieval**: Scanned product data is securely stored in Firebase Firestore and associated with the user's account. The app also retrieves previous scans and medical condition information during login.
