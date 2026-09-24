# 🏠 NYC Airbnb Room Type Predictor

An end-to-end Machine Learning web application that predicts the **room type of an Airbnb listing** based on its property, location, pricing, reviews, and availability information.

The project combines a trained Machine Learning pipeline with a **FastAPI backend** and a modern web-based frontend to provide real-time predictions.

---

## 🚀 Live Project

Live Demo:https://nyc-air-bnb-2zwx.onrender.com/
---

## 📌 Project Overview

The NYC Airbnb dataset contains information about Airbnb listings such as:

- Location
- Price
- Minimum nights
- Number of reviews
- Reviews per month
- Host listing count
- Availability
- Neighbourhood
- Neighbourhood group

This project uses these features to predict the listing's **room type**, such as:

- Private room
- Entire home/apt
- Shared room

The trained ML pipeline is integrated into a FastAPI application, allowing users to enter listing information through a web interface and receive a prediction with its associated probabilities.

---

## ✨ Features

- 🏠 Predict Airbnb room type
- 📍 Location-based prediction using latitude, longitude, neighbourhood and borough
- 💰 Price-based prediction
- ⭐ Review and availability information
- 🤖 Machine Learning prediction pipeline
- 📊 Prediction probabilities
- ⚡ FastAPI REST API
- 🌐 Interactive web interface
- 🔒 Input validation using Pydantic
- 🔗 Frontend-backend integration using API requests
- 🌍 CORS-enabled API
- ☁️ Deployment-ready architecture

---

## 🧠 Machine Learning Pipeline

The application uses a pre-trained Machine Learning pipeline stored as:

```text
Model_pipeline.pkl
