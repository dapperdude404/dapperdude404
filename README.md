## Hi there 👋

<!--
**dapperdude404/dapperdude404** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
# 🚀 M.Tech Artificial Intelligence (AI) — Master Repository

<div align="center">

[![Amity University](https://img.shields.io/badge/Institution-Amity%20University-blue?style=for-the-badge&logo=graduated-circle)](https://amity.edu)
[![Degree](https://img.shields.io/badge/Program-M.Tech%20(AI)-orange?style=for-the-badge&logo=artificial-intelligence)](https://github.com)
[![Status](https://img.shields.io/badge/Semester-1%20%2F%202-success?style=for-the-badge&logo=target)](https://github.com)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)

*Official academic repository containing practical lab manuals, machine learning implementations, mathematical derivations, IoT architectures, and project management frameworks.*

</div>

---

## 👨‍💻 Student Profile
* **Name:** Aryan Sengar
* **Enrollment No:** A2305226001
* **Program:** M.Tech in Artificial Intelligence (Semester I)
* **University:** Amity University, Lucknow Campus

---

## 📂 Repository Structure

```text
├── AIML601-Laboratory-Records/       # Official lab manuals, regression, KNN, TinyML quantization
├── Machine-Learning-and-DWDM/        # Mathematical derivations, regression scripts, market-basket analysis
├── IoT-and-Edge-AI/                  # CNN architectures, ANN integration, pixel image processing pipelines
├── Advanced-Software-Project-Mgmt/   # ASPM frameworks, WBS, PERT/CPM calculations, EVM metrics
├── Professional-Communication/       # Persuasive communication modules, ELM, message framing
└── German-Language-A1/               # A1 level vocabulary, conjugations, time expressions, self-introductions
```

---

## 📚 Core Curriculum & Coursework

### 1. Machine Learning & Data Mining (AIML202 / AIML601)
* **Regression Analysis:** Step-by-step mathematical derivations for Simple Linear Regression (Slope $b_1$, Intercept $b_0$, Means $\bar{x}, \bar{y}$, MSE, MAE, $R^2$ scores).
* **Classification & Clustering:** K-Nearest Neighbors (KNN), K-Means Clustering (WCSS/Inertia, Elbow method), and Hierarchical Clustering (Ward's linkage, Dendrograms).
* **Data Preprocessing:** Z-score normalization (Standardization), Entropy, Information Gain, and Gini Index formulations.

### 2. Neural Networks & Edge AI (IoT Module)
* **CNN Architecture:** Comprehensive pipeline breakdowns (`Convolution` $\rightarrow$ `ReLU` $\rightarrow$ `Pooling` $\rightarrow$ `Flattened` $\rightarrow$ `Fully Connected (ANN)`).
* **Pixel Image Processing:** Spatial feature extraction vs. flat 1D vector representations in ANNs.
* **Quantization & Deployment:** TinyML model optimization for edge hardware.

### 3. Advanced Software Project Management (ASPM)
* **Process Models & Estimation:** COCOMO II, Function Point Analysis (FPA), and Use Case Points.
* **Network Scheduling:** PERT 3-point estimation ($T_e = \frac{o + 4m + p}{6}$) and Critical Path Method (CPM) float calculations.
* **Earned Value Management (EVM):** PV, EV, AC, CV, SV, CPI, and SPI performance metrics.

### 4. Professional & Business Communication (Module 5)
* **Persuasive Frameworks:** Elaboration Likelihood Model (Central vs. Peripheral routes).
* **Message Framing:** Gain frames vs. Loss frames in executive decision-making.
* **Evidence Hierarchy:** Blending Tier 1 quantitative metrics with Tier 3 narrative case studies.

### 5. German Language (A1 Level)
* Numbers (*Die Zahlen*), Time expressions (*Die Uhrzeit*), Verb conjugations (*haben, sein, machen, arbeiten*), and structured Self-Introductions (*Sich vorstellen*).

---

## 🛠️ Tech Stack & Libraries

* **Languages:** Python, SQL, Markdown
* **Data Science & ML:** NumPy, Pandas, SciPy, Scikit-Learn
* **Deep Learning:** TensorFlow, PyTorch, Keras (TinyML)
* **Visualization:** Matplotlib, Seaborn
* **Tools:** Git, GitHub, MS Project, Google Docs / LaTeX

---

## 📜 Lab Implementations Example (`SciPy Linear Regression`)

```python
import matplotlib.pyplot as plt
from scipy import stats

# Sample Dataset
x = [5, 7, 8, 7, 2, 17, 2, 9, 4, 11, 12, 9, 6]
y = [99, 86, 87, 88, 111, 86, 103, 87, 94, 78, 77, 85, 86]

# Linear Regression Computation
slope, intercept, r, p, std_err = stats.linregress(x, y)

def predict_value(x_val):
    return slope * x_val + intercept

model_line = list(map(predict_value, x))

# Plotting
plt.scatter(x, y, color='blue', label='Actual Data')
plt.plot(x, model_line, color='red', label='Fitted Line')
plt.xlabel("X Variable")
plt.ylabel("Y Variable")
plt.title("Linear Regression Model")
plt.legend()
plt.show()
```

---

## 🤝 Connect & Collaboration
* **Institution:** Amity University, Lucknow
* **Repository Maintenance:** Active update cycle for M.Tech Semester 1 & 2 practical submissions and viva preparation.

⭐ *Feel free to star this repository if you find the notes and implementations helpful for your academic journey!*
