# jedha_dts_getaround
getaround (Jedha Deployment project)

# Getaround modules

- jedha-dts-getaround-schemas
    This module is a shared Python package that defines data models and validation schemas used across different compenents of the getaround ecosystem.

- jedha-dts-getaround-eda
    - EDA for Rental Price prediction
    - EDA for Delay analysis

- jedha-dts-getaround-price-predictor
    - rental price model pipeline
    - log model training experiment (model, params, scores)

- jedha-dts-getaround-dashboard
    - deployed on Streamlit HF space
    - Dashboard 
        - displaying delay analysis results
        - provide acces point to rental price prediction

- jedha-dts-getaround-api
    - deployed on FastApi HF Space
    - rental price predict endpoint