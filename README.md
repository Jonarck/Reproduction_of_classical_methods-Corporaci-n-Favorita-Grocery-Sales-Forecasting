# Project Repository
Project Theme: In order to familiarize ourselves with technical details at various stages of time series tasks, this project aims to address the time series unit sales prediction challenge within a classical kaggle competition - Corporación Favorita Grocery Sales Forecasting competition。(From HKUST(GZ)-DSAA5021 Instructed by Prof. TANG Jing)

**Note: We selected and extensively studied the solutions of the top competitors in the competition, and ultimately found that they employed relatively similar input-output modeling approaches. Therefore, we began our own practical implementation based on this insight:**
[reference_project_1-by_oberoiheman](https://github.com/oberoiheman/Corporaci-n-Favorita-Grocery-Sales-Forecasting "Corporaci-n-Favorita-Grocery-Sales-Forecasting"), 
[reference_project_2-by_sjvasquez](https://github.com/sjvasquez/web-traffic-forecasting "web-traffic-forecasting"), 
[reference_project_3-by_weiwei](https://www.kaggle.com/code/shixw125/1st-place-lgb-model-public-0-506-private-0-511/script "1st Place LGB Model(public:0.506, private:0.511)"), 

Through exploration and reconstruction of historical sales records, sales planning, and auxiliary information, we successfully constructed feature vectors for each individual product, organized into a comprehensive Feature-Batch encompassing all items. Leveraging the XGBoost machine learning model, which takes the complete Feature-Batch as input and predicts the unit sales for all items over the upcoming 16 days, we trained the model using the provided data to forecast the unit sales of thousands of products across various Favorita stores in Ecuador over the next 16 days.

In the given topic provided by our teacher, we chose this task mainly because we encountered relevant knowledge in the field of "time series prediction" during stock forecasting assignments, and we felt the learning value and application prospects of this machine learning domain. Therefore, our initial motivation is to fully engage in learning the practical application of machine learning time series prediction tasks. 

To achieve this, we primarily need to clarify several important subtasks aimed at learning: 
- First, we should define the pipeline for time series prediction tasks.
- Second, we need to understand how to model based on time series prediction tasks, defining how the objective should be modeled as output and how the data should be modeled as input.
- **Third, we need to familiarize ourselves with technical details at various stages of time series tasks, such as initial data exploration, mid-term model selection, and late-stage model evaluation.**

Based on these motivations and tasks, we have outlined the fundamental approach to completing this project: **within a more refined application-oriented competition, using an existed excellent solution as a "Role Model", we aim to accomplish the several learning-oriented subtasks we’ve proposed.** We selected and extensively studied the solutions of the top competitors in the competition, and ultimately found that they employed relatively similar input-output modeling approaches. Therefore, we began our own practical implementation based on this insight.
