# Cancer Prediction with Machine Learning

This project aims to predict the likelihood of cancer using machine learning techniques. It utilizes a dataset containing various features related to patients' health and medical history to build a predictive model.

## Requirements

- Python 3.x
- Libraries:
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/mehrdadOrouei/predict-cancer-with-Ml.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have a dataset containing relevant features such as age, gender, family history, etc., along with the target variable indicating cancer status.

2. Run the main script:
   ```
   python main.py
   ```

3. Follow the prompts to input patient data and obtain cancer prediction results.

## Dataset

The project utilizes a dataset containing anonymized patient information, including demographic data, medical history, and cancer diagnosis.

## Approach

1. **Data Preprocessing**: Clean and preprocess the dataset, handle missing values, encode categorical variables, and normalize numerical features.

2. **Feature Selection**: Select relevant features that contribute the most to predicting cancer status.

3. **Model Training**: Train various machine learning models such as logistic regression, decision trees, random forests, etc., on the preprocessed dataset.

4. **Model Evaluation**: Evaluate the trained models using appropriate metrics such as accuracy, precision, recall, and F1-score.

5. **Hyperparameter Tuning**: Fine-tune the parameters of selected models to improve predictive performance.

6. **Prediction**: Utilize the trained model to predict cancer likelihood for new patient data.

## Contributors

- mehrdad.orouei@yahoo.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
