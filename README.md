# Smart Vehicle Accident Alert System
![Screenshot (361)](https://github.com/01harsh/Smart_Accident_Alert_system/assets/60311625/c6ad4f22-3c87-44c7-b717-bb41511a3e81)

## Overview

Welcome to the Smart Vehicle Accident Alert System! This system is designed to enhance road safety by detecting accidents using IoT sensors, notifying relevant parties through a call rendering system powered by Twilio, accessing live location through a Geolocation API, storing user and vehicle data in real-time using PostgreSQL, and predicting accident severity using a Support Vector Machine (SVM) algorithm.
![Screenshot (364)](https://github.com/01harsh/Smart_Accident_Alert_system/assets/60311625/aba7f6b4-5953-4ac6-8c49-f042778ac8a6)
![Screenshot (363)](https://github.com/01harsh/Smart_Accident_Alert_system/assets/60311625/530ab531-c833-426e-84ea-ae7bea0b3dbf)

## Features

### 1. Accident Detection via IoT Sensors

The system is equipped with IoT sensors that can detect accidents in real-time. These sensors are strategically placed in vehicles to monitor various parameters such as sudden acceleration or deceleration, airbag deployment, and collision forces. When an accident is detected, the system initiates a series of actions to ensure prompt response.

### 2. Call Rendering System with Twilio Integration

We have integrated Twilio, a powerful calling API, to facilitate immediate communication in case of accidents. The system can make phone calls to emergency services or designated contacts to report the accident. This ensures that help arrives as quickly as possible.

### 3. Live Location Access with Geolocation API

To provide precise information about the accident location, the system leverages a Geolocation API. It can access the live location of the vehicle involved in the accident, making it easier for emergency services to locate the scene and respond effectively.

### 4. Real-time Data Storage with PostgreSQL

The system utilizes PostgreSQL, a robust relational database management system, to store user and vehicle data in real-time. This includes user profiles, vehicle information, and historical accident data. This data is crucial for reporting, analysis, and ensuring seamless communication between system components.

### 5. Accident Severity Prediction with SVM Algorithm

To assist emergency responders in understanding the potential severity of an accident, the system employs a Support Vector Machine (SVM) algorithm. This machine learning model analyzes sensor data from the accident scene and predicts the accident's severity. This prediction is invaluable for dispatching the appropriate resources and medical personnel to the accident site.

![Screenshot (362)](https://github.com/01harsh/Smart_Accident_Alert_system/assets/60311625/5dc1b4d2-50cd-4ad4-a051-eedc839fef38)
