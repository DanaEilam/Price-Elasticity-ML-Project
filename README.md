# Introduction
<b>This project was assigned as the seminar as part of my B.Sc. in the field of computer science at Tel Aviv University, and was done in a team.
The project was implemented using Google Colab platform, using Python, machine learning and libraries such as Pandas, NumPy, Scikit-learn etc.</b>

<ins>Since we signed a non-disclosure agreement with the company which the project is intended for, 
I cannot share code and specific details from the project</ins>, but I can briefly explain what was done and share the project poster that was presented at Tel Aviv University.

### The Company the project was designated for:
This project was for Ogentech company. A little about the company: "Ogentech is an independent software company specializing in the creation, management and optimization of business forecasting and inventory solutions."
<br> The company provides solutions for product demand forecasting, inventory planning, and order planning for many leading companies.
<br>The company collects various sales data from its customers and uses it, along with additional data, to derive different business insights.
<br>More information is availble on their website: https://www.ogentech.com/

The main goal was to examine the possibility of using machine learning tools in the company's work. 
<ins>In the project terms, the goal is to examine the effectiveness of machine learning tools by constructing a price elasticity table and curve for different products.</ins>

# Project steps

### Data investigation:
We received a large dataset from the company that contains sales data from several branches of one of the company's clients over the course of a year.
The dataset contained approximately 2 million records and over 17,000 different products.

We researched products with a high likelihood of price sensitivity at the company's recommendation and examined each variable separately while making the necessary adjustments for further processing.

### Data processing:
Examples of the transformation actions we performed: Removing outlier observations, changing variable names, converting variable values, creating new variables, and more.

### Building machine learning models and evaluation:
We chose well-known models such as neural networks and random forest, and we trained each machine learning model to predict the demand for a specific product.
The evaluation of the models is done using the R^2 parameter.

### Production of the final outputs for the project:
Based on the demand forecast results of the best model, we were able to calculate approximately the product elasticity and create a curve and a table, and later the production possibility curve.
Our final outcomes were as follows:
1. A demand forecasting machine learning model - for estimating price elasticity
2. Elasticity curve and table for different products.
3. Production possibility curve
4. Pipeline - for data processing, model training, and generating graphs for a specific product

# Summary and Conclusions
Machine learning tools can be indeed suitable for addressing such business issues, like demand forecasting from tabular data.
In our results, we can see interesting discount ranges - a range that greatly affects the demand for the selected products and a range where the discount does not lead to a change in sales.
These points can support the assumption that there is a range of discounts within which a change in the product's price affects its demand.

The project was challenging but rewarding; we learned and grew a lot together. The work and communication with Ron Levkovitz, the CTO of Ogentech company, were easy-going, interesting, and educational. 

Overall, we faced a big project, with many difficulties and many questions. But our investment, self-learning, teamwork, and cooperation made the project very successful and enjoyable.
