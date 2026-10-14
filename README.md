# AI-Powered Sales Prediction System Using Random Forest Regression

A machine learning web application that predicts total sales using key business inputs such as advertising spend, store size, and discount percentage. The project combines a Random Forest Regression model with a FastAPI backend and an interactive frontend dashboard built using HTML, CSS, JavaScript, and Chart.js.

## Overview

This project helps businesses estimate future sales based on historical data and marketing factors. By analyzing patterns in ad spend, store size, and discounts, the system provides quick and intuitive sales forecasts for decision-making.

The application includes:
- a trained machine learning model
- a FastAPI backend for serving predictions
- an interactive dashboard for user input and visualization
- real-time chart-based output for sales analysis

## Features

- Sales prediction using Random Forest Regression
- Input fields for:
  - Advertising budget
  - Store size
  - Discount percentage
- Real-time prediction output
- Interactive charts for data visualization
- FastAPI-based backend
- Responsive HTML/CSS/JavaScript dashboard
- Easy-to-extend architecture

## Tech Stack

- Python
- FastAPI
- Scikit-learn
- Pandas
- NumPy
- Random Forest Regressor
- HTML
- CSS
- JavaScript
- Chart.js

## Project Structure

```text
AI-Powered-Sales-Prediction-System-Using-Random-Forest-Regression/
├── app/
│   ├── main.py
│   ├── model.py
│   ├── train.py
│   ├── schema.py
│   └── utils.py
├── data/
│   └── sales_data.csv
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
├── requirements.txt
├── README.md
└── .gitignore
