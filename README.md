Smart Wearable Activity and Health Monitoring

Team members: Rajkumar T , Priyadharshini B

IoT Dataset and System Design Proposal

Dataset Source
The dataset selected for this project is the PAMAP2 Physical Activity Monitoring
Dataset, available from the UC Irvine Machine Learning Repository.
Source Link:
https://archive.ics.uci.edu/ml/datasets/PAMAP2+Physical+Activity+Monitoring

How the Data Was Collected
The dataset was collected using real wearable IoT devices worn by nine participants
performing daily life activities such as walking, running, sitting, cycling, and household
tasks. Each participant wore three wireless inertial measurement units (IMUs) placed
on the wrist, chest, and ankle. These sensors recorded tri-axial acceleration, gyroscope,
magnetometer, and heart rate data in real time. The data was logged at a sampling rate
of 100 Hz, making it a true time-series IoT dataset collected from physical devices in
real environments.

Number of Observations

The dataset contains approximately 3.8 million individual sensor readings across all
participants and activities, making it large enough for deep learning and time-series
prediction tasks.
Variables in the Dataset
Key variables included in the dataset are:
• Timestamp (time series index)
• Accelerometer readings (x, y, z axes)
• Gyroscope readings (x, y, z axes)
• Magnetometer readings (x, y, z axes)
• Heart rate measurements
• Activity label (e.g., walking, sitting, running, etc.)
• Subject ID
These variables provide both physiological and motion-based information, allowing
multiple machine learning and analytics use cases.

Proposed IoT Application/System

The proposed IoT system is a Smart Wearable Activity and Health Monitoring
Platform. The system is designed to continuously monitor user movements and vital
signs using wearable IoT sensors. It will:
• Identify and classify user activities in real time (e.g., sitting, walking, exercising)
• Predict future heart rate trends based on past sensor data
• Detect abnormal patterns such as unusual inactivity or elevated heart rate
• Provide personalized health and fitness insights through a dashboard

Who Will Use It?
The primary users of this system would be:
• Individual consumers tracking their fitness and daily activities
• Healthcare professionals remotely monitoring patients
• Fitness trainers analyzing client performance
• Corporate wellness programs

Industry Fit
This IoT application fits primarily within the Healthcare and Personal Devices
(Wearables) Industry, with additional relevance to the fitness and wellness domain.
Planned System Overview
The theoretical IoT system will consist of:
• Wearable sensors (accelerometer, gyroscope, heart rate monitor)
• Edge processing on a smartphone or microcontroller
• Data transmission via Bluetooth/Wi-Fi using MQTT protocol
• Cloud storage for time-series data
• Machine learning models for activity classification (deep learning)
• Time-series prediction of heart rate trends
• A Tableau-based dashboard for visualization and insights

This dataset and application allow implementation of both required tasks: a deep
learning model for activity classification and a time-series prediction model for
forecasting physiological metrics.
