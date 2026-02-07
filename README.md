**Used Car Price Prediction**

End-to-end machine learning pipeline to predict used car selling prices based on vehicle and listing attributes.

---

**Results**

| Model              | MAE (lakhs) | RMSE (lakhs) |
|-------------------|------------|--------------|
| Linear Regression | ~1.20      | ~1.84        |
| Random Forest     | ~0.63      | ~0.95        |

---

**Observations**

- Random Forest performs noticeably better than Linear Regression, suggesting that used car prices follow non-linear patterns rather than simple linear trends.
- Present showroom price plays the biggest role in predictions, which makes sense since resale values are often anchored to current market prices.
- Car age and kilometers driven have a strong impact on price, reflecting common depreciation behavior.
- Brand, fuel type, transmission, and seller type influence prices but mainly act as secondary factors.
- The model tends to make larger errors for higher-priced cars, likely due to greater variability in premium vehicle listings.
