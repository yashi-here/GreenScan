# GreenScan
AI-powered browser extension that provides instant eco and health scores for online products, helping users make sustainable and health-conscious shopping decisions.
# Eco-Health Product Scorer

## Project Overview
The **Eco-Health Product Scorer** is a browser extension powered by AI that provides users with **instant eco and health scores** for products while shopping online. The system scans product pages, extracts relevant parameters, and predicts scores using a machine learning model, helping users make **sustainable and health-conscious choices**.

---

## Features
- **Real-time Scoring:** Displays eco & health scores on product pages.  
- **AI-Powered:** Multi-output Random Forest Regressor predicts scores based on product attributes.  
- **Extensible Pipeline:** Easily integrates with any e-commerce platform via a browser extension.  
- **Transparent & Educational:** Helps consumers understand product sustainability and health impact.

---

## Technical Approach
1. **Data Extraction:** Browser extension scrapes product name and ingredients/features.  
2. **Feature Engineering:** Encodes and normalizes data for model input.  
3. **Model:** Multi-output Random Forest Regressor predicts eco & health scores.  
4. **Training & Evaluation:** Trained on labeled datasets; metrics include RMSE, MAE, R².  
5. **Integration:** Real-time predictions served via Flask/FastAPI; displayed in the extension.  
6. **Scalability:** Cloud-hosted AI pipeline with caching and CI/CD support.

**Tech Stack:**  
- Python, Scikit-learn, Pandas, NumPy, Matplotlib/Seaborn  
- Flask/FastAPI for backend API  
- JavaScript & Browser Extension APIs (Chrome/Edge)  
- AWS EC2/Lambda, Docker, Redis, GitHub Actions  

## Directory Structure

eco-health-product-scorer/
│
├── README.md
├── requirements.txt
├── LICENSE
├── data/ # Placeholder dataset
├── model/
│ ├── model.py # Random Forest placeholder
│ ├── train.py # Training pipeline 
│ └── predict.py # Inference script
├── extension/ # Browser extension placeholder
│ └── README.md
└── docs/ # Flowcharts, diagrams


---

## Current Status
- Model and pipeline structure implemented (placeholder model)  
- Browser extension ready
- Integration on process 
- All diagrams and workflows documented  

---

## Future Work
- Improve model accuracy with larger datasets  
- Complete integration with live browser extension  
- Expand scoring to more product categories and platforms  

---



## Directory Structure
