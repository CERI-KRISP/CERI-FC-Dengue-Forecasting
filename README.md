# Dengue Forecasting Model Repository

## Team and Contributors

**CERI Forecasting Club:**  

*Graeme Dor<sup>1</sup>, Monika Moir<sup>1</sup>, Gaspary Mwanyika<sup>1</sup>, Jenicca Poongavanan<sup>1</sup>, Houriiyah Tegally<sup>1</sup>*  

<sub>
<sup>1</sup>Centre for Epidemic Response and Innovation (CERI), School of Data Science and Computational Thinking, Stellenbosch University, Stellenbosch, South Africa
</sub>

---

## Repository Structure

A brief description of the contents and purpose of each folder and file in the repository:
<pre>
```
├── data/                  # Contains all datasets used for training and evaluation
├── notebooks/             # Jupyter/R notebooks used for exploratory data analysis
├── src/                   # Source code including preprocessing, modeling, and utilities
├── models/                # Trained models, weights, or model configuration files
├── output/                # Forecast results, logs, and plots
└── README.md              # Project overview and documentation
```
</pre>


---

## Libraries and Dependencies

A list of all libraries and packages used to process the data and train your model:

- `pandas`

- `numpy`
 
- `scikit-learn`
 
- `prophet`

---

## Data and Variables

### Datasets and variables used
- Dengue.csv

- Climate.csv  

### Data preprocessing
- Describe how the data was cleaned and transformed.  

### Variable selection
- Explain how predictors were chosen.
    
- Link to relevant code or analysis section.

---

## Model Training

### Training details
- Describe model architecture or algorithms used.
    
- Specify any cross-validation or time series split methods.

### Hyperparameter optimization
- Detail any grid search, Bayesian optimization, or manual tuning used.

### Training code
- Point to the specific script or notebook.

---

## Data Usage Restriction

- Forecasts from EW 41 (year N) to EW 40 (year N+1) are based **only** on data up to EW 25 (year N).
  
- Describe how this was enforced in preprocessing or model training.

---

## Predictive Uncertainty

- How are your prediction intervals computed?
