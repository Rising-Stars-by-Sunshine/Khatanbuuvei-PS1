# Khatanbuuvei-PS1
# Netflix vs Disney Data Analysis

This repository contains the data analysis for the research project comparing Netflix and Disney's content strategies, pricing models, and subscriber trends using open-source datasets.

## System Configuration Instructions

### 1. Setting Up Locally

#### **Prerequisites**
Ensure you have the following installed:
- **Python (>=3.8)**: [Download here](https://www.python.org/downloads/)
- **R (>=4.0)**: [Download here](https://cran.r-project.org/)
- **Git**: [Download here](https://git-scm.com/)
- **Jupyter Notebook** (for Python analysis):
  ```sh
  pip install jupyterlab
  ```
- **R Packages**:
  ```r
  install.packages(c("tidyverse", "ggplot2", "fixest", "lmtest", "sandwich"))
  ```
- **Python Packages**:
  ```sh
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

#### **Running the Analysis Locally**
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd <repository_name>
   ```
2. Open Jupyter Notebook for Python analysis:
   ```sh
   jupyter lab
   ```
3. Open RStudio or run R scripts in the terminal:
   ```r
   source("analysis_script.R")
   ```

### 2. Setting Up in the Cloud

#### **Google Colab (Python)**
1. Upload the dataset to Google Drive.
2. Open Google Colab and mount the drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Install dependencies (if needed):
   ```sh
   !pip install pandas numpy matplotlib seaborn scikit-learn
   ```
4. Load the dataset and run the analysis.

#### **RStudio Cloud**
1. Create a new RStudio Cloud project.
2. Install required R packages:
   ```r
   install.packages(c("tidyverse", "ggplot2", "fixest", "lmtest", "sandwich"))
   ```
3. Upload the dataset and run the analysis script.

### 3. Notes
- Ensure you have the correct dataset path when running scripts.
- If using a cloud environment, adjust file paths accordingly.
- For troubleshooting, refer to the documentation of installed packages.

---

For questions or contributions, feel free to open an issue or submit a pull request!
