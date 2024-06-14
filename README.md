
**Project Objective**

The project aims to predict housing listing prices using data scraped from a real estate website with Selenium, incorporating various house features.

**Project Process**

 - The process begins with feature engineering to extract both numerical and categorical data. 
 - Text data is embedded using an LLM model(Flan-T5) from Hugging Face. 
 - Numerical and categorical data, along with embeddings, are integrated to train XGBoost and Random Forest models for predicting listing prices.

**Outcome**

The XGBoost model demonstrates superior performance compared to the Random Forest model, resulting in a relatively high R^2
