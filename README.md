# Project
Warehouse Process Optimization Using Agile Methodologies
Objective: To enhance order fulfillment speed, reduce errors, and improve overall efficiency.

Solutions Implemented:

Agile Methodologies: Transitioned to Agile with sprint planning, daily stand-ups, and retrospectives to improve flexibility and collaboration.
Lean Principles: I would apply value stream mapping and 5S implementation to eliminate waste and streamline processes.
Data-Driven Decision Making: Used JMP Pro for statistical analysis, control charts, and time series forecasting to monitor and improve processes.
Training and Education: I Would provid Agile and Lean training to team members to ensure a smooth transition and continuous improvement.
Results:

Order Processing Time: Reduced from 5 days to 3.6 days.
Error Rate: Decreased from 4% to 2.3%.
Inventory Accuracy: Increased from 95% to 98%.
Pick and Pack Time: Reduced from 20 minutes to 14 minutes.
Using JMP Pro, I analyzed performance data and visualized the impact of the changes. Below are some insights:

Order Processing Time Trend 

Error Rate Improvement 

Forecasted Inventory Accuracy 

<img width="893" alt="Screenshot 2024-05-21 at 11 18 31 PM" src="https://github.com/Fhemiee/Project/assets/154028690/021a8297-8616-4931-930f-b01fe2890d90">

<img width="893" alt="Screenshot 2024-05-21 at 11 18 34 PM" src="https://github.com/Fhemiee/Project/assets/154028690/9e9e466e-07fe-4fa3-bce2-ba1a654f7658">

<img width="770" alt="Screenshot 2024-05-21 at 11 08 18 PM" src="https://github.com/Fhemiee/Project/assets/154028690/aae36dd5-7d88-44c7-9b61-512c1a55dfed">

<img width="657" alt="Screenshot 2024-05-21 at 11 15 44 PM" src="https://github.com/Fhemiee/Project/assets/154028690/901c3536-ec0a-4723-8a83-eda9887e4dd8">

<img width="699" alt="Screenshot 2024-05-21 at 11 16 06 PM" src="https://github.com/Fhemiee/Project/assets/154028690/6fb8ce1a-fe90-47a3-8ea5-31e42ab0e8cc">

<img width="745" alt="Screenshot 2024-05-21 at 11 16 23 PM" src="https://github.com/Fhemiee/Project/assets/154028690/528d8929-3df2-431b-95d7-1c1f296179bf">

<img width="668" alt="Screenshot 2024-05-21 at 11 16 42 PM" src="https://github.com/Fhemiee/Project/assets/154028690/f8745cb2-a404-4e38-91b3-8585a4ac3d9a">

<img width="510" alt="Screenshot 2024-05-21 at 11 17 00 PM" src="https://github.com/Fhemiee/Project/assets/154028690/617a8f71-f6fe-4e3d-bb71-6c0fb025b315">

<img width="407" alt="Screenshot 2024-05-21 at 11 17 18 PM" src="https://github.com/Fhemiee/Project/assets/154028690/8f0ec452-28f9-4eee-852e-54ef3720c046">

1. Bivariate Fit of Order Processing Time (days) By Week 

Correlation (-0.93955): 
Explanation: Correlation measures the strength and direction of a linear relationship between two variables. A correlation of -0.93955 indicates a strong negative relationship between weeks and order processing time. As the weeks increase, the order processing time decreases significantly. 
The negative correlation of -0.94 shows that as time progresses, the order processing time has decreased significantly, indicating that the process improvements are having a “positive effect." 
Significance Probability (<.0001): 
The p-value indicates the probability that the observed correlation is due to random chance. A very low p-value (<0.0001) means the result is statistically significant and highly unlikely to be due to chance. 
Detail: The p-value is less than 0.0001, which means the reduction in order processing time is statistically significant and not due to random variation. 

2. Bivariate Fit of Error Rate (%) By Week 

Correlation (-0.96504): 
Explanation: A correlation of -0.96504 indicates a very strong negative relationship between week and error rate. As the weeks increase, the error rate decreases significantly. 
The strong negative correlation of -0.97 shows the error rates have consistently decreased over time, demonstrating the effectiveness of our quality improvement measures. 
Significance Probability (<.0001): 
A very low p-value (<0.0001) indicates that the observed reduction in error rate is statistically significant and not due to random chance. 
Detail: With a p-value of less than 0.0001, the decrease in error rate is statistically significant and not just a random fluctuation. 

<img width="1037" alt="Screenshot 2024-05-21 at 11 17 38 PM" src="https://github.com/Fhemiee/Project/assets/154028690/c06eefed-b8dc-4a86-bfc7-a8b255d93e7c">
Control Chart for Order Processing Time 

Explanation: A control chart is used to monitor the stability of a process. It shows the individual order processing times over weeks, with control limits that indicate the expected range of variation. 
Key Points: 
Lower Control Limit (LCL): 3.453337 days 
Upper Control Limit (UCL): 4.234663 days 
Average: 3.844 days 

Detail: The control chart indicates the order processing time is within control limits, showing consistent improvement without unusual variations. The average processing time has dropped to 3.84 days, which is within the expected range. 


<img width="729" alt="Screenshot 2024-05-21 at 11 18 02 PM" src="https://github.com/Fhemiee/Project/assets/154028690/23aff155-eb19-4cce-a4fe-f500d5aaeb79">

<img width="729" alt="Screenshot 2024-05-21 at 11 18 08 PM" src="https://github.com/Fhemiee/Project/assets/154028690/1cdda2bb-8ee4-46aa-827b-a376d7df5004">

Time Series Forecast for Inventory Accuracy 

Model Type (Multiplicative Error, Multiplicative Trend, Damped): 
Explanation: The model accounts for multiplicative errors and trends, with a damping effect to reduce the impact of the trend over time. 
Detail: Using a multiplicative error and trend model with damping to forecast inventory accuracy. This model helps predict future values by accounting for the proportional changes and gradually reducing the trend's influence over time. 
Model Summary: 
AIC (48.98005) and BIC (60.45219): 
Explanation: These criteria help compare different models. Lower values generally indicate a better fit. 
Detail: The AIC and BIC values help to assess the model's fit. Lower values suggest a better model, and these values indicate a good fit for our data. 
Parameter Estimates: 
Alpha, Beta, Phi, Initial Level (I0), Initial Trend (B0): 
Explanation: These parameters define the behavior of the time series model, such as the smoothing factor, trend, and initial conditions. 
Detail: The parameter estimates show the model's specifics. For instance, the alpha value represents the smoothing factor, which influences how much weight recent observations have on the forecast. The initial level and trend parameters set the starting point for the model. 
One-Step-Ahead Forecasting Errors: 
Explanation: This graph shows the differences between the actual and predicted values for each time point. 
Detail: The forecasting errors are small and consistently close to zero, indicating that the model's predictions are accurate.


Detail of the Overall Process 

When explaining the project to a recruiter, focus on the main objectives, the approach you took, and the key results: 

Objective: 
"The goal of the project was to enhance order fulfillment speed, reduce errors, and improve overall efficiency in our warehouse processes." 
Approach: 
I randomly collected weekly data on key metrics like order processing time, error rate, inventory accuracy, and pick and pack time. Using JMP Pro for data analysis, including correlation analysis, control charts, and time series forecasting." 
Key Findings: 
Found a strong negative correlation between weeks and both order processing time (-0.94) and error rate (-0.97), with statistically significant p-values (<0.0001), indicating our process improvements were effective. 
Control charts showed that the processes were stable and under control, with a significant reduction in average order processing time. 
The Time series forecast predicted continued improvement in inventory accuracy, supporting the ongoing efforts to enhance efficiency. 
Results: 
Overall, was able to reduce the average order processing time from 5 days to 3.6 days, decreased error rates from 4% to 2.3%, and improved inventory accuracy from 95% to 98%. These improvements significantly enhanced operational efficiency. 
