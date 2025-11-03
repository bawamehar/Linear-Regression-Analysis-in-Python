
# Linear Regression Analysis in Python

This repository contains a Jupyter Notebook that demonstrates the complete workflow of **Linear Regression** using two datasets — *Advertising* and *Fuel Consumption*.  
The notebook includes data visualization, model training, coefficient interpretation, and performance evaluation using statistical error metrics.

---

## 📊 Datasets Used

### 1. Advertising.csv
This dataset represents marketing data for various media channels and their effect on product sales.

| Feature | Description |
|----------|--------------|
| TV | Budget spent on TV advertising (in thousands of dollars) |
| Radio | Budget spent on radio advertising (in thousands of dollars) |
| Newspaper | Budget spent on newspaper advertising (in thousands of dollars) |
| Sales | Product sales (in thousands of units) |

**Insight:**  
> The model predicts that sales increase by **0.0557 units for every 1 unit increase in TV advertising**.

---

### 2. FuelConsumption.csv
This dataset represents data about vehicles including engine size, fuel consumption, and CO₂ emissions.

| Feature | Description |
|----------|--------------|
| ENGINESIZE | Engine size of the vehicle |
| CYLINDERS | Number of engine cylinders |
| FUELCONSUMPTION_COMB | Combined fuel consumption (L/100 km) |
| CO2EMISSIONS | Emission of CO₂ (grams/km) |

**Insights:**
- CO₂ emission increases by **38.99 units for every 1 unit increase in engine size**.  
- CO₂ emission increases by **16.31 units for every 1 unit increase in combined fuel consumption**.

---

## 🧠 Machine Learning Workflow

1. **Data Loading & Exploration**  
   - Used `pandas` to read CSV files  
   - Performed data inspection and statistical summary  

2. **Data Visualization**  
   - Visualized relationships using `matplotlib` and `seaborn`  
   - Correlation heatmaps, regression plots, and scatter plots  

3. **Model Training**  
   - Built Linear Regression model using `sklearn`  
   - Split data into training and test sets  

4. **Model Evaluation**  
   Calculated key regression errors:
   ```python
   RSS = sum((y_pred - y_test) ** 2)
   MAE = np.mean(abs(y_pred - y_test))
   MSE = np.mean((y_pred - y_test) ** 2)
   RMSE = np.sqrt(MSE)
   ```
   - **RSS**: Residual Sum of Squares  
   - **MAE**: Mean Absolute Error  
   - **MSE**: Mean Squared Error  
   - **RMSE**: Root Mean Squared Error  

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📈 Key Learnings

- Understanding of how Linear Regression models work
- Interpreting coefficients to make real-world inferences
- Evaluating regression performance using statistical metrics
- Importance of visualization in feature relationship analysis

---

## 📂 File Structure

```
📦 Linear-Regression-Analysis-in-Python
│
├── Advertising.csv
├── FuelConsumption.csv
├── Linear_Regression.ipynb
└── README.md
```

---

## 👨‍💻 Author
**Mehar Bawa**

If you like this project, feel free to ⭐ the repo and connect!
