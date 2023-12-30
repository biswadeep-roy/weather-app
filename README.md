# Weather App


## Description

This is a mobile weather application built with React Native that provides users with real-time weather information based on their current location. The app displays the current temperature, weather condition, and a 3-day forecast.

## Features

- Real-time weather updates
- Location-based weather information
- 3-day forecast display




## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Node.js and npm installed
- Expo CLI installed (`npm install -g expo-cli`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/biswadeep-roy/weather-app.git
   ```
2. Change into the project directory:

  ```bash

  cd weather-app
  ```
3. Install dependencies:

  ```bash
  npm install
  ```
4. Start the development server:


  ```bash
  expo start
  ```
5. Follow the Expo CLI instructions to run the app on an emulator or a physical device.

6.Building APK:

Users can also build the APK on their own using the Expo EAS (Expo Application Services) CLI. Follow these steps:

Install the EAS CLI globally:
``` bash
npm install -g eas-cli
```

Log in to Expo EAS:
``` bash
eas login
```

Configure the build settings:
``` bash
eas build:configure
```

Build the APK (Android):
``` bash
eas build --platform android
```

Users can customize the build process further using the eas.json file generated during the configuration step.
### Contact Developer
To contact the developer or provide feedback, use the "Contact Me" feature within the app. Fill in your name, email, and message, and the developer will receive your email.

### Technologies Used
### Technologies Used

- **React Native:** A JavaScript framework for building mobile applications using React.
- **Expo:** A framework and platform for universal React applications, simplifying development and deployment.
- **Expo CLI:** Command-line tools for working with Expo projects.
- **React Navigation:** A library for routing and navigation in React Native applications.
- **Expo Vector Icons:** A set of customizable icons for React Native with support for Expo.
- **Expo Font:** A module for loading and using custom fonts in Expo projects.
- **Expo Location:** A module providing access to the device's location information.
- **Expo EAS (Expo Application Services) CLI:** Command-line tools for building and configuring Expo projects.
- **WeatherAPI:** An external API used to fetch real-time weather information.
- **Node.js and npm:** The JavaScript runtime and package manager used for server-side and development dependencies.



### API Used
WeatherAPI

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.


