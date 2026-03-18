# Time Series Analysis

**Haydar Kilic, Artificial Intelligence Engineering**

This repository contains university-level Python notebooks for a Time Series Analysis course. Each notebook reinforces theoretical content with Python implementations, visualisations, and interpreted outputs.

---

## 📚 Contents

| Notebook | Lecture | Topics |
|----------|---------|--------|
| [`Lecture_01_Introduction.ipynb`](Lecture_01_Introduction.ipynb) | Lecture 1 | Time series examples, simple models (WN/MA/AR), stationarity, ACF, trend and seasonality estimation, Ljung-Box test |
| [`Lecture_02_Stationary_Processes.ipynb`](Lecture_02_Stationary_Processes.ipynb) | Lecture 2 | ACVF/ACF theory, linear processes, Durbin-Levinson algorithm, Wold decomposition |
| [`Lecture_03_ARMA_Models.ipynb`](Lecture_03_ARMA_Models.ipynb) | Lecture 3 | ARMA(p,q), causality and invertibility (characteristic roots), Yule-Walker ACF, model identification (ACF/PACF), h-step forecasting |
| [`Lecture_04_Spectral_Analysis.ipynb`](Lecture_04_Spectral_Analysis.ipynb) | Lecture 4 | Theoretical spectral density, periodogram, Welch method, Butterworth filters |
| [`Lecture_05_ARMA_Modelling.ipynb`](Lecture_05_ARMA_Modelling.ipynb) | Lecture 5 | Yule-Walker and Burg estimation, MLE, bootstrap, residual diagnostics (ACF/QQ/LB), AICC model selection |
| [`Lecture_06_ARIMA_SARIMA.ipynb`](Lecture_06_ARIMA_SARIMA.ipynb) | Lecture 6 | Integrated processes, differencing, ADF/KPSS unit root tests, SARIMA, AirPassengers example |
| [`Lecture_07_Financial_Time_Series.ipynb`](Lecture_07_Financial_Time_Series.ipynb) | Lecture 7 | Financial return stylized facts, ARCH/GARCH(1,1)/EGARCH, volatility clustering, Geometric Brownian Motion, Black-Scholes |
| [`Lecture_08_Multivariate_Time_Series.ipynb`](Lecture_08_Multivariate_Time_Series.ipynb) | Lecture 8 | Cross-covariance (CCF), VAR(p) model, lag selection, Granger causality, Engle-Granger cointegration |
| [`Lecture_09_State_Space_Kalman.ipynb`](Lecture_09_State_Space_Kalman.ipynb) | Lecture 9 | State-space representation, Kalman filter (manual implementation), local linear trend model, missing observation handling |
| [`Lecture_10_Forecasting.ipynb`](Lecture_10_Forecasting.ipynb) | Lecture 10 | ARAR algorithm, SES/Holt/Holt-Winters (additive & multiplicative), 5-method benchmark comparison |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/HAYDARKILIC/time_series_analysis.git
cd time_series_analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter
```bash
jupyter notebook
```
---

## 🔧 Requirements

| Library | Version | Usage |
|---------|---------|-------|
| `numpy` | ≥ 2.0 | Core numerical operations |
| `pandas` | ≥ 2.0 | Time series data management |
| `matplotlib` | ≥ 3.7 | Visualisation |
| `scipy` | ≥ 1.11 | Statistical tests, signal processing |
| `statsmodels` | ≥ 0.14 | ARIMA/SARIMA/VAR/ETS models |
| `arch` | ≥ 6.0 | ARCH/GARCH/EGARCH models |
| `filterpy` | ≥ 1.4 | Kalman filter (Lecture 9, optional) |
| `scikit-learn` | ≥ 1.3 | Error metrics (MSE/MAE) |

For the full pinned version list see [`requirements.txt`](requirements.txt).

## 📖 Reference

Brockwell, P. J., & Davis, R. A. (2009). Time series: theory and methods. Springer science & business media.

---
