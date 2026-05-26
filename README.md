# Al-Based-Water-Demand-Forecasting-for-Campus-Operations

I had a wonderful opportunity to create a sustainable solution as an internship project for 1B1M. I  was also selected in top 30 Best performers. While working solo and I have learnt a lot about time management and overall the support and guidance from the mentors helped me a lot. Despite the initial hurdle of not having access to real campus data, I learned how to generate realistic synthetic data that captured seasonal, weekly, and weather‑driven patterns.

It is a project that  presents a **data‑driven approach** to forecast daily water demand in a campus zone (Hostel A) using a **Long Short‑Term Memory (LSTM)** neural network. The model uses historical consumption, temperature, rainfall, and calendar information to predict next‑day demand. By aligning pumping schedules with predicted demand, the system can reduce energy waste and improve water supply reliability.

> 🧪 **Note:** Due to limited access to real campus data, a synthetic dataset was generated that mimics realistic seasonal, weekly, and weather‑driven patterns. The methodology is fully reproducible and ready for deployment with real data.
---

##  Problem Statement :
Campuses often operate on fixed pumping schedules, leading to either over‑pumping (wasting energy) or water shortages during demand spikes. An adaptive, forecast‑based approach can save water, electricity, and reduce carbon footprint.

---

##  Objectives :

- Build a machine learning model to predict next‑day water demand with less than 10% error (relative to average demand).
- Develop an interactive dashboard to visualise forecasts and suggest pumping schedules.
- Quantify potential energy savings and CO₂ reduction.

---

##  How to Run :

### 1. Clone the repository

```bash
git clone https://github.com/your-username/water-demand-forecasting.git
cd water-demand-forecasting
```

### 2. Install dependencies

```bash
pip install tensorflow pandas numpy matplotlib plotly scikit-learn
```

### 3. Run the Jupyter notebook

```bash
jupyter notebook "Al-Based Water Demand Forecasting for Campus Operations.ipynb"
```
The notebook will:
- Generate synthetic data
- Train the LSTM model
- Plot actual vs. predicted demand
- Calculate energy savings

##  Repository Structure :
```
├── Al-Based Water Demand Forecasting for Campus Operations.ipynb   # Main notebook
├── Project Submission Template.pdf                                 # Internship submission
├── 1B1M project report.docx                                        # Detailed project report
└── README.md                                                       # This file
└── Info                                                            # Additional Summary
```
