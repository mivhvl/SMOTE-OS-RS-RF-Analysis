# README.md

## Project Overview
This project explores techniques for handling imbalanced datasets in machine learning. Solutions like Random Forest with class weights, Random Oversampling, Random Undersampling, SMOTE, and its variants were analyzed and compared.

## Methodology
- **Data Preparation:** Synthetic data generated with `make_classification`.
- **Resampling Techniques:** Random Oversampling, Random Undersampling, and SMOTE.
- **Model Training:** Random Forest Classifier with and without class weights.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score.

## Results
- Resampling methods enhance classifiers' performance, especially for the minority class.
- SMOTE and Hybrids improve recall but may reduce precision.
- Random Undersampling balances class distribution but lowers precision due to majority class reduction.
- Random Oversampling boosts precision but may lead to suboptimal results due to duplicates.
- SMOTE-based techniques are ideal for recall-focused tasks.
- Random Oversampling or Borderline-SMOTE balances precision and minority class performance.
- Preprocessing techniques should be tested with the chosen classifier to determine the best approach.

## Environment
This project was developed in a Python 3.8+ environment. Below are the dependencies required to replicate the environment:

### Dependencies
- **pandas**
- **scikit-learn**
- **matplotlib**
- **seaborn**
- **imbalanced-learn**
- **smote-variants**

## Usage
1. Clone the repository:
   ```bash
   git clone <https://github.com/mivhvl/SMOTE-OS-RS-RF-Analysis.git>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   jupyter notebook
   ```

## Structure
- `notebook.ipynb`: Analysis notebooks
- `RAPORT.pdf`: Analysis raport and conclusions

## License
This project is licensed under the MIT License.

