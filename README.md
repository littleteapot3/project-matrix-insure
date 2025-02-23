# project-MatrixInsure
A linear algebra project for insurance analytics. 

## 📌 Overview  
This project is all about using **linear algebra and machine learning** to help **Sure Tomorrow Insurance** make smarter decisions. The company wants to:  
- Find similar customers for better marketing,  
- Predict who might receive insurance benefits,  
- Estimate how many benefits a customer could get, and  
- Keep customer data private without messing up predictions.  

By working through these challenges, we’re blending math, coding, and real-world problem-solving!  

## 🎯 Goals  
The main goal of this project is to **explore how linear algebra powers machine learning models** in practical scenarios. Along the way, we’ll:  
- Use **distance metrics** to group similar customers.  
- Train models to **predict insurance benefits** (and compare them to a random guess).  
- Build a **linear regression model** to estimate benefits.  
- Apply **data masking** to protect personal information—without breaking our model.  

## 📊 The Data  

The dataset (`insurance_us.csv`) contains:  
- **Features**: Gender, age, salary, and number of family members.  
- **Target**: Number of insurance benefits received in the last five years.  

## 🛠 How It Works  

### 🔍 Step 1: Exploratory Data Analysis (EDA)  
- Clean the data and check for missing values.  
- Visualize patterns and relationships in the data.  

### 🤖 Step 2: Build Machine Learning Models  
- **Find similar customers** using k-Nearest Neighbors (kNN).  
- **Predict benefit eligibility** with logistic regression.  
- **Estimate the number of benefits** using linear regression.  
- **Protect customer data** by applying data masking and ensuring models still work.  

## 📈 Key Takeaways  

- **kNN clustering** successfully identified groups of similar customers.  
- **Predictive models** performed better than a random guess (which is always a good sign!).  
- **Linear regression** provided reasonable estimates for the number of benefits.  
- **Data masking** worked! We protected customer data without hurting accuracy.

## 🔦 Future Improvements

- Improve EDA with additional visualizations (e.g., correlation heatmaps).
- Optimize feature selection for similarity analysis.
- Explore alternative regression techniques (e.g., Ridge, Lasso).
- Extend data obfuscation methods and assess real-world implications.

## How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/project-MatrixInsure.git
   cd project-MatrixInsure

