
# Medical Data Visualizer

## Introduction

This repository contains a Python script that performs data visualization and analysis on medical examination data using the Pandas, Seaborn, and Matplotlib libraries. The script draws a categorical plot and a heatmap to visualize various aspects of the dataset.

## Table of Contents

- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Code Description](#code-description)
- [Key Points / Learning](#key-points--learning)
- [Applicability](#applicability)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [Initial Contributor](#initial-contributor)

## Code Description

The Python script performs the following tasks:

1. Imports necessary libraries: `pandas`, `seaborn`, `matplotlib`, and `numpy`.

2. Reads medical examination data from a CSV file using Pandas.

3. Adds an 'overweight' column to the DataFrame based on weight and height.

4. Normalizes data for 'cholesterol' and 'gluc' columns.

5. Defines a function `draw_cat_plot` to draw a categorical plot using Seaborn.

6. Creates a DataFrame for the categorical plot using `pd.melt`, groups and reformats the data, and draws the plot using `sns.catplot`.

7. Defines a function `draw_heat_map` to draw a heatmap using Seaborn.

8. Cleans the data for the heatmap, calculates the correlation matrix, generates a mask for the upper triangle, and draws the heatmap using `sns.heatmap`.

9. Calls the `draw_cat_plot` and `draw_heat_map` functions to generate and save plots.

10. Displays the plots.

## Key Points / Learning

- **Pandas Usage:** The script showcases the use of Pandas library for data manipulation and analysis.

- **Data Visualization:** The script demonstrates how to create informative visualizations using Seaborn and Matplotlib libraries.

- **Categorical Plotting:** The script utilizes Seaborn's `sns.catplot` function to create categorical plots.

- **Heatmap Creation:** The script illustrates the creation of a heatmap using Seaborn's `sns.heatmap`.

## Applicability

This code is applicable in scenarios where you need to visualize and analyze medical examination data for various aspects. Potential areas of application include:

- **Healthcare Research:** Analyzing medical examination data to extract insights and correlations.

- **Medical Reports:** Generating visualizations for medical reports and presentations.

- **Health Monitoring Applications:** Incorporating data visualization for health monitoring applications.

## How to Use

To visualize and analyze medical examination data using this script, follow these steps:

1. Clone the repository to your local machine using `git clone https://github.com/Mabdullahatif/Medical_Data_Visualizer.git`.

2. Download the dataset file `medical_examination.csv` and place it in the repository directory.

3. Open the Jupyter Notebook or Google Colab environment.

4. Navigate to the repository directory.

5. Open the `main.py` file.

6. Run the code cells to perform data visualization and analysis and view the generated plots.

## Contributing

Contributions are welcome! To contribute to the Medical Data Visualizer, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and commit them with descriptive commit messages.

4. Push your changes to your forked repository.

5. Create a pull request detailing your changes and explaining their purpose.

Please make sure to follow the repository's code of conduct and guidelines.

## Initial Contributor

So far, all the work in this repository is purely done by me.

## LinkedIn &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Facebook &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Instagram &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Twitter
<a href="https://www.linkedin.com/in/muhammad-abdullah-atif/">
    <img height="50" src="https://cdn2.iconfinder.com/data/icons/social-icon-3/512/social_style_3_in-306.png"/>
</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;

<a href="https://www.facebook.com/abdullahatif362/">
    <img height="50" src="https://cdn0.iconfinder.com/data/icons/social-flat-rounded-rects/512/facebook-64.png"/>
</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

<a href="https://www.instagram.com/abdullah._.atif/">
    <img height="50" src="https://cdn2.iconfinder.com/data/icons/social-media-applications/64/social_media_applications_3-instagram-64.png"/>
</a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;

<a href="https://www.twitter.com/abd_allah_atif/">
    <img height="50" src="https://cdn3.iconfinder.com/data/icons/2018-social-media-logotypes/1000/2018_social_media_popular_app_logo_twitter-64.png"/>
</a>

