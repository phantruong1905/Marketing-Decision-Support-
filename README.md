# Marketing-Decision-Support

### Project Overview
This project aims to optimize marketing expenditures across different advertising channels (Television, Social Media, and Newspaper) by building a predictive model that forecasts revenue based on marketing investments. The model leverages machine learning techniques, with a focus on Lasso regularization, to provide actionable insights for marketing budget allocation.

### Key Features
- **Predictive Model**: Built using machine learning techniques to estimate the impact of advertising spend on revenue.
- **Lasso Regularization**: Employed to enhance the model’s performance and reduce overfitting by selecting the most relevant features.
- **Channels Analyzed**: Television, Social Media, Newspaper.

### Technology Stack
- **Language**: R
- **Machine Learning Algorithms**: Lasso Regression, Linear Regression
- **Libraries Used**: 
  - `glmnet` for Lasso Regression
  - `ggplot2` for data visualization
  - `caret` for model training and evaluation

### Getting Started

#### Prerequisites
To run this project, you need to have R and the following libraries installed:
```r
install.packages(c("glmnet", "ggplot2", "caret"))
