# Rock vs Mine Detection

## 📌 Project Overview
This project focuses on detecting whether an object found under the sea is a **rock** or a **mine** using **Logistic Regression**. The dataset used for training and testing consists of sonar readings, with each instance representing different frequency responses from underwater objects.

## 📂 Dataset Information
- **Dataset File**: `Sonar data.csv`
- **Columns**: 60 numerical feature columns representing sonar readings
- **Label Column**: The 60th column contains labels:
  - `R` → Rock
  - `M` → Mine

## 🚀 Steps Involved
1. **Data Preprocessing**:
   - Loaded the sonar dataset from the CSV file.
   - Separated features and labels.
   - Converted categorical labels (`R`, `M`) into numerical format.
   - Split data into training and testing sets.

2. **Model Training**:
   - Used **Logistic Regression** as the classification model.
   - Trained the model on the sonar data.
   - Evaluated accuracy and performance on the test set.

3. **Prediction & Evaluation**:
   - Tested the model on new data points.
   - Measured model accuracy using performance metrics.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

## 📊 Results
- Achieved a satisfactory classification accuracy.
- Model successfully differentiates between **rock** and **mine** based on sonar signals.

## 🔥 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rock-vs-mine-detection.git
   cd rock-vs-mine-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run `Rock_vs_Mine_Detection.ipynb`.

## 📌 Future Improvements
- Implement more advanced classification models like **Random Forest, SVM, or Neural Networks**.
- Perform feature selection to enhance accuracy.
- Deploy the model as a web application for easy accessibility.

---

**Author:** [NAMAN CHACHAN]  
📧 Contact: chachannaman@gmail.com
  

