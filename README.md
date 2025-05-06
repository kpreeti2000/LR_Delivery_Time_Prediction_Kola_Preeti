# LR_Delivery_Time_Prediction

This project builds a predictive pipeline to estimate order delivery times using real-world dispatch data. We ingested timestamps and transactional fields, engineered features like elapsed minutes, order hour, weekday/weekend flags, and handled outliers. After EDA and correlation analysis, we trained and tuned linear regression models—using recursive feature elimination to find the most impactful predictors (distance, item count, weekend flag)—and evaluated performance with MAE, MSE, R² and residual diagnostics.
