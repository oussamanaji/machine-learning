# FIFA AutoFeatureSelector Tool

This project presents an automated feature selection toolkit that intelligently identifies the most informative features in complex datasets. By integrating a diverse range of feature selection techniques, including filter methods, wrapper methods, and embedded methods, the AutoFeatureSelector streamlines the process of selecting relevant features, enhancing model performance and interpretability.

## Features
- Incorporates state-of-the-art feature selection techniques such as Pearson Correlation, Chi-Square, Recursive Feature Elimination, and Embedded Methods
- Utilizes advanced machine learning algorithms like Random Forest and LightGBM for feature importance evaluation
- Automates the feature selection process, saving time and effort in manual feature engineering
- Enhances model performance by identifying the most discriminative features and reducing dimensionality
- Provides a user-friendly interface for easy integration into machine learning pipelines

## Methodology
1. **Data Loading**: The FIFA 19 Player dataset, containing a wide range of player attributes, is loaded and preprocessed to handle missing values and encode categorical variables.
2. **Feature Selection Techniques**:
   - **Pearson Correlation**: Measures the linear relationship between each feature and the target variable.
   - **Chi-Square**: Assesses the dependence between categorical features and the target variable.
   - **Recursive Feature Elimination (RFE)**: Recursively removes the least important features based on a specified estimator.
   - **Embedded Methods**: Utilizes the feature importance scores derived from machine learning models like Random Forest and LightGBM.
3. **Automated Selection**: The AutoFeatureSelector automatically applies the specified feature selection techniques and combines their results to identify the most informative features.
4. **Model Evaluation**: The selected features are used to train machine learning models, and the model performance is evaluated using appropriate metrics to validate the effectiveness of the feature selection process.

## Results
- The AutoFeatureSelector successfully identified the top [insert number] most informative features in the FIFA 19 Player dataset.
- The selected features significantly improved the performance of machine learning models, achieving an accuracy of [insert accuracy] on the test set.
- The automated feature selection process demonstrated the ability to efficiently identify relevant features, reducing the dimensionality of the dataset and enhancing model interpretability.
- The project showcases the potential of feature selection techniques in optimizing machine learning pipelines and achieving better model performance.

## Technical Skills
- Feature Selection
- Machine Learning
- Data Preprocessing
- Model Evaluation
- Python
- Libraries: scikit-learn, pandas, numpy

## Applications
- Player Performance Analysis
- Talent Scouting and Recruitment
- Player Valuation and Transfer Market Insights
- Team Formation and Tactics Optimization

## Getting Started
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VNq41yfpuzfzJQHtdhP2Req2WkyFpyxH?usp=sharing)

1. Prepare your dataset in the appropriate format.
2. Follow the instructions in the notebook to run the AutoFeatureSelector, explore the selected features, and evaluate their impact on model performance.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. This means you are free to use, modify, and distribute the software, as long as you include the original license and copyright notice in any copies or substantial portions of the software.

## Contact
For any inquiries or collaborations, please contact:
- Mohamed Oussama NAJI
- LinkedIn: [Mohamed Oussama Naji](https://www.linkedin.com/in/oussamanaji/)
