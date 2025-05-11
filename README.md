# 🌩️ stormmind.ch

**Predicting Storm Damage in Switzerland using Machine Learning**

StormMind is a Bachelor's thesis project focused on developing a deep learning system to predict storm-related infrastructure damage in Switzerland. By analyzing historical weather data and damage reports, our system forecasts potential storm damage to support better preparedness and cost reduction.

---

## 📁 Project Structure

The project consists of **three main repositories**:

### 🧠 [`ai`](https://github.com/stormmind-ch/ai)
> The deep learning engine of StormMind

- Time series forecasting models (FNN, LSTM, Transformer)
- Data preprocessing and augmentation
- Training, evaluation, and hyperparameter tuning (via Weights & Biases)
- Dataset handling for historical weather data and storm damage

### 🛠️ [`backend`](https://github.com/stormmind-ch/backend)
> RESTful API and model serving (Java, Spring Boot, DJL)

- Hosts trained models using [Deep Java Library (DJL)](https://djl.ai/)
- Connects frontend with predictions and weather input
- Handles inference, logging, and validation

### 🖥️ [`frontend`](https://github.com/stormmind-ch/frontend)
> Interactive dashboard for users (React.js + Vite.js)

- Map visualization of predicted storm damage
- Upload or input weather forecast data
- Displays model confidence and affected regions
- Currently not published

---

## 🎓 About the Thesis
Extreme weather events cause considerable damage to infrastructure, the economy, and the environment worldwide. Predicting such damage can help to optimize preventive measures and reduce costs. In this project, a neural network is being developed that analyzes historical weather data and damage reports to predict potential storm damage in Switzerland based on new weather forecasts. Using modern machine learning techniques, relevant patterns are recognized in order to train a predictive model. The model is tested for accuracy and optimized to enable reliable predictions.

---

## 🚀 Technologies Used

| Component   | Tech Stack                        |
|------------|-----------------------------------|
| AI / ML     | PyTorch, W&B, NumPy               |
| Backend     | Java, Spring Boot, DJL            |
| Frontend    | React.js, Vite.js                 |
| DevOps      | GitHub Actions, Docker (optional) |

---

## 📊 Live Demo

🚧 *Coming soon: hosted frontend + inference API*

---

## 🤝 Team

This project is part of our Bachelor's thesis at [Zurich University of Applied Sciences].  
Team Members: 
- [Nils Gämperli](https://github.com/Nelson0101?tab=overview&from=2025-05-01&to=2025-05-11)
- [Damian Ueltschi](https://github.com/duke-j)



