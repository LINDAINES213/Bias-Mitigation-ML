# Bias Mitigation in Machine Learning

This repository demonstrates bias detection and mitigation techniques applied to the **Adult Income dataset**.  
This is a Responsible AI project which includes reproducible code, results, and documentation.

# Authors

- Linda Inés Jiménez Vides

- Diego Alexander Hernández Silvestre

- Mario Antonio Guerra Morales

- Kristopher Javier Alvarado López

- Daniel Adolfo Sarmiento Peralta

**Project Website (GitHub Pages):**  
[https://lindaines213.github.io/Bias-Mitigation-ML/](https://lindaines213.github.io/Bias-Mitigation-ML/)

---

## Project Structure

## ▶️ Reproduction Instructions

## 1) Clone the repository
```bash
git clone https://github.com/LINDAINES213/Bias-Mitigation-ML.git
cd Bias-Mitigation-ML
```
## 2) Create and activate a virtual environment

### Windows
```bash
python -m venv .venv
. .venv/Scripts/activate
```

### macOS/Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
```

## 3) Install dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

## 4) Run the notebook
```bash
jupyter lab
```

## 📊 Key Results

- **Baseline fairness metrics** show disparities by **sex** and **race**  
  - Metrics: *Demographic Parity Difference*, *Equal Opportunity Difference*  
- **Bias mitigation (Reweighing)** reduces disparities while maintaining accuracy  
- **Interpretability with SHAP values** highlights the most influential features  
- Visual and tabular results are available on the [project website](https://lindaines213.github.io/Bias-Mitigation-ML/)

### Website sections
- [Figures](https://lindaines213.github.io/Bias-Mitigation-ML/figures/) – SHAP and fairness plots  
- [Reports](https://lindaines213.github.io/Bias-Mitigation-ML/reports/) – Standalone HTML reports  
- [Data](https://lindaines213.github.io/Bias-Mitigation-ML/data/) – CSV files rendered as tables  

