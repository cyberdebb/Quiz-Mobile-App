# Quiz Mobile App

Quiz Mobile App is a mobile application that delivers a fun and interactive quiz experience using real-time trivia questions. Built with **React Native**, the app provides smooth performance across **iOS and Android** devices and fetches questions dynamically from the **Open Trivia Database (OpenTDB) API**.

---

## Features

- Multiple-choice quiz questions  
- Real-time data fetched from OpenTDB API  
- Session-based trivia using API tokens  
- Clean and intuitive mobile interface  
- Cross-platform support (iOS and Android)  

---

## Getting Started

These instructions will help you set up the project locally for development and testing purposes.

---

## Prerequisites

Before running the app, make sure you have the following installed:

- Node.js  
- npm or Yarn  
- React Native CLI  
- Expo CLI  

---

## Installation

### 1. Install Required Dependencies

Make sure the following tools are installed globally:

```bash
npm install -g expo-cli@6.3.10 react-native-cli@2.0.1
```

Project dependencies include:

```bash
@babel/core@7.24.4
@eslint/js@9.0.0
@expo/webpack-config@19.0.1
@react-native-community/eslint-config@3.2.0
@react-navigation/bottom-tabs@6.5.20
@react-navigation/native@6.1.17
eslint-plugin-react@7.34.1
eslint@8.57.0
expo@49.0.23
expo-status-bar@1.6.0
globals@15.0.0
moment@2.30.1
prettier@3.2.5
punycode@2.3.1
react@18.2.0
react-dom@18.2.0
react-native@0.72.10
react-native-dotenv@3.4.11
react-native-safe-area-context@4.6.3
react-native-screens@3.22.1
react-native-web@0.19.10
```

2. Clone the Repository

```bash
git clone https://github.com/cyberdebb/Quiz-Mobile-App.git
```

3. Navigate to the Project Directory and Install Dependencies
```bash
cd Quiz-Mobile-App
npm install
```

4. Start the Application

```bash
npm start
```

or

```bash
npx react-native start
```

---

## API Used
Open Trivia Database (OpenTDB)

Endpoint: https://opentdb.com/api.php
Parameters:
- amount=5
- type=multiple
