# \# Email Spam Classification Using Logistic Regression

# 

# \## Overview

# This project applies logistic regression to classify emails as spam or not spam using the Spambase dataset from the UCI Machine Learning Repository. 

# It demonstrates the complete data science workflow, from data cleaning and feature engineering to model development, evaluation, and interpretation.

# 

# \## Objectives

# \- Perform exploratory data analysis (EDA) on textual frequency data.

# \- Build and evaluate logistic regression models with and without regularization.

# \- Apply principal component analysis (PCA) for dimensionality reduction and visualization.

# \- Assess model performance using accuracy, precision, recall, F1-score, and ROC-AUC metrics.

# 

# \## Methods and Tools

# \- \*\*Programming Language:\*\* Python

# \- \*\*Libraries:\*\* pandas, numpy, matplotlib, seaborn, scikit-learn

# \- \*\*Environment:\*\* Jupyter Notebook

# \- \*\*Version Control:\*\* GitHub

# 

# \## Project Structure

# ```

# spam-classification/

# │

# ├── data/

# │   └── spambase.csv

# │

# ├── notebooks/

# │   └── spam\_classification.ipynb

# │

# ├── report/

# │   └── spam\_report.pdf

# │

# ├── README.md

# └── requirements.txt

# ```

# 

# \## Results

# | Metric | Score |

# |--------|--------|

# | Accuracy | 93.5% |

# | Precision (Spam) | 92% |

# | Recall (Spam) | 91.7% |

# | ROC-AUC | 0.975 |

# 

# \*\*Key Predictors\*\*

# \- char\_freq\_!

# \- word\_freq\_your

# \- word\_freq\_free

# \- capital\_run\_length\_longest

# 

# The logistic regression model achieved strong predictive performance, confirming that well-engineered linear models can effectively classify spam emails based on textual features.

# 

# \## Future Work

# \- Incorporate additional features such as sender metadata or message context.

# \- Experiment with advanced models such as Gradient Boosted Trees or Neural Networks.

# \- Evaluate performance on contemporary datasets to assess model generalization.

# \- Develop a Streamlit-based application for real-time spam prediction.

# 

# \## Author

# Rania Hamid  

# Graduate Student, Data Analytics (UMGC)  

# LinkedIn: \[linkedin.com/in/raniahamid](https://www.linkedin.com/)  

# GitHub: \[github.com/raniahamid](https://github.com/)



