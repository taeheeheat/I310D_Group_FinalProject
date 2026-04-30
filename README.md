# I310D_Group_FinalProject
## Data-Driven Animal Welfare: Predicting Adoption Outcomes
**Course:** I310D Introduction to Human-Centered Data Science  
**Group Members:** Seah Im, Hailey Kim, Uiin John Kim  

## Data Setup
Our code uses the Austin Animal Center dataset. Because we used Google Colab, the code tries to load the data from Google Drive.

1. Download the dataset file: `AustinAnimalCenter_27Mar5pm.csv`
2. Go to your Google Drive and create a folder named `I310D_project`.
3. Upload the `.csv` file into that folder. 
*(If you want to use a different folder or run it locally, please change the `file_path` variable in Step 1 of the code).*

## How to Run the Code
Please follow these simple steps to reproduce our analysis:

1. Open Google Colab (https://colab.research.google.com/).
2. Upload our Jupyter Notebook file (`.ipynb') to Colab.
3. Run **Step 1** block. It will ask for permission to connect to your Google Drive. Please click "Allow".
4. Run the rest of the code blocks in order (Step 2 to Step 5).
5. You will see the data cleaning results, EDA graphs, model accuracy, and the fairness confusion matrix at the end.

## 📁 Code Structure
* **Step 1: Loading data** - Connects to Google Drive and loads the CSV file.
* **Step 2: Data Cleaning & Preprocessing** - Filters only Dogs and Cats, handles missing values ('Unknown'), and makes the target variable.
* **Step 3: Exploratory Data Analysis (EDA)** - Shows 3 graphs about adoption rates and days in shelter.
* **Step 4: Logistic Regression** - Does one-hot encoding, trains the model, and prints the accuracy and classification report.
* **Step 5: Fairness Audit (HCDS)** - Compares the model's accuracy between dogs and cats and draws confusion matrices.
