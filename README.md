# DATA-PIPELINE-DEVELOPMENT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: JAYESH MODHVADIYA

*INTERN ID*: CT4MDA791

*DOMAIN*: DATA SCIENCE

*DURATION*: 4 MONTHS

*MENTOR*: NEELA SANTOSH

## 1. Data Preprocessing ETL Pipeline

This repository contains a Python-based **ETL (Extract, Transform, Load)** pipeline for data preprocessing, transformation, and loading using **Pandas** and **Scikit-Learn**. The pipeline is designed to process CSV files and perform data cleaning, transformation, encoding, and scaling operations automatically.

---

## Project Overview

The project aims to automate the ETL process for structured datasets. It handles common preprocessing tasks like:

- Loading CSV files  
- Handling missing data  
- Encoding categorical features  
- Scaling numeric features  
- Saving the transformed data to a new CSV file

### 🔑 Key Features

- **Missing Data Handling**: Fills missing numeric values with the mean and categorical values with the mode.  
- **Categorical Encoding**: Converts categorical columns into numbers using **LabelEncoder**.  
- **Data Scaling**: Applies **StandardScaler** to normalize numeric columns.  
- **Custom Columns**: You can define which columns to include in preprocessing.

---

## 💻 How to Use

### 1. Clone the repository:

bash
git clone https://github.com/jayesh2039/ScikitLearn-ETL-Pipeline
cd ScikitLearn-ETL-Pipeline

# 2. Install the required dependencies:

Make sure you have Python 3.x installed and then install the necessary libraries:

bash
Copy
Edit
pip install -r requirements.txt

# 3. Prepare your CSV file:

Place the CSV file you want to process in the same directory as the script.

Ensure the CSV file contains at least the following columns: Name, Sex, Age, Fare, and Embarked.

# 4. Run the pipeline:

Run the etl_pipeline.py script with your CSV file:

bash
Copy
Edit
python etl_pipeline.py <input_file.csv>
Replace <input_file.csv> with the path to your CSV file. The script will process the file and save the transformed data as processed_output.csv.

📥 Example Input
| Name    | Sex    | Age | Fare  | Embarked |
| ------- | ------ | --- | ----- | -------- |
| John    | male   | 22  | 7.25  | S        |
| Sarah   | female | 28  | 71.28 | C        |
| Michael | male   | NaN | 8.05  | Q        |


📥 Example Output
| Name   | Sex | Age   | Fare  | Embarked |
| ------ | --- | ----- | ----- | -------- |
| 0.447  | 1   | -1.60 | -0.83 | 0.577    |
| -0.447 | -1  | 1.05  | 1.63  | -1.732   |
| 1.342  | 1   | 0.00  | -0.80 | 0.577    |

🤝 Contributing
Feel free to fork the repository, make improvements, and submit pull requests.

🧰 Requirements
- Python 3.x
- Pandas
- Scikit-learn

You can install all required dependencies using:
bash
Copy
Edit
pip install -r requirements.txt

# Output:

![Image](https://github.com/user-attachments/assets/09bb2678-6f36-4d53-9c24-bb04d2af665f)

