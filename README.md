# 🤖 Watsonx AutoAI Streamlit App

This project demonstrates how to deploy an **IBM Watsonx AutoAI model** and consume it using a **Streamlit app**. The model is trained using Watsonx Studio and deployed via an online endpoint. The Streamlit frontend collects user input, sends it to the model, and displays real-time predictions.

---

## 📌 Features

- Trains an ML model using **AutoAI on IBM Watsonx Studio**
- Deploys the best pipeline as an **Online REST API**
- Builds a user interface using **Streamlit**
- Sends input to AutoAI via IBM Cloud API and displays predictions
- Optional: Hosted on **Streamlit Cloud**

---

## 🧰 Tech Stack

- [IBM Watsonx Studio](https://dataplatform.cloud.ibm.com/)
- Streamlit
- Python
- IBM Cloud IAM Authentication
- GitHub (for version control and cloud deployment)

---
```toml

DEPLOYMENT_URL = "https://au-syd.ml.cloud.ibm.com/ml/v4/deployments/2be32b0b-25bc-440f-9dff-dcfec35506ed/predictions?version=2021-05-01"
```

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/autoai-streamlit-app.git
cd autoai-streamlit-app
