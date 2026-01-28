# Customer Purchase Predictor

This project is a simple Java application that demonstrates how to build and use a **basic regression prediction model**. It predicts a customer's purchase amount based on their income using **linear regression**.

The project uses:

- **Apache Commons Math** – for building the regression model (`SimpleRegression`)
- **OpenCSV** – for reading customer data from a CSV file
- **Maven** – for dependency management and build
- A main class: `CustomerPurchasePredictor`

---

## Project Overview

This application:

1. Loads customer purchase data from a CSV file.
2. Trains a **simple linear regression model** where:
   - **X (independent variable)** = customer income  
   - **Y (dependent variable)** = customer purchase amount
3. Uses the trained model to predict purchase amounts for new income values.
4. Prints the predictions to the console.

This is an introductory lab for understanding how to integrate a machine learning–style regression model into a Java/Maven project.

