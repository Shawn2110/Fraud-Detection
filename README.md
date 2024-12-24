# Fraud Detection Using Machine Learning

This project aims to detect fraudulent transactions using machine learning techniques, implemented in a Jupyter Notebook. The notebook demonstrates the process of data preparation, model training, and evaluation.

## Project Structure

1. **fraud.ipynb**: The main Jupyter Notebook containing the full implementation of the fraud detection model.
2. **README.md**: This documentation file providing an overview of the project.

## Requirements

The project requires the following Python libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install the required libraries using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Dataset

- Add your dataset to the project directory.
- Ensure your dataset contains the following columns:
  - `amount`: Feature column representing transaction amounts.
  - `isFraud`: Target column indicating if a transaction is fraudulent (1) or not (0).
- Update the file path in the notebook to point to your dataset.

## Notebook Details

The notebook includes the following steps:

1. **Data Loading**:
   - Load the dataset into a pandas DataFrame.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze and visualize the distribution of data using plots.

3. **Feature Selection**:
   - Use `amount` as the feature and `isFraud` as the target.

4. **Model Training**:
   - Train a machine learning model (e.g., Random Forest Classifier).

5. **Evaluation**:
   - Evaluate the model using accuracy and confusion matrix.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fraud-detection.git
   cd fraud-detection
   ```

2. Add your dataset to the project directory.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook fraud.ipynb
   ```

4. Run the cells sequentially to execute the analysis and model training.

## Outputs

- **Accuracy**: The percentage of correctly classified transactions.
- **Confusion Matrix**: Visual representation of the model's performance.

## Contributions

Contributions are welcome! Feel free to fork the repository and submit pull requests for enhancements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

