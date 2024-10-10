# Google Play Store Apps EDA

This project contains an Exploratory Data Analysis (EDA) of the Google Play Store app dataset. Using Python libraries such as **numpy**, **pandas**, **matplotlib**, and **sklearn**, I cleaned the data and performed both univariate and bivariate analyses to uncover insights into app trends, ratings, installs, and other factors.

## Dataset
The dataset used in this analysis is publicly available and can be found [here](https://raw.githubusercontent.com/krishnaik06/playstore-Dataset/main/googleplaystore.csv). It includes details about various apps on the Google Play Store, such as app name, category, rating, size, number of installs, and more.

## Libraries Used
The following Python libraries were utilized in the project:
- **pandas**: For data manipulation and cleaning
- **numpy**: For numerical computations
- **matplotlib**: For data visualization
- **sklearn**: For preprocessing and statistical modeling

## Project Workflow
### 1. Data Cleaning
- Handled missing values and removed inconsistencies.
- Converted columns to appropriate data types.
- Cleaned entries related to app ratings, installs, and other features.

### 2. Univariate Analysis
- Explored individual variables such as app ratings, number of installs, and app sizes.
- Used visualizations such as histograms and box plots to understand the distribution of these variables.

### 3. Bivariate Analysis
- Analyzed relationships between two variables, like the correlation between app installs and ratings, or how paid apps perform in comparison to free apps.
- Visualized the relationships using scatter plots and correlation matrices.

## Visualizations
- **Histograms**: To display the distribution of numerical features.
- **Box Plots**: To understand the spread and outliers in variables such as ratings.
- **Scatter Plots**: To visualize relationships between different features such as installs and ratings.

## How to Run the Code
1. Clone this repository:
   ```bash
   git clone <repository_url>
