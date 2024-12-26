# Predicting Airbnb Availability

This program is designed to predict whether an Airbnb listing is available using machine learning techniques. The project leverages feature engineering, data preprocessing, and supervised learning models to achieve accurate predictions.

## Features

- **Data Preprocessing:** Handles missing data, encodes categorical variables, and scales numerical features for optimal model performance.
- **Feature Engineering:** Extracts relevant features to improve prediction accuracy.
- **Modeling:** Trains and evaluates supervised learning models to predict Airbnb availability.
- **Visualization:** Includes plots to analyze data trends and model performance.

## Requirements

To run the notebook, you need the following dependencies:

- Python 3.7+
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/airbnb-availability-predictor.git
   ```

2. Navigate to the project directory:

   ```bash
   cd airbnb-availability-predictor
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook Listings_Availability.ipynb
   ```

4. Run the cells in the notebook sequentially to:

   - Load and preprocess the data
   - Perform exploratory data analysis (EDA)
   - Train and evaluate machine learning models

## Dataset

The dataset includes Airbnb listings with various features such as location, price, and previous booking history. These attributes are used to predict the availability status of a listing.

> **Note:** Ensure you have the required dataset in the specified location before running the notebook. Replace the placeholder path in the notebook with your actual dataset path.

## Results

The notebook provides:

- A detailed analysis of features impacting availability.
- Performance metrics (e.g., accuracy, precision, recall) of the trained models.
- Visualizations to understand data distribution and model predictions.

## Contributing

Contributions are welcome! If you have ideas for improving the project or adding new features, feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Inspiration from Airbnb's open data initiative.
- Tools and libraries used in this project, such as scikit-learn and pandas.
