
# Digit Recognizer with PCA

This project aims to recognize hand-written digits using the MNIST dataset and Principal Component Analysis (PCA) for dimensionality reduction.

## Project Overview

The project is structured as follows:

1. **Data Loading**: The MNIST dataset, which contains 28x28 pixel images of hand-written digits, is loaded into the notebook for analysis and model building.

2. **Data Preprocessing**: The images are flattened into 1D arrays and normalized to have values between 0 and 1. Additionally, PCA is applied to reduce the dimensionality of the data while preserving most of its variance.

3. **Model Building**: Several machine learning models, such as logistic regression, support vector machine (SVM), and random forest, are trained on the preprocessed data to recognize the hand-written digits.

4. **Model Evaluation**: The trained models are evaluated using metrics such as accuracy and confusion matrix to assess their performance in recognizing the digits.

5. **Conclusion**: The project concludes with a summary of the findings, including the best-performing model, key insights from the data analysis, and any recommendations for further improvement.

## Getting Started

To run the project, follow these steps:

1. Clone this repository:
   ```
   git clone https://github.com/shubh123a3/Machine_learning_project.git
   ```

2. Navigate to the project directory:
   ```
   cd Machine_learning_project/MINIST_PCA/
   ```

3. Install the required libraries:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. Open the Jupyter Notebook `digit_recoginizer.ipynb` to view the project code and analysis.

## Libraries Used

- pandas: Data manipulation and analysis
- numpy: Mathematical functions
- matplotlib: Data visualization
- seaborn: Data visualization
- scikit-learn: Machine learning models and tools

## Results

The project results in a machine learning model that can recognize hand-written digits with high accuracy using PCA for dimensionality reduction. The performance of the model is evaluated using various metrics to ensure its accuracy and reliability.

## Future Improvements

- Experiment with different numbers of principal components in PCA to find the optimal number for the best performance.
- Explore other dimensionality reduction techniques to compare their performance with PCA.
- Fine-tune the hyperparameters of the machine learning models for improved accuracy.

## Contributors

- Shubh Shrishrimal

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

