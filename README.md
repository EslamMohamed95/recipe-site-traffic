# Tasty Bytes Recipe Traffic Prediction
## Explore Problem
Tasty Bytes was founded in 2020 amidst the Covid Pandemic, providing inspiration and assistance to people in finding creative ways to cook with limited supplies at home. Over the years, it has evolved into a full-fledged business, offering a monthly subscription-based meal plan to ensure customers and their families maintain a healthy, balanced diet within their budget.

Currently, Tasty Bytes selects a favorite recipe from a collection and prominently displays it on the homepage. They have observed that featuring a popular recipe boosts website traffic by up to 40%, leading to a higher number of subscriptions. Predicting which recipes will attract high traffic is crucial to the company's success.

#### Our Goals:

Predict which recipes will lead to high traffic.
Achieve an 80% correct prediction rate for high traffic recipes.
Data Validation and Cleaning
During data preprocessing, we carefully validated and cleaned each column in the dataset. We ensured that all data entries were consistent, missing values were handled appropriately, and any outliers or anomalies were addressed.

### Exploratory Analysis
To answer Tasty Bytes' questions, we performed exploratory analysis on the dataset. We utilized various graphical representations to gain insights into the data, including:

Two different types of graphics showing single variables only.
At least one graphic showing the relationship between two or more variables.
Our findings from the exploratory analysis were insightful and guided the model development process.

### Model Development
We framed this problem as a classification task. Our aim was to predict whether a recipe would lead to high traffic (1) or not (0). For model development, we followed the following steps:

Fitting a Baseline Model: We established a baseline model using simple algorithms to have a benchmark for comparison.

Fitting a Comparison Model: To improve performance, we experimented with more advanced machine learning algorithms, optimizing hyperparameters to achieve better accuracy.

Model Evaluation: We evaluated the performance of both models using appropriate evaluation metrics, ensuring a comprehensive understanding of their strengths and weaknesses.

### Model Comparison and Business Metric
We compared the performance of the baseline and comparison models. Based on the evaluation metrics, we identified the model with the highest accuracy for predicting high traffic recipes.

For the business to monitor its recipe traffic prediction, we propose using the accuracy metric, which indicates the percentage of correct predictions made by the model. Tasty Bytes should strive to achieve an accuracy of 80% or higher to maximize website traffic and, subsequently, subscription numbers.

### Recommendations
Based on our analysis, we recommend the following actions for Tasty Bytes:

Utilize the comparison model: The comparison model demonstrated higher accuracy in predicting high traffic recipes. Implementing this model will lead to better selections for the homepage, increasing website traffic and subscriptions.

Regularly monitor accuracy: Continuously track the model's accuracy to ensure it remains above the 80% threshold. If accuracy drops, investigate and fine-tune the model to maintain optimal performance.

Collect additional data: Consider collecting more data to enhance the model's predictive capabilities. Additional features, such as recipe attributes and customer feedback, may provide valuable insights.

A/B testing: Implement A/B testing to further optimize recipe selections for the homepage. Experiment with different popular recipes to identify those that resonate the most with visitors.

By implementing these recommendations, Tasty Bytes can improve the effectiveness of its homepage recipe selections, attract more website visitors, and increase subscription rates.
