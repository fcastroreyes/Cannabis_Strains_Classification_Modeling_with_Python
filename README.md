# Cannabis_Strains_Classification_Modeling_with_Python
This notebook presents a comprehensive analysis using linear classifiers to distinguish between different cannabis strains. Through methodical data preprocessing, model application, and evaluation, it sheds light on the challenges and strategies of multi-class classification in a practical context.

# Dependencies
The analysis requires pandas, numpy, plotnine, and sklearn. Make sure these are installed in your Python environment.

# Setup Instructions
Ensure you have Python and necessary libraries installed.
Download the cannabis.csv dataset and place it in the same directory as the notebook.
Install graphviz for decision tree visualization if not already installed: pip install graphviz.

# Key Takeaways
The notebook emphasizes the nuanced decisions in employing linear classifiers for complex classification tasks, providing valuable insights into machine learning model selection and evaluation in real-world scenarios

# Notebook Overview
## Objective: To explore and implement linear classifiers for the classification of cannabis strains based on their characteristics, focusing on linear support vector machines (SVM) and logistic regression models.

# Methodology:
- Data Preparation: Involves loading the dataset (cannabis.csv), exploring its features (e.g., strain, type, rating, effects), and performing necessary data cleaning steps.
- Feature Engineering: Extracts and preprocesses features for model training, including handling categorical variables and standardizing data.
- Model Training and Tuning: Utilizes SVM and logistic regression models, employing techniques like cross-validation and GridSearchCV for hyperparameter tuning to improve model performance.

# Evaluation:
- Assesses models based on metrics such as F1 score and accuracy, and explores the challenges of classifying hybrid strains due to their shared characteristics with indica and sativa strains.

# Results:
- Discusses the complexity of multi-class classification and the performance drop when introducing more classes (indica, sativa, hybrid).
- Highlights the computational costs and decision-making involved in choosing between one-vs-one and one-vs-rest strategies for multi-class classification.
- Insights and Conclusions: Provides thoughtful analysis on the implications of model choice and strategy for multi-class classification, specifically in the context of cannabis strain classification.
