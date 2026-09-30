# Healthy Lifestyle Hackathon - Vaccine Adoption Prediction

A Machine Learning & predictive analytics solution classifying vaccine adoption using LightGBM.

## Project Summary
– **Tools & Technologies**: Python, LightGBM, NumPy, Pandas, Scikit-Learn.
– **Built a LightGBM multi-label classification model** for vaccine adoption prediction (`xyz_vaccine` & `seasonal_vaccine`), achieving **~0.84 ROC-AUC**.
– **Built an end-to-end ML pipeline**: feature engineering, categorical encoding, missing-value treatment, and class imbalance handling.
– **Tuned hyperparameters** and evaluated models to generate competition-ready predictions on unseen test data.

---

## File Structure
- `Healthy_Lifestyle_Hackathon_Vaccine_Adoption.ipynb` - Main Jupyter Notebook containing data preprocessing, feature engineering, LightGBM model training, evaluation, and test predictions.
- `submission_format.csv` - Target predictions containing `respondent_id`, `xyz_vaccine`, and `seasonal_vaccine` adoption probabilities.

---

## Model Performance & Evaluation
- **Seasonal Vaccine ROC-AUC**: ~0.8390 (0.84 AUC)
- **Evaluation Metric**: Mean Area Under the Receiver Operating Characteristic Curve (ROC-AUC) score.
