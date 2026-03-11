# The Influence of Urban Environmental and Socioeconomic Variables on Childhood Obesity Prevalence: A Case Study of London

## Summary

This project investigates which urban environmental and socioeconomic factors drive childhood obesity prevalence across London wards.

**Data Sources**
- Childhood obesity rates: National Child Measurement Programme (2021/22–2023/24), children aged 4–5
- Fast food outlet density: Food Standards Agency (2024)
- Green space coverage: London Data Portal (NDVI, 2024)
- Socioeconomic indicators: 2021 Census (deprivation, unemployment, car ownership, ethnic diversity)

**Methodology**

Cross-sectional analysis using two machine learning regression models — Random Forest and XGBoost — to quantify associations between ward-level variables and obesity prevalence.

**Key Findings**
- Unemployment rate is the strongest predictor (RF: 44.6%, XGBoost: 39.4% importance)
- Ethnic diversity is the second most important factor (RF: 18.8%, XGBoost: 29.4%)
- Environmental factors (fast food density, green space) show comparatively weaker predictive power
- Both models achieve similar test R² (~0.47), with consistent results reinforcing the findings

**Conclusion**

Childhood obesity in London is primarily driven by socioeconomic conditions rather than the physical food or green space environment. Effective interventions should focus on reducing unemployment and developing culturally tailored health programmes.

---

- Code: [GitHub](https://github.com/JialeiGuo1108/Childhood_Obesity)
- Data: [data/](https://github.com/JialeiGuo1108/Childhood_Obesity/tree/main/data)
- License: [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
