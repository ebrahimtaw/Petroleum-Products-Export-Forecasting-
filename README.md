# Petroleum-Products-Export-Forecasting 🚀

The project focuses on building a neural network to predict the future export volumes of petroleum products in Bahrain. By leveraging historical data and various petroleum products as input features, the model forecasts future exports with a high degree of accuracy. This forecasting tool can be integrated into business workflows to aid in planning and decision-making.

> **Dataset**: The data used in this project was sourced from Bahrain's Open Data Portal.

## Features / Variables 📊
- **Year**: The year of the export.
- **Petroleum Products Exported**: Type of petroleum product (e.g., Naphtha, Diesel, Fuel Oil, etc.).
- **Export Volume in (,000) U.S. Barrels**: The target variable representing the volume of exports.

## Technical Overview ⚙️
- **Input Data**: Year, one-hot encoded petroleum products.
- **Model**: A neural network with ReLU activation functions trained using the Adam optimizer.
- **Loss Function**: Mean Squared Error (MSE).
- **Performance Metrics**: 
  - Test RMSE: ~1045 barrels
  - R² Score: 0.986

## Highlights ✨
- **One-Hot Encoding** used for categorical features (petroleum products).
- **Residual analysis** to detect underfitting/overfitting patterns.
- Model achieved a high **R² score**, indicating accurate forecasting for unseen data.

## Key Steps 📋
1. Data preprocessing and one-hot encoding of categorical features.
2. Splitting data into training, validation, and test sets (60% training, 20% validation, 20% test).
3. Model training with TensorFlow, fine-tuned for optimal performance.
4. Performance evaluation using MSE, RMSE, and residual plots.

Explore the code to learn how deep learning can forecast future trends in the oil and gas sector! 🚀

