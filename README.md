# Body_Temperature_Detection
Link to DataSet = https://drive.google.com/drive/folders/1TDey84SnvCukwnsebZ-1hmq2KG6PfLTu 
Body_Temperature_Detection using Regression 
The dataset comprises de-identified information from a study evaluating standardized deployment practices in measuring Elevated Body Temperature (EBT) using Infrared Thermographs (IRTs). With over a thousand subjects, oral temperatures and facial thermal images from two IRTs were collected. The dataset includes 33 features encompassing gender, age, ethnicity, ambient temperature, humidity, distance, and various facial temperature readings. The goal is regression to predict oral temperature utilizing both environmental data and thermal image readings.

Exploratory Data Analysis (EDA): Data cleaning involves handling missing values and ensuring data integrity. Feature extraction may be necessary to derive additional insights. Visualizations via libraries like matplotlib, seaborn, and plotly aid in understanding feature distributions, relationships, and patterns.

Linear Regression Modeling: Implementation of a custom linear regressor using gradient descent is required, excluding any built-in functions. Performance evaluation involves metrics like R-squared error and Root Mean Squared Error (RMSE). Comparison with a pseudoinverse-based regressor allows assessing the efficacy of the custom model. Various hyperparameters such as batch size and learning rate can be tuned for optimization.

Training Process Experimentation: Plotting the loss against the number of iterations for the gradient-descent-based linear regressor elucidates the learning process. Injecting noise into inputs and parameters aids in understanding the model's robustness and sensitivity to perturbations. This exercise provides insights into overfitting, underfitting, and generalization capabilities.

Use-case Suggestion: Understanding noise effects on model performance is crucial in applications like predictive maintenance systems. Predictive maintenance relies on accurate predictions for scheduling maintenance tasks efficiently. By comprehending noise impact, more robust predictive maintenance models can be developed, enhancing equipment reliability and reducing downtime.
