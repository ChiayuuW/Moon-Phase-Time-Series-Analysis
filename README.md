# Moon Phase Time Series Analysis 🌙

This project analyzes the **durations between lunar phases** (New Moon, First Quarter, Full Moon, Last Quarter) using **time series methods** such as ARIMA modeling, Fourier analysis, and residual diagnostics.  

We investigate whether lunar phase durations are evenly distributed and explore their cyclical fluctuations over time.

---

## 📌 Project Overview
- **Dataset**: Moon phase data (1970–2021) from [Astropixels](https://astropixels.com/ephemeris/phasescat/phasescat.html)  
- **Goal**: Evaluate if the durations between phases are stable or exhibit meaningful variation.  
- **Techniques Used**:
  - Exploratory Data Analysis (cycle durations & beating patterns)  
  - One-way ANOVA (testing equality of durations)  
  - Stationarity check with ADF test  
  - ARIMA modeling (short-term forecasting)  
  - Fourier Transform (long-term periodic structure detection)  

---

## 📊 Key Findings
- Lunar phase durations average ~7.38 days but are **not equal**.  
- They follow a **wave-like oscillation**, compensating each other to keep the total cycle consistent (~29.5 days).  
- ARIMA(13,0,5) model fits short-term trends but residuals show autocorrelation.  
- Fourier analysis reveals a strong **14-cycle periodicity**, matching astronomical expectations.  

---

## 🚀 Future Work
- Extend dataset and integrate **astronomical simulations**.  
- Explore **nonlinear models** (TAR, GARCH) for residual dynamics.  
- Include Fourier terms directly into SARIMA models.  

---

## 📂 Repository Structure
- `Final-Project.pdf` – Full report (methods, results, and discussion)  
- (Optional) Add code/notebooks if you have them  

---

## 👥 Authors
- Chia-Yu Wei  
- Ming-Wei Kuo  

---

## 📖 Reference
Fred Espenak. *Catalog of Moon Phases*. Retrieved from [Astropixels](https://astropixels.com/ephemeris/phasescat/phasescat.html).
