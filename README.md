# Product Rating & Review Analysis Project

## 📌 Project Overview
This project analyzes product data to uncover insights related to:
- Low-rated products
- Review volume behavior
- Rating polarization
- Key pain points driving customer dissatisfaction

The analysis is performed using **Python, Pandas, Matplotlib, and basic NLP techniques**.

---

## 📂 Dataset
**File used:** `NEC_Assignment_Final_Data.csv`

### Important Columns:
- `Rating_data` – Product rating (text format)
- `Review_data` – Number of reviews
- `Specs_data` – Product specifications
- `Stock_data` – Availability / offer information

---

## 🎯 Objectives
The project answers the following analytical questions:
- Percentage of products with ratings below 3.5
- Rating behavior for high-review products
- Identification of top pain points from low-rated products
- Detection of rating polarization
- Data cleaning and preprocessing challenges

---

## 🛠️ Technologies Used
- Python 3
- Pandas
- Matplotlib
- Regular Expressions (re)
- Collections (Counter)
- Jupyter Notebook / Google Colab

---

## ⚙️ Methodology
1. Load dataset using Pandas
2. Clean rating and review count columns
3. Handle missing and malformed values safely
4. Filter low-rated products (Rating < 3.5)
5. Perform keyword frequency analysis
6. Visualize results using bar charts

---

## 📊 Key Insights
- A measurable percentage of products fall below the acceptable rating threshold
- High-review products show more polarized ratings
- Common pain points are identifiable through frequent keywords
- Text-based proxy analysis can be used when raw reviews are unavailable

---

## 🚀 How to Run
1. Place `NEC_Assignment_Final_Data.csv` in the project folder
2. Open the notebook in Jupyter / Colab
3. Run cells sequentially
4. View printed insights and visualizations

---

## ⚠️ Note
Since raw customer review text was not available, `Specs_data` and `Stock_data` were used as proxy text sources to identify recurring dissatisfaction indicators.

---

## 👩‍💻 Author
**Harika Chennupalli**

---

## 📜 License
This project is licensed under the MIT License.
See the LICENSE file for details.
