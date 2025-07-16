# Used Car Price Analysis
Will we provide meaningful insights into drivers of used car prices?

## Overview

This project analyzes a subset of 426,000 used car listings to identify key factors influencing price. You'll run the solution.ipynb notebook in Google Colab, mount your Drive, and reproduce data cleaning, preparation, modeling, and evaluation steps.

## Prerequisites

This project is designed to run in a Codio cloud workspace with full Jupyter Notebook and Python support. No local setup is required.

* Google account with Drive access
* Internet connection

## Project Structure

```
M11_PA2/
├── data/              # raw CSV file
├── images/            # figures and visualizations
├── solution.ipynb     # Jupyter notebook with code and results
└── README.md          # project instructions
```

## Usage

Open the Notebook

1. Click on the solution.ipynb file in the repository: solution.ipynb
2. Open in Google Colab: At the top of the solution.ipynb file, click the Open in Colab badge or button.
3. Mount Google Drive: In the notebook, execute the first code cell. This will prompt you to authorize and mount your Google Drive.
4. Create Project Folder: After mounting, create a new folder M11_PA2 in your Drive (/content/drive/MyDrive/) to hold the assignment files.
5. Upload Data and Images in /content/drive/MyDrive/M11_PA2/ (Note: You can use the Colab file browser (left sidebar) or the upload button to drag and drop files).
6. Once the files are in place, click on `Run all` to execute the entire notebook.
## Analysis Steps

1. **Data Inspection**: Load CSV, check data types and missing values.
2. **Preprocessing**: Handle nulls, convert categories, engineer features (e.g., vehicle age).
3. **Modeling**: Fit baseline and advanced regressors (e.g., Random Forest, XGBoost).
4. **Evaluation**: Compare RMSE, R² on validation set.
5. **Interpretation**: Identify top predictors influencing price.

## Key Findings

* **Top Drivers**: Age of vehicle, odometer reading, manufacturer/model, condition.
* **Price Trends**: Newer cars and low-mileage vehicles command higher prices.
* **Model Performance**: Random Forest achieved

## Author

Yashaswi Raval

---

*For questions or contributions, please open an issue or submit a pull request.*
