# Ensemble Learning Techniques for Binary Classification
This project explores Ensemble Learning techniques in machine learning. Using a binary-class classification dataset with 30,000 samples and 2 features, multiple ensemble methods are implemented and compared. The main goal is to train and evaluate models like Bagging, Random Forest, AdaBoost, and a custom Stacked Ensemble, focusing on improving accuracy and generalization.

The project includes manual implementations and uses scikit-learn models for benchmarking. Key evaluation metrics such as accuracy, precision, recall, and F1-score are calculated throughout all phases for both training and test datasets.

## Key Achievements
- **Manually implemented Bagging algorithm**: using decision trees and visualized the output of individual classifiers.
- **Built and analyzed Random Forest**: ensembles with both custom and sklearn-based implementations.
- **Applied AdaBoost**: to study the sequential improvement of weak learners and their cumulative impact.
- **Developed a Stacked Ensemble**: combining at least 4 diverse base classifiers, including custom and sklearn learners.
- **Performed hyperparameter tuning**: across all models to optimize performance.
- **Evaluated models using comprehensive metrics**: (accuracy, precision, recall, F1-score) on both training and test sets.
- **Visualized the progression of ensemble stages**: (especially in AdaBoost) to analyze classifier contributions.
- **Prevented overfitting in stacking**: by avoiding reusing previously trained classifiers and employing new models for meta-learning.
- **Plotted performance vs. number of estimators**: for all ensemble methods.
