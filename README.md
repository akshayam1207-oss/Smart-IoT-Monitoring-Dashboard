# Smart IoT Monitoring Dashboard

## 📌 Project Overview

The **Smart IoT Monitoring Dashboard** is a web-based IoT project designed to monitor environmental conditions and control connected appliances through a centralized dashboard.

The project uses **Firebase Authentication, Firebase Realtime Database, and Firebase Hosting** to provide a web interface for users to log in, view sensor information, check appliance status, and control connected devices.

The dashboard provides the foundation for real-time IoT monitoring and can be extended by connecting physical sensors and an ESP32 microcontroller.

## 🎯 Objectives

- Develop a user-friendly IoT monitoring dashboard.
- Implement user authentication using Firebase Authentication.
- Store and retrieve IoT data using Firebase Realtime Database.
- Display environmental sensor readings and appliance status.
- Provide manual and automatic appliance control options.
- Deploy the web application using Firebase Hosting.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Structure of the web pages |
| CSS | Dashboard styling and layout |
| JavaScript | Dashboard functionality and Firebase integration |
| Firebase Authentication | User login and authentication |
| Firebase Realtime Database | Store and retrieve IoT data |
| Firebase Hosting | Host and deploy the web application |
| ESP32 | Microcontroller for IoT hardware integration |

## ✨ Features

### 1. User Authentication
- Provides a login interface.
- Uses Firebase Authentication to manage user sign-in.
- Restricts access to authenticated users according to the application's authentication flow.

### 2. Environmental Monitoring
The dashboard includes cards for displaying:

- 🌡️ Temperature
- 💧 Humidity
- 💡 Ambient Light
- 🔌 Bulb Status

These values are intended to be updated using data stored in Firebase Realtime Database.

### 3. Appliance Control
- Provides an interface for controlling a connected bulb.
- Supports manual control.
- Includes an automatic-control option for the IoT system.

Actual appliance control requires the appropriate hardware and backend integration.

### 4. System Status
- Displays the system's status through the dashboard.
- Provides a centralized interface for monitoring the connected IoT system.

### 5. Firebase Integration
- Uses Firebase Authentication for user access.
- Uses Firebase Realtime Database to store and retrieve application data.
- Uses Firebase Hosting to make the dashboard accessible through a web browser.

## 🏗️ System Architecture

The project follows this general architecture:

**User → Web Dashboard → Firebase Authentication / Realtime Database → IoT System**

1. The user opens the dashboard and signs in.
2. Firebase Authentication verifies the user's credentials.
3. The dashboard retrieves available data from Firebase Realtime Database.
4. The dashboard displays environmental readings and bulb status.
5. Appliance-control options allow the user to interact with the connected IoT system when the necessary hardware integration is available.

## 🔥 Firebase Configuration

The project uses the following Firebase services:

- **Firebase Authentication:** Manages user sign-in.
- **Firebase Realtime Database:** Stores and retrieves monitoring data.
- **Firebase Hosting:** Deploys the dashboard.

A Firebase configuration file connects the web application to the Firebase project.

**Security note:** Keep private credentials and sensitive configuration details out of public repositories. Configure appropriate Firebase Authentication and Realtime Database security rules before deployment.

## 🚀 Deployment

The dashboard can be deployed using Firebase Hosting.

General deployment steps:

1. Create or select a Firebase project.
2. Enable Firebase Authentication.
3. Create a Firebase Realtime Database.
4. Configure the web application's Firebase settings.
5. Prepare the dashboard files.
6. Install and configure the Firebase CLI.
7. Deploy the application using Firebase Hosting.

After successful deployment, Firebase provides a hosting URL through which the dashboard can be accessed.

## 📸 Project Screenshots

Add your actual Task 4 screenshots to the repository and display them here.

### Login Page
![Smart IoT Dashboard Login Page](assets/task4-photo9.png)

### Dashboard Interface
![Smart IoT Monitoring Dashboard](assets/task4-photo10.png)

> **Note:** Ensure that these image files exist at the specified paths in your repository. Update the paths if your screenshots are stored in a different folder.

## 🔮 Future Enhancements

- Integrate physical sensors with the ESP32.
- Display live temperature, humidity, and ambient-light readings.
- Improve automated appliance control.
- Add historical data logging and graphical analysis.
- Provide CSV export for collected sensor data.
- Improve dashboard responsiveness for mobile devices.

## 📚 Conclusion

The Smart IoT Monitoring Dashboard establishes a web-based interface for monitoring environmental conditions and controlling connected appliances. By integrating Firebase Authentication, Realtime Database, and Hosting, the project provides a foundation for an IoT monitoring system that can be extended with physical sensors, automated control, and historical data analysis.

---

**Project:** Smart IoT Monitoring Dashboard  
**Task:** 4  
**Repository:** [Smart-IoT-Monitoring-Dashboard](https://github.com/akshayam1207-oss/Smart-IoT-Monitoring-Dashboard)
