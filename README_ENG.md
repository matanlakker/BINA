
# README - AI Project on COVID-19 Severity Prediction

## Project Overview
This project investigates different approaches for predicting the severity of COVID-19 cases based on both tabular clinical data and radiographic lung images. Various models were developed and evaluated:

- **Machine Learning Models:** Random Forest, Logistic Regression, Decision Tree.
- **Deep Learning Models:** Artificial Neural Networks (ANN), Convolutional Neural Networks (CNN), and Transfer Learning using ResNet50.

Findings indicate that image-based models, particularly those leveraging Transfer Learning with ResNet50, achieved the highest accuracy (70%), whereas models based on tabular data performed significantly worse (32%-33%).

## Authors
- Chaya Brien (213199896)
- Yuval Maimoni (211450184)
- Uri Mor (213437155)
- Matan Laker (314683301)

## Supervisor
Dr. Revital Marbel

## GitHub Repository
[Project Link](https://github.com/matanlakker/BINA)

## Repository Structure
📂 **data/** – Processed datasets (tabular + image)  
📂 **models/** – Trained models & configurations  
📂 **notebooks/** – Jupyter Notebooks for analysis  
📂 **scripts/** – Python scripts for data processing & training  
📄 **requirements.txt** – Dependencies  
📄 **README.md** – Project documentation  

## How to Run the Project
1. Clone the repository:

   ```bash
   git clone https://github.com/matanlakker/BINA.git
   cd BINA
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run data preprocessing:

   ```bash
   python scripts/preprocess_data.py
   ```
4. Train models:

   ```bash
   python scripts/train_model.py --model ResNet50
   ```
5. Evaluate models:

   ```bash
   python scripts/evaluate.py
   ```

## License
This project is open-source and licensed under the MIT License.
