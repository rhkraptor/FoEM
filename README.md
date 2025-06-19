
---

## Models Implemented

- **Baseline Models**: Naive, Mean, Drift, Seasonal Naive
- **Exponential Smoothing**: SES, Holt, Holt-Winters
- **ARIMA (9,1,9)**: Parameterized manually after ADF and ACF/PACF analysis
- **Prophet**: Trend-focused model with automatic changepoint detection
- **RNN & LSTM**: Deep learning models for non-linear temporal modeling

---

## Evaluation Metrics

Model performance was evaluated using:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **MAPE / sMAPE**
- **MASE (Mean Absolute Scaled Error)**

Visual comparison plots and metric tables highlight LSTM as the most accurate model on the test set.

> Note:
Some evaluation metric values presented in this report may slightly differ from those in the original notebook. This is due to the notebook being reloaded at a later stage, which can introduce variability in model predictions—especially for stochastic methods like RNN and LSTM. These changes do not affect the overall conclusions or model rankings but may lead to minor numerical differences in reported metrics.

---

## Technologies Used

- Python (NumPy, pandas, matplotlib, seaborn, statsmodels)
- Facebook Prophet, TensorFlow/Keras
- Jupyter Notebooks

---

## Final Report

The final academic report includes:
- Motivation and methodology
- Step-by-step modeling logic
- Evaluation tables and visual insights
- Critical reflection on model performance

> [Download Full Report (PDF)](https://github.com/rhkraptor/FoEM/SS25_FOEM_FinalPaper_Hussnain_Khalil.pdf)

---

## Author

**Hussnain Khalil**  
4th Semester B.Eng. Data Science in Engineering and Management  
Technische Hochschule Ingolstadt  
 [LinkedIn](https://www.linkedin.com/in/hussnain-khalil)  
 huk7464@thi.de  
 [GitHub](https://github.com/rhkraptor)

---

## Citation

If this project helps your work or learning, please consider citing:

```bibtex
@misc{khalil2025foem,
  title={Applied Time Series Forecasting in Engineering and Management: From Bitcoin EDA to S\&P 500 Model Evaluation},
  author={Hussnain Khalil},
  year={2025},
  note={Undergraduate project at THI}
}
