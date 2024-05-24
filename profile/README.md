# Smart Coupled Clock (WIP)

## Project Overview

Welcome to our Smart Coupled Clock! This project is a collaborative effort by a group of dedicated students aimed at developing an innovative solution utilizing Internet of Things (IoT) devices, a robust backend system deployed on the cloud, and an intuitive frontend interface. 

## Project Components

### 1. IoT Device
Our IoT device serves as the foundation of our project, enabling real-world data collection and interaction. It is designed to collect temperature and humidity readings, along with the current air quality in the room. It is also, unmistakably, a clock... doing clock things ;)
- **Custom written drivers**: LCD screen and RTC module.
- **Encryption**: AES CBC with IV.
- **Authentification**: Ability to associate a clock with a user.

### 2. Backend with Cloud
The backend system is the powerhouse of our project, responsible for processing data received from IoT devices, managing user interactions, and storing data securely on the cloud. Key features of our backend include:
- **Authentication & Authorization**: Secure user authentication and authorization mechanisms.
- **Database Management**: Storage and retrieval of data in a scalable and reliable cloud database.
- **APIs**: Well-defined APIs to facilitate communication between frontend and backend components.

### 3. Frontend
The frontend interface provides users with a seamless and intuitive way to interact with our system. It offers functionalities such as:
- **User Dashboard**: Personalized dashboards for users to view and manage their data.
- **Configuration Settings**: Customizable settings to tailor the user experience.
- **Responsive Design**: Support for various devices and screen sizes.
