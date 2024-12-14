
# Skills: Programming - Introduction Level

## Description
This project is a comprehensive analytics platform designed to process and visualize football league data. It integrates a Jupyter Notebook for interactive analysis and a Python script for deploying an interactive web application.

### Key Features
- **Interactive Visualizations**: Provides rich visualizations for trends and performance.
- **Model**: Various models were utilized, ranging from Linear Regression to Random Forest, to analyze and predict football match results and league data.
- **Web Application**: A Streamlit-based web app for interactive user experiences.

## Files
- **Model Folder**: This folder includes the exploratory analysis and the scripts used to train the model based on the data.
- **Website Folder**: This folder holds the code for the final website, which integrates the model with user inputs to predict stadium attendance. It serves as the final interface and the culmination of our work. The Python script in this folder powers an interactive web application, accessible at: https://skillsprogramming-cvt8mis9yw6qbnresnkxqx.streamlit.app

## Dependencies
The following libraries are required for this project:
- base64
- datetime
- io
- matplotlib
- numpy
- pandas
- pickle
- requests
- streamlit

Install these dependencies using:
```bash
pip install -r requirements.txt
```

## Usage

### Running the Web Application
1. Ensure all dependencies are installed.
2. Run the script using Streamlit:
   ```bash
   streamlit run app_v4_final.py
   ```
3. Or just open https://skillsprogramming-cvt8mis9yw6qbnresnkxqx.streamlit.app

### Using the Jupyter Notebook
1. Open the notebook file "model.ipynb" in Jupyter Notebook or JupyterLab.
2. Execute cells interactively to explore data.

## Dataset Details
The project uses football match results and league data, which are processed and analyzed within the notebook and the web app.

### CSV Files
- `football_results.csv`: Contains historical match results.
- `league_table_combined.csv`: Includes additional league data displayed interactively on the website. Contains example data just to demonstrate the layout and the functionality of the website.

Note: The data "football_results.csv" was originally sourced from Kaggle. However, the specific dataset is no longer available on Kaggle. It was downloaded while it was still accessible.

### IPYNB Files
- `model.ipynb`: Explores the data and trains models as the main part of the project.

### PY Files
- `app_v4_final.py`: Implements the final version of the website application.
