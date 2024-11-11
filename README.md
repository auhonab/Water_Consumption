# EcoPredict

or 

# Village Resource Insight

A deep learning-powered project for predicting and monitoring water consumption and solar energy production in a village, combining LSTM models and a user-friendly interface.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Overview

**Village Resource Insight** is a predictive analytics tool designed to monitor and forecast water consumption and solar energy production in rural areas. By utilizing deep learning models for both domains, the project enables better resource management and sustainability practices.

## Features
- **Water Consumption Model**: Uses LSTM with TensorFlow to predict water consumption patterns.
- **Solar Energy Production Model**: Implements LSTM with PyTorch to forecast solar energy output.
- **Integrated Frontend**: User-friendly interface developed for easy data visualization and interaction.

## Project Structure
```plaintext
Village-Resource-Insight/
├── models/
│   ├── solar_production/       # Solar production model (PyTorch, LSTM)
│   ├── water_consumption/      # Water consumption model (TensorFlow, LSTM)
│
├── frontend/
│   ├── public/                 # Public files for frontend
│   ├── src/                    # Frontend source code and components
│
├── backend/
│   ├── app.py                  # Backend connection logic
│   ├── api/                    # API for connecting models and frontend
│
└── README.md
```

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Village-Resource-Insight.git
   cd Village-Resource-Insight
   ```

2. Install dependencies:
   - For the water consumption model (TensorFlow):
     ```bash
     pip install tensorflow
     ```
   - For the solar production model (PyTorch):
     ```bash
     pip install torch
     ```
   - For other project dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. Run the backend server:
   ```bash
   python backend/app.py
   ```

4. Launch the frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```

## Usage

1. Access the web application in your browser at `http://localhost:3000`.
2. Use the dashboard to view real-time data and predictions for both water consumption and solar production.

## Contributors

- **Divij** - Developed the solar production model (LSTM with PyTorch)
- **Auhona** - Developed the water consumption model (LSTM with TensorFlow)
- **Aryan** - Frontend development and integration
- **Anthony** - Frontend and backend connection

## License

This project is licensed under the MIT License.

