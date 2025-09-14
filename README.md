# 🔭 Hunting of Exoplanets using Machine Learning

This project focuses on **detecting exoplanets** — planets outside our solar system — using **machine learning techniques**.  
By analyzing astronomical data, the model predicts whether a celestial object is an exoplanet or not, based on various observed parameters.

---

## 📂 Project Structure
```
Hunting_Of_Exoplanets.ipynb   # Main Jupyter Notebook
dataset/                        # Folder containing astronomical dataset (if applicable)
README.md                       # Project documentation
```

---

## 🚀 Features
- Data loading and preprocessing of astronomical datasets.
- **Exploratory Data Analysis (EDA)** to understand features related to exoplanet detection.
- Implementation of **machine learning models** for classification.
- Performance evaluation using metrics like accuracy and confusion matrix.
- Visual representation of results with charts and graphs.

---

## 🛠 Tech Stack
- **Programming Language:** Python 🐍
- **Libraries Used:**
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computations
  - `matplotlib` & `seaborn` - Data visualization
  - `scikit-learn` - Machine learning algorithms and evaluation
  - `jupyter` - Notebook environment

---

## 📊 Workflow
1. **Import Libraries** – Load essential Python libraries.
2. **Load Dataset** – Import exoplanet dataset for analysis.
3. **Data Preprocessing** – Handle missing values, normalization, and feature scaling.
4. **Exploratory Data Analysis (EDA)** –  
   - Understand data distributions.
   - Identify key factors affecting exoplanet detection.
   - Visualize relationships between variables.
5. **Model Building** – Train and test models such as:
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - Support Vector Machines (SVM)
6. **Model Evaluation** – Evaluate using metrics:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix
7. **Predictions** – Classify new data points to predict the presence of exoplanets.

---

## 📥 Installation
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/hunting-of-exoplanets.git
cd hunting-of-exoplanets
```

### **2. Create Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

---

## 🧪 Usage
To run the project:
```bash
jupyter notebook
```
Then open `Hunting_Of_Exoplanets.ipynb` and execute the cells step-by-step.

---

## 📈 Results
- Visualization of features that are most important for identifying exoplanets.
- Model performance comparison across different machine learning algorithms.
- A trained model capable of predicting whether a celestial object is an exoplanet.

Example Result:
| **Object ID** | **Predicted Label** |
|---------------|---------------------|
| KOI-1234.01   | Exoplanet 🌍 |
| KOI-5678.02   | Not an Exoplanet ✖️ |

---

## 📜 License
This project is licensed under the MIT License.  
Feel free to use and modify for research and learning purposes.

---

## 👤 Author
- **Krishna Karbhari**
- GitHub: [kishu01karb](https://github.com/kishu01karb)

---

## 🌌 Acknowledgements
- NASA's Kepler Space Telescope mission data.
- [Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)
- Inspiration from astronomical research and machine learning applications in space exploration.
