# House Price Prediction

This project aims to predict house prices using two different machine learning algorithms: Linear Regression and Gradient Boosting Regressor. The dataset used contains various features related to houses, such as the number of bedrooms, bathrooms, square footage, etc., and the corresponding sale prices.

## Dataset

The dataset used for this project contains the following columns:
- **Bedrooms**: Number of bedrooms in the house.
- **Bathrooms**: Number of bathrooms in the house.
- **Square footage**: Total square footage of the house.
- **Garage spaces**: Number of garage spaces.
- **Year built**: Year the house was built.
- **Sale price**: The price at which the house was sold.

## Dependencies

To run the code, the following Python libraries are required:
- NumPy
- pandas
- scikit-learn

## Usage

1. **Clone the repository to your local machine:**
    ```bash
    git clone https://github.com/your_username/house-price-prediction.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd house-price-prediction
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook or Python script to train and evaluate the models:**
    ```bash
    jupyter notebook House_Price_Prediction.ipynb
    ```
    or
    ```bash
    python house_price_prediction.py
    ```

## Project Structure

```
house-price-prediction/
│
├── data/
│   └── house_prices.csv       # Dataset file
│
├── notebooks/
│   └── House_Price_Prediction.ipynb  # Jupyter Notebook for model training and evaluation
│
├── scripts/
│   └── house_price_prediction.py  # Python script for model training and evaluation
│
├── requirements.txt  # List of dependencies
│
├── LICENSE  # License file
│
└── README.md  # Project readme file
```

## Results

The project compares the performance of Linear Regression and Gradient Boosting Regressor in predicting house prices. Evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared are used to assess the performance of the models.

## Conclusion

Based on the evaluation metrics, we conclude which model performs better in predicting house prices. Additionally, insights into the importance of different features in predicting house prices are provided.

## Future Work

Future work may involve:
- Exploring other machine learning algorithms
- Fine-tuning hyperparameters
- Incorporating additional features to improve the accuracy of the predictions

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by forking the repository and submitting pull requests. For major changes, please open an issue first to discuss what you would like to change. 

If you find this project helpful, please give it a star!

