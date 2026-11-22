Smart City App

A mobile application developed with React Native and Expo that enables citizens to report urban issues and monitor reported problems within their communities.

Features

Issue Reporting: Submit reports describing local infrastructure and public service problems.

Issue Categories: Road damage, street lighting, waste management, water supply and green spaces.

GPS Location: Automatically capture geographical coordinates when submitting reports.

Photo Capture: Attach photographs to reports using the device camera.

Live Reports: Retrieve and display submitted reports using Firebase Firestore.

Interactive Map: Visualise reported issues through geographical markers, with different colours indicating their status.

Technologies

Technology

Purpose

React Native

Mobile application development

Expo

Development environment

TypeScript

Application logic

Firebase Firestore

Cloud database

React Native Maps

Map integration

Expo Location

GPS services

Expo Image Picker

Camera functionality

Expo Router

Navigation

Installation

Clone the repository.

Install dependencies:

npm install

Configure your Firebase project in firebaseConfig.ts.

Start the development server:

npx expo start

Run the application using Expo Go or an Android/iOS emulator.

Project Structure

SmartCityApp/
├── app/
│   ├── (tabs)/
│   │   ├── index.tsx
│   │   ├── map.tsx
│   │   ├── report.tsx
│   │   ├── reports.tsx
│   │   └── firebaseConfig.ts
│   └── _layout.tsx
├── assets/
├── components/
├── hooks/
├── constants/
├── package.json
└── app.json

Purpose

The project explores how mobile technology and real-time data can improve communication between citizens and local authorities, making urban issue reporting more accessible and efficient.
