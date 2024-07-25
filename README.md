# Credit Card Fraud Detection

## Project Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. Using a dataset of credit card transactions, we perform exploratory data analysis and build classification models to accurately identify fraudulent activities.

## Dataset
The dataset used in this project is `creditcard.csv`, which contains the following columns:
- **Time**: Time elapsed since the first transaction in the dataset (in seconds)
- **V1, V2, ..., V28**: Principal components obtained using PCA (to protect confidentiality)
- **Amount**: Transaction amount
- **Class**: Target variable (0 for non-fraudulent, 1 for fraudulent)

## Project Structure
The project is structured as follows:
- `data/`: Contains the dataset file (`creditcard.csv`).
- `notebooks/`: Contains Jupyter notebooks for data analysis and model building.
- `scripts/`: Contains Python scripts for data preprocessing and model training.
- `README.md`: Project overview and documentation.

## Libraries and Tools
The following libraries and tools are used in this project:
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Exploratory Data Analysis
We perform exploratory data analysis (EDA) to understand the distribution of the data and the relationship between features and the target variable. Key insights include:
- Distribution of transaction amounts.
- Correlation between features.
- Imbalance between fraudulent and non-fraudulent transactions.

## Data Visualization
Various plots are used to visualize the data:
- Histograms to visualize the distribution of transaction amounts.
- Heatmaps to visualize the correlation between features.
- Bar plots to show the imbalance in the class distribution.

## Data Preprocessing
The data is preprocessed to handle missing values, scale features, and split the data into training and testing sets:
- Handling missing values (if any).
- Scaling features using standard scaling techniques.
- Splitting the data into training and testing sets.

## Model Building
We build and evaluate multiple classification models to detect fraudulent transactions:
1. **Logistic Regression**:
   - **Accuracy**: Measure of correct predictions.
   - **Precision**: Proportion of true positive predictions.
   - **Recall**: Proportion of actual positives correctly identified.
   - **F1 Score**: Harmonic mean of precision and recall.
   - **Confusion Matrix**: Matrix to visualize true/false positives and negatives.
2. **Decision Tree Classifier**:
   - Similar evaluation metrics as Logistic Regression.

## Results
The models are evaluated based on their performance metrics, with a focus on accurately detecting fraudulent transactions:
- **Logistic Regression**: Provides a baseline model with reasonable accuracy and recall.
- **Decision Tree Classifier**: Achieves higher accuracy and recall, making it a more effective model for fraud detection.

## Conclusion
The project demonstrates how machine learning models can effectively detect fraudulent credit card transactions. The Decision Tree Classifier, in particular, shows high accuracy and recall, making it a valuable tool for fraud detection.

## Usage
To run the project, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook or Python script for data analysis and model training.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
This project is part of the CodSoft Data Science Internship. Special thanks to the CodSoft team for their support and guidance.
