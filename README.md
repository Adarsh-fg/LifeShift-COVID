## **LifeShift-COVID: A COVID-19 Psychological Effects Prediction App**

### **Overview**
LifeShift-COVID is a Streamlit-based web application that predicts whether individuals are likely to experience lifestyle changes due to the psychological effects of the COVID-19 pandemic. This app leverages a machine learning model trained using a decision tree algorithm.

---

### **Key Features**
- Upload a CSV file with user data to make predictions.
- Automated preprocessing for numerical and categorical data.
- Outputs predictions indicating if a lifestyle change is likely.

---

### **Tech Stack**
- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy

---

### **How It Works**
1. The app prompts the user to upload a CSV file containing the relevant data.
2. Data preprocessing includes:
   - Mapping age groups to numerical values.
   - Standardizing numerical features.
   - One-hot encoding categorical features.
3. A decision tree model (`decision_tree_model_covid.pkl`) makes predictions based on the processed data.
4. The prediction results are displayed on the screen.

---

### **Installation Instructions**
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd LifeShift-COVID
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run covid_app.py
   ```

---

### **Usage**
- Prepare a CSV file with user data similar to `covid_preprocessed_data.csv`.
- Upload the file when prompted by the app.
- View the prediction results.

---

### **Sample Data**
The app requires data with columns for both numerical and categorical features. Below are some key features expected in the input:
- Age group (mapped internally by the app)
- Other health, social, or demographic data

---

### **Model Information**
The machine learning model is a decision tree classifier stored as `decision_tree_model_covid.pkl`.

---

### **Future Improvements**
- Extend model capability with more advanced algorithms.
- Add visualization for better data analysis.
- Include user demographic trends in predictions.

---

### **Contributors**
- Adarsh-fg

---

### **License**
MIT License. 

---

Would you like any edits or additional sections in the README? 
