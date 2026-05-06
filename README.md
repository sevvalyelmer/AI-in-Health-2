# Group 34 - Assignment 2

**Authors:** Dora Khoshimova, Sevval Yelmer

## Overview
In this repository, the main file for the assignment is (`main.ipynb`), which preprocesses the breast cancer dataset, uses Random Forest, and XAI techniques such as SHAP, LIME and EBM.

The models were trained on a breast cancer dataset containing medical features such as `age`, `tumor-size`, `deg-malig`, `node-caps`, `inv-nodes`, `menopause`, `breast-quad`, and `irradiate`.

## File Structure
* **`main.ipynb`**: The main Jupyter Notebook containing all the code for data processing, model training, and visualizations for XAI techniques.

## Workflow
1. **Environment Setup:** Please run the first two cells to import every required library
2. **Random Forest Model:** Implementation and training of a Random Forest model with max depth of 8 and tree number of 300.
3. **Explainable AI :** Implementation of several XAI models to analyze features and importance.

## Dependencies
In the first two cells, you can automatically download every requested library

## How to Run
1. Clone or download this repository to your computer
2. Open `main.ipynb` using Jupyter Notebook.
3. Run the first cell to download dependecies
4. Run the remaining cells sequentially to train the models and generate the explainability reports.