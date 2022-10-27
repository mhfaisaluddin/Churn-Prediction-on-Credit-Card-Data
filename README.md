# Churn Prediction on Credit Card Data
**A credit card** is a payment method that provides convenience in making payments for your financial transactions. Along with this convenience, users may have the opportunity to give a negative impact on service owners, for example ignoring the installments that must be paid and leaving the service.  Through **predictive modeling**, we can classify user churn trends based on service usage characteristics and minimize the churn occurrence by giving a treatment recommendation.

The dataset and all information about it can be downloaded at https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers. This notebook contains exploratory data analysis (EDA) stages, preprocessing, machine learning modeling, and model interpretability.

**Conclusion & Actionable Insight**
- Platinum users became the most valuable card due to its average transaction in the last 12 months, but the Gold users became the top valuable churned card. The customer is in the range of 40-49 y.o. became the most active users.
- The best predictive model is Random Forest with tuned parameters, F1 score of 82%. Through the SHAP method, we can identify the predicted customer at risk and their specific reasons.
- Review the user's profile to learn more about their preferences and previous service interactions. Accommodate their needs by providing the latest offers and services. Focus retention efforts on profitable risky users before they churn.

## File Description
- The dataset .csv, the dataset used in this project, can be downloaded from this repository or the website for the updated data.
- The code .ipnyb, the notebook (jupyter notebook) contains the end-to-end of this project. *churn_prediction_notebook.ipnyb* as the final project notebook at bootcamp, and *temporary_script.ipnyb* as the updated project notebook.

## References:
- https://www.creditcards.com/glossary/
- https://scikit-learn.org/stable/user_guide.html
- https://www.kaggle.com/learn/
- https://medium.com/swlh/understanding-the-random-forest-function-parameters-in-scikit-learn-9f42fde0101
- https://medium.com/@pararawendy19/memahami-metrik-pada-pemodelan-klasifikasi-29cd5b738ee7
- https://medium.com/@ali.soleymani.co/stop-using-random-forest-feature-importances-take-this-intuitive-approach-instead-4335205b933f
- https://shap.readthedocs.io/en/latest/index.html
- https://www.revenera.com/blog/software-monetization/what-is-user-retention/
