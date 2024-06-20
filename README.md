# ML-Fundamental-Linear-Regression-Model
## Salary Prediction with Linear Regression

### DOCUMENTATION 

### Salary Prediction with Linear Regression

**Overview**
This project aims to predict salaries based on years of experience using a linear regression model. The dataset used for training and evaluation is sourced from the YBIFoundation Dataset repository.

The project includes:
- **Data preprocessing**
- **Model training and evaluation**
- **Results visualization**

**Installation**
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

**Dataset**
The dataset used (`Salary Data.csv`) is available from the YBIFoundation Dataset repository. It contains the following columns:

- **Experience Years**: Number of years of experience
- **Salary**: Corresponding salary in USD

**Usage**
#### Running the Jupyter Notebook
1. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

2. **Open and run `notebooks/analysis.ipynb`** for a detailed step-by-step analysis.

#### Running the Python Script
- Execute `src/main.py` to train the model and visualize the results directly from the command line:
  ```bash
  python src/main.py
  ```

**Project Structure**
- **`notebooks/analysis.ipynb`**: Jupyter Notebook with detailed analysis steps.
- **`src/main.py`**: Python script version of the notebook's code for direct execution.
- **`requirements.txt`**: List of dependencies required to run the project.
- **`LICENSE`**: MIT License file governing the usage of the project.

**Results**
The trained linear regression model achieved a Mean Absolute Percentage Error (MAPE) of approximately X% on the test dataset. Below is a visualization of the regression line fitted to the data points:

![Regression Plot](results.png)

**Next Steps**
Feel free to explore and modify the code to further improve the model's performance or experiment with different algorithms.
