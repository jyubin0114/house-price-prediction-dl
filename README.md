# House Price Prediction Using MLP

### Overview
This project develops predictive models to estimate housing prices using machine learning and deep learning approaches. The goal is to improve pricing accuracy for real estate applications (e.g., Zillow iBuyer) and support data-driven decision-making.

### Methods
We implemented and compared:
- Linear Regression (baseline model)
- Multilayer Perceptron (MLP)

The MLP model includes multiple hidden layers with ReLU activation and was trained using stochastic gradient descent (SGD) with Mean Squared Error (MSE) loss. Model performance was evaluated using Median Error Rate (MER). :contentReference[oaicite:0]{index=0}

We further experimented with:
- Deeper architectures
- L2 regularization
- Dropout
- Early stopping

### Key Findings
- MLP significantly outperformed linear regression, achieving lower prediction error and better generalization. :contentReference[oaicite:1]{index=1}  
- Increasing model depth did not significantly improve performance, suggesting the dataset did not require highly complex architectures. :contentReference[oaicite:2]{index=2}  
- Regularization and dropout improved model stability and prevented overfitting. :contentReference[oaicite:3]{index=3}  
- The final model achieved consistent performance with validation error around 0.09–0.10. :contentReference[oaicite:4]{index=4}  

### Business Insights
- The model slightly overestimates housing prices (~7% bias), which may lead to overpricing risks. :contentReference[oaicite:5]{index=5}  
- Actual profit margins (~4–5%) were significantly lower than the target (12%) due to prediction bias. :contentReference[oaicite:6]{index=6}  
- Model stability and generalization are critical for real-world deployment in dynamic housing markets.

### Dataset
Housing price dataset (Kaggle / Zillow-style data)
