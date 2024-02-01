# House Price Predictor

## Overview
This project uses Elixir, Livebook, Explorer, Nx, VegaLite, and Scholar to build a machine-learning model that predicts house prices in King County, Washington. It focuses on essential steps like data cleaning, feature engineering, and model evaluation to ensure accurate price predictions.

## Features
- **Data Visualization**: Uses `VegaLite` to create insightful visualizations.
- **Data Preprocessing**: Includes comprehensive data cleaning and preprocessing.
- **Predictive Modeling**: Built with Elixir libraries (`Nx`, `Explorer`, `Scholar`) for prediction.
- **Model Evaluation**: Features model evaluation through cross-validation.
- **Interactive Predictions**: Provides an interactive interface for making predictions.

## Dependencies
- **Elixir & Livebook**: For running code and visualizing data.
- **Nx**: Handles numerical computations and machine learning.
- **Explorer**: Used for data analysis and manipulation.
- **VegaLite**: For generating interactive visualizations.
- **Scholar**: Elixir library for machine learning.

## Getting Started
To run this project, ensure Elixir and Livebook are installed on your system.

1. **Access the Project**:
   - Import the project notebook into Livebook using the following link: 
   - https://github.com/Hooahclitus/House-Price-Predictor/blob/main/House-Price-Predictor.livemd.

2. **Start Livebook**:
   - Open Livebook and import the notebook from the URL provided. 

3. **Run the Entire Notebook**: 
    - After importing the notebook, run all cells from start to finish. This action loads all modules and data and executes the analysis steps automatically.

## How to Use
Once you have the notebook open in Livebook:

1. **Explore the Notebook**: It's divided into sections for easy navigation. Each section builds upon the previous one, from data collection and cleaning to modeling and predictions.
2. **Run Code Cells**: Execute the code cells in each section by clicking the play button. Make sure to run them in order, as later sections depend on the setup and results from earlier ones.
3. **Data Visualization**: Check the EDA section's visualizations to understand the data better.
4. **Model Prediction**: When you reach the model application section, you'll find an interactive form. Here, you can input features like the number of bedrooms, bathrooms, and square footage.
5. **Get Predictions**: After filling in the form with your desired inputs, submit it to get a prediction on the house price. The model uses the input features and median values from the dataset for other necessary features to estimate the price.
6. **Experiment**: Feel free to go back and change your inputs to see how different features affect the predicted price.

## Contributing
Contributions are welcome. If you have improvements or bug fixes, please fork the repository and submit a pull request.

## Acknowledgments
- Kaggle for providing the King County House Sales dataset.
- The Elixir community for the helpful libraries and tools.

Questions or suggestions? Please feel free to open an issue in the GitHub repository.
