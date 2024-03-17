<div align="center">
    <h1 align="center">CARA</h1>
    <h3>Multi-Lingual Conversational Assistance and Reality Augmentation (CARA) for E-Commerce with Gen-AI enhancements</h3>
</div>

## Links

[`Website link`](http://www.google.com) [`Demo video link `](http://www.google.com) [`Other links `](http://www.google.com)

- The Website Link will take the users to a fully functional deployment of our project with all the features up and running
- The Demo video has a through explantion and a complete walkthrough of our project
- The Presentation used in the video

## Team Details

`Team Number` : VH006
`Team Name` : Dawgs

| Name             | Email                      |
| ---------------- | -------------------------- |
| Mukesh Kannan    | mukeshkannan311@gmail.com  |
| Pranav Sathya    | pranavsathyaar@gmail.com   |
| Bharath Sanjeevi | bhrathsanjeevi.t@gmail.com |
| Srivatsav Auswin | auswinsrivatsav@gmail.com  |

## Screen-Shots and Demo-Video

## Problem statement

> Multi-Lingual Conversational Assistance and Reality Augmentation (CARA) for E-Commerce with Gen-AI enhancements

To overcome the Complexities of E-Commerce with a Simple and Easy to use E-Commerce application by using Multi-Lingual Conversational Assistance and Reality Augmentation (CARA) to provide a unique and relaxed expirence which is further improved with Gen-AI.

## About the project

### Our Mission:

We're on a mission to simplify online shopping by leveraging intuitive technology that speaks your language, understands your preferences, and enhances your shopping environment.

### Key Features:

- **Multi-lingual conversational assistance**: Our platform breaks language barriers by providing natural language understanding and generation capabilities in multiple languages. Whether you're browsing from Tokyo or Toronto, our AI-powered assistants ensure clear communication and personalized support.

- **Reality Augmentation for E-Commerce**: Immerse yourself in a virtual shopping environment with our reality augmentation features. Visualize products in your surroundings through augmented reality, enabling you to assess their fit, style, and compatibility with your space before making a purchase.

- **Gen-AI Enhancements**: Experience personalized shopping like never before. Our AI-driven platform learns from your interactions to provide tailored recommendations and assistance, ensuring every step of your shopping journey is effortless and enjoyable.

- **Retailer Access**: Retailers have a special route that let's them update or manage their produxts more easily.

### Benefits:

- **Simplicity**: Our user-friendly interface ensures a seamless shopping experience, making it easy for you to browse, discover, and purchase products hassle-free.
- **Accessibility**: Break through language barriers effortlessly, as our platform caters to a global audience with multi-lingual support and intuitive design.
- **Personalization**: Enjoy a personalized shopping experience tailored to your preferences, with AI enhancements that anticipate your needs and provide relevant recommendations.

## Technical implemntaion

- The main focus while implemnting our project was to deliver a simple and Easy to use application
- We have built an uniquely tailored Web Application that houses a Multi-Lingual Conversational Assistant and Reality Augmentation (CARA) features
- We have used Whisper by Open AI with some modifications along with a seamless integration of GPT 3.5 by Turbo to support and enable our Multi-Lingual Conversational Assistance.
- For a unique and better user experience we have added AR features to visualize the products to get a better "perspective" of things.
- Our Multi-Lingual Conversational Assistant takes in audio input and fetches data accordingly
- This Multi-Lingual Conversational Assistant fully supports foriegn various languages (Chinese,French,German,etc...)
- This also supports **Traditional Native language** (Tamil,Hindi,Malayalam,Bengali,etc...) upto a limited level
- A backend server is built and integrated with Flask
- The frontend communiates with Whisper with the help of a Next Serer that converts Base64 audio to Mp3 audio
- Once the user validates the request the Flask Server handles this request and fetches the required data from the DB
- Here's a flowchart of the workflow of our application
- ![alt text](https://github.com/Sak1012/vashiht-24/tree/CocaCola/assets/image.jpg?raw=true)

## Techstacks used

### FRONTEND

- NextJS -> framework
- ZUSTAND -> global state management
- ZOD -> validations
- FRAMER MOTION and LOTTIE -> animations
- TAILWINDCSS -> design
- PLAYCANVAS -> AR Try On feature

### BACKEND

- FLASK (Server)
- OPEN-AI
  - GPT-3.5-turbo (Querying prompt by user)
  - WHISPHER-1.0 (Multilingual Audio to Text Transcription)
  - LLAMA INDEX (Vectorizing the DataFrame)
- PANDAS (Creating Dataframe)
- SQLALCHEMY (SQL Connectivity)
- POSTGRES (Database)

## How to run locally

To run this locally follow these steps:

- Step 1 : clone the frontend repo and backend repo seperately

```bash

git clone https://github.com/MKMukeshkannan/vashisht-frontend.git
git clone https://github.com/BharathSanjeeviT/vashisht-backend.git

```

### Frontend

Run these following commands in the terminal to start the local server

```bash
yarn
yarn dev
```

### Backend

Run these following commands in the terminal to start the local server

```bash
npm install
npm start
```

# What's next ?

We further Aim to develop this project with an improved native language support and an improved inventory management system for retailers.

## Declaration

We confirm that the project showcased here was either developed entirely during the hackathon or underwent significant updates within the hackathon timeframe. We understand that if any plagiarism from online sources is detected, our project will be disqualified, and our participation in the hackathon will be revoked.
