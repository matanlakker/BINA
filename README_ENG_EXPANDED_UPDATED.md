
# README - AI Project on COVID-19 Severity Prediction

## Project Overview
This project compares different approaches for predicting the severity of COVID-19 cases based on **tabular clinical data (symptoms, age, gender)** and **radiographic lung images**. The research investigates whether tabular data models or image-based models provide better accuracy.

The following models were tested:

- **Machine Learning Models:** Random Forest, Logistic Regression, Decision Tree.

- **Deep Learning Models:** ANN, CNN, and Transfer Learning (ResNet50).


## Authors
  - - Chaya Brien
  - - Yuval Maimoni
  - - Uri Mor
  - - Matan Laker

## Supervisor
Dr. Revital Marbel

## GitHub Repository
[Project Link](https://github.com/matanlakker/BINA)

---

## **Project Structure**
📂 **data/** – Processed datasets (tabular + image)  
📂 **models/** – Trained models & configurations  
📂 **notebooks/** – Jupyter Notebooks for analysis  
📂 **scripts/** – Python scripts for data processing & training  
📄 **requirements.txt** – Dependencies  
📄 **README.md** – Project documentation  

---

## **Installation & Execution Instructions**

### **1. Clone the Repository**
```bash
git clone https://github.com/matanlakker/BINA.git
cd BINA
```

### **2. Install Required Packages**
```bash
pip install -r requirements.txt
```

### **3. Preprocess Data**
```bash
python scripts/preprocess_data.py
```

### **4. Train Models**
```bash
python scripts/train_model.py --model ResNet50
```

### **5. Evaluate Performance**
```bash
python scripts/evaluate.py
```

---

## **Model Performance Results**

### **Tabular Data Models**
| Model | Accuracy | Precision | Recall |
|---|---|---|---|
| Random Forest | 26.99% | 27% | 27% |
| Logistic Regression | 32.91% | 33% | 33% |
| Decision Tree | 32.24% | 32% | 32% |

### **Image-Based Models**
| Model | Accuracy | Precision | Recall |
|---|---|---|---|
| CNN | 67.3% | 69.8% | 68.5% |
| Transfer Learning (ResNet50) | 70% | 72.5% | 70% |

## **Conclusions & Recommendations**
- **Transfer Learning (ResNet50) performed best** compared to other models.

- **Image-based models achieved significantly better results** than tabular models.

- **Larger datasets are required** to further improve performance.


## **License**
This project is open-source and licensed under the MIT License.
