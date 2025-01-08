# House Price Prediction

This repository contains a machine learning project aimed at predicting house prices based on features such as the number of rooms and the area of the house. The project is implemented in Python using Jupyter Notebook.

## Project Overview

The goal of this project is to develop a regression model that can accurately predict house prices. The dataset used for this project contains information on house features and their corresponding prices.

### Key Steps
1. **Data Loading**: Load the dataset (`House_Price_Project_data.csv`) and perform an initial preview.
2. **Feature Selection**: Use features like `Rooms` and `Area` to predict the target variable, `Price`.
3. **Data Splitting**: Split the dataset into training and testing sets using an 80-20 ratio.
4. **Model Training**: Train a linear regression model on the training data.
5. **Evaluation**: Evaluate the model's performance using metrics like Mean Squared Error (MSE) and R-squared.
6. **Visualization**: Plot results for better understanding and insights.

## Files in the Repository

- `House_Price_Prediction_Model.ipynb`: The main notebook containing the project code and explanations.
- `House_Price_Project_data.csv`: The dataset used for training and testing the model.

## Dependencies

To run this project, you need the following Python libraries:

- pandas
- scikit-learn
- matplotlib

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
   ```bash
   git clone <[repository_url](https://github.com/AbhiAnand-1011/House-Price-Prediction)>
   ```

2. Ensure the dataset (`House_Price_Project_data.csv`) is in the repository directory.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook House_Price_Prediction_Model.ipynb
   ```

4. Follow the steps in the notebook to run the model and visualize results.

## Results

The trained model achieves the following metrics on the test data:
- **Mean Squared Error (MSE)**: [Add value here after running]
- **R-squared**: [Add value here after running]

## Future Improvements

- Include additional features for better prediction.
- Experiment with other regression models.
- Implement hyperparameter tuning for optimization.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

## Acknowledgments

- The dataset is assumed to be fictional and created for educational purposes.
- Inspiration and guidance from the open-source machine learning community.

---
Feel free to reach out if you have any questions or suggestions!

