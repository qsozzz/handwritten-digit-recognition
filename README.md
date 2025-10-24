# Handwritten Digit Recognition

## Overview

The "Handwritten Digit Recognition" is a simple yet powerful web application that identifies handwritten digits (0–9) in real time. The core model was originally trained using PyTorch, and its outputs were later converted to a JavaScript-friendly format so it can run directly in your browser. The app uses arrays and matrices to represent the model’s weights and biases, enabling fast and accurate predictions.

## How It Works

At the heart of the project lies a neural network — a machine learning model inspired by how the human brain processes information. This network is made up of layers of interconnected “neurons” that learn from data and make predictions. In our case, it’s trained to recognize handwritten digits by analyzing patterns in pixel data and using the learned weights and biases from the training phase.

## Live Demo
[Try the application online](https://hoffhannisyan.github.io/handwritten-digit-recognition/): Draw any digit (0-9) on the canvas and see the neural network predict it in real-time!

## Running the Project

To use the "Handwritten Digit Recognition":

1. Clone the project from the GitHub repository.
2. Ensure you have Node.js installed on your local machine.
3. Navigate to the project directory in your terminal.
4. Run the project using the command `npm run start` or `node app.js`.
5. Open your web browser and go to `localhost:8080`.

