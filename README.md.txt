# South African Retail & FMCG Inventory Optimization Engine

## 📋 Business Problem
In regional South African supply chains and distribution hubs (such as the N3 logistics corridor), maintaining optimal inventory balance is a critical challenge. Stockouts lead to lost sales and disappointed customers, while overstocking ties up valuable working capital. Furthermore, unpredictable supplier lead times and fluctuating consumer demand require a mathematical, data-driven approach to inventory replenishment rather than guesswork.

This project builds an automated Python inventory control model that processes historical sales transactions, measures demand volatility, and dynamically calculates critical stock parameters.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Google Colab / Jupyter Notebook

---

## 📊 Key Features & Calculations
1. **Demand Volatility Analysis:** Computes daily sales means and standard deviations using Poisson statistical distributions to model real-world retail demand.
2. **Dynamic Safety Stock Buffer:** Incorporates a 95% service level Z-score ($Z = 1.65$) combined with lead-time variability to protect against stockout risks.
3. **Automated Reorder Point (ROP):** Calculates exact threshold triggers for purchase orders to ensure seamless replenishment before shelves run dry.
4. **Visual Analytics:** Generates comparative bar charts visualizing SKU reorder policies and safety stock allocations.

---

## 🚀 How to Run the Code
1. Clone this repository or download the Jupyter notebook (`.ipynb`).
2. Run the script in Google Colab or your local Python environment with the required dependencies installed:
   ```bash
   pip install pandas numpy matplotlib seaborn