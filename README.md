
**Project Objective**

The project aims to predict housing listing prices using data scraped from a real estate website with Selenium, incorporating various house features.

**Project Process**

The process begins with feature engineering to extract both numerical and categorical data. Next, text data is embedded using an LLM model(Flan-T5) from Hugging Face. Finally, the datasets are merged, and XGBoost and Random Forest models are trained to predict listing prices. 

**Outcome**

The XGBoost model demonstrates superior performance compared to the Random Forest model, resulting in a relatively high R^2
