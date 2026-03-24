# Fitness-Tracker-Desktop-App
A complete Fitness Tracker Desktop Application developed using Python, PyQt5, SQLite, and Matplotlib. This app enables users to log daily workouts, store and manage fitness data locally, and analyze performance using graphical visualizations (Distance vs Calories).

# 🏃‍♂️ Fitness Tracker Desktop App

## 📖 Overview

The Fitness Tracker Desktop App is a user-friendly GUI-based application
developed using Python and PyQt5. It helps users record, manage, and
visualize their daily fitness activities such as calories burned and
distance covered.

The application stores data locally using SQLite and provides a
graphical representation of fitness progress using Matplotlib.

## 🎯 Objective

The main goal of this project is to: - Practice GUI development using
PyQt5\
- Understand database integration using SQLite\
- Visualize data using charts\
- Build a real-world desktop application

## ✨ Features

### 📝 Workout Management

-   Add new workout records
-   Store:
    -   Date
    -   Calories burned
    -   Distance covered
    -   Description
-   Delete selected workout entries

### 📊 Data Visualization

-   Scatter plot: Distance vs Calories
-   Color gradient based on normalized calorie values

### 🌙 UI Features

-   Light Mode (default)
-   Dark Mode toggle
-   Clean and responsive layout

### 🧹 Utility Functions

-   Clear/reset input fields
-   Auto-refresh table after operations

## 🛠️ Technologies Used

-   Python
-   PyQt5
-   SQLite
-   Matplotlib
-   NumPy

## 📂 Project Structure

FITTRACK/ │ ├── main.py ├── fitness.db └── README.md

### Install Dependencies

pip install PyQt5 matplotlib numpy

### Run Application

python main.py

## 📊 Graph Explanation

-   X-axis → Distance (KM)
-   Y-axis → Calories Burned
-   Color → Normalized calorie values


