---

# Smart Agriculture Advisor

**Repository**: [Wise-Ai-thon](https://github.com/Git-me-Harish/Wise-Ai-thon)

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training and AI Techniques](#model-training-and-ai-techniques)
- [Frontend](#frontend)
- [Backend](#backend)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)
- [License](#license)

---

## Project Overview

The **Smart Agriculture Advisor** is an AI-driven application aimed at providing personalized farming recommendations based on a variety of data inputs including soil characteristics, weather conditions, crop types, and historical yield data. It incorporates advanced machine learning algorithms and deep learning models to offer precise farming advice and crop yield predictions.

The system is designed with a user-friendly frontend where farmers can input data and receive custom recommendations. Additionally, the platform offers an AI-based chatbot for query resolution using Retrieval-Augmented Generation (RAG).

---

## Features

- **Soil Analysis**: Leverages soil data (e.g., pH, moisture content) to provide crop recommendations.
- **Weather-Based Suggestions**: Integrates real-time weather data to optimize planting, irrigation, and harvesting schedules.
- **Personalized Recommendations**: Provides personalized advice based on the farmer's input using machine learning models.
- **AI Chat Assistance**: An AI-powered chatbot using RAG (Retrieval-Augmented Generation) to answer queries and provide advice.
- **Crop Yield Prediction**: Predicts future crop yields using historical and real-time data.
- **Recommendation System**: Offers crop and fertilizer suggestions tailored to local conditions.

---

## Architecture

The **Smart Agriculture Advisor** architecture includes the following components:

1. **Frontend**: Built using **React.js** to provide an intuitive and responsive user interface for farmers to input data and receive recommendations.
   
2. **Backend**: Powered by **Node.js** and **Express**, the backend handles the application logic, API communication, and machine learning model interactions.

3. **Database**: The system uses **MongoDB** to store user inputs, historical crop data, and recommendations.

4. **AI and ML Models**:
   - **Deep Learning** frameworks for complex pattern recognition.
   - **Machine Learning** algorithms for recommendation systems and predictive analytics.
   - **RAG (Retrieval-Augmented Generation)** for AI-based chat assistance.

---

## Technologies Used

### Frontend:
- **React.js**: For building a dynamic, responsive user interface.
  
### Backend:
- **Node.js**: Backend runtime environment.
- **Express.js**: Web framework for building RESTful APIs.

### Database:
- **MongoDB**: NoSQL database for storing farmer data, soil properties, weather inputs, and recommendations.

### Machine Learning & AI:
- **TensorFlow/PyTorch**: For building and deploying deep learning models for yield predictions and crop recommendations.
- **Scikit-learn**: For ML algorithms like regression, decision trees, and random forest.
- **RAG (Retrieval-Augmented Generation)**: Used for implementing the AI-based chatbot.

---

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/Git-me-Harish/Wise-Ai-thon.git
cd Wise-Ai-thon
```

### 2. Install dependencies for the backend and frontend:
Navigate to the backend folder and install dependencies:
```bash
cd backend
npm install
```
Navigate to the frontend folder and install dependencies:
```bash
cd ../frontend
npm install
```

### 3. Set up environment variables:
Create a `.env` file in the root directory with necessary credentials:
- MongoDB connection string.
- Weather API key.
- Other necessary environment variables for RAG and model access.

### 4. Run the application:

To start the backend:
```bash
cd backend
npm start
```

To start the frontend:
```bash
cd ../frontend
npm start
```

The app should now be running locally. Access it via `http://localhost:3000`.

---

## Usage

1. **Access the Frontend**:
   - Visit `http://localhost:3000` to open the input form for farmers.
   
2. **Input Data**:
   - Farmers can input soil details (e.g., pH level, moisture), crop type, and relevant weather data.
   
3. **Get Recommendations**:
   - The backend processes the input data and returns personalized farming advice and crop yield predictions.
   
4. **AI Chat Assistance**:
   - Farmers can interact with the built-in chatbot, powered by RAG, for additional queries and advice.

---

## Dataset

The system uses data from multiple sources to provide accurate recommendations:
- **Soil Data**: pH, nitrogen content, moisture, etc.
- **Weather Data**: Real-time and historical data obtained through an external API.
- **Crop Yield Data**: Historical crop performance data used for training machine learning models.

---

## Model Training and AI Techniques

### 1. **Machine Learning Models**:
   - **Regression Models**: Used for yield prediction.
   - **Classification Models**: For crop recommendation based on soil and weather conditions.
   - **Recommendation Systems**: Personalized suggestions based on past data and user input.

### 2. **Deep Learning**:
   - **Neural Networks**: Used for analyzing complex relationships between soil and environmental data.
   - **Convolutional Neural Networks (CNN)**: For any image-based analysis (e.g., detecting plant diseases).

### 3. **Retrieval-Augmented Generation (RAG)**:
   - AI-based chatbot using RAG for interacting with farmers and answering queries.
   
All models are trained on historical datasets and fine-tuned with recent data to ensure accuracy.

---

## Frontend

The frontend is built using **React.js** for a responsive and intuitive user interface. It allows farmers to:
- Input soil, weather, and crop data.
- Get personalized farming advice and crop yield predictions.
- Access an AI chatbot for further assistance.

---

## Backend

The backend is built using **Node.js** and **Express.js**. Key functionalities include:
- API endpoints for receiving and processing data from the frontend.
- Interfacing with MongoDB to store and retrieve data.
- Handling the execution of machine learning models and generating predictions.
- Providing real-time advice using the AI chatbot based on RAG.

---

## Future Improvements

- **Mobile App**: Develop a mobile application for better accessibility.
- **IoT Integration**: Include support for IoT sensors to gather real-time soil and weather data.
- **Multilingual Support**: Extend support to regional languages for a broader farmer base.
- **Satellite Data Integration**: Use satellite imagery to provide even more accurate predictions.

---

## Contributors

- **Sri Harish** - [GitHub](https://github.com/Git-me-Harish)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

