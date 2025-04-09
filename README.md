# Heart Risk Predictor 

This is the backend of a heart disease risk prediction application.  
It is built with **FastAPI** and uses a **pre-trained logistic regression model** (`logistic_model.pkl`) to make predictions based on user health data.
##  Features

-  Machine Learning-powered logistic regression model
-  Fast and lightweight REST API built with FastAPI
-  JSON input for prediction
-  Fully compatible with a React frontend
-  Model trained using [heart.csv](./heart.csv)

##  Installation

> Requires Python 3.8+

```bash
# Clone the repository
git clone https://github.com/yourusername/heart-risk-predictor.git
```
```bash
cd heart-risk-predictor
```
Run the API Server
```bash
uvicorn main:app --reload --port 8002
```
Open in browser: http://localhost:8002/docs (Swagger UI)
