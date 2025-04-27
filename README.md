# Customer Satisfaction Prediction System

## About
🐍 A machine learning system for predicting customer satisfaction using **ZenML** to orchestrate production-grade ML pipelines with **MLflow** integration. The system handles data preprocessing, model training, automatic deployment, and provides an interactive **Streamlit** dashboard. Supports continuous model improvement and full experiment tracking to help make smarter business decisions.

## Features
- 📊 **Data Processing:** Automated cleaning and feature engineering.
- 🤖 **Model Training:** Build and evaluate multiple ML models.
- 🚀 **Auto-Deployment:** Deploy models into production with minimal manual effort.
- 🌐 **Streamlit Interface:** Simple, user-friendly dashboard for predictions.
- 📈 **Continuous Improvement:** Supports retraining and updating models.
- 📝 **Comprehensive Tracking:** Integrated with MLflow for experiment and model version tracking.

## Tech Stack
- **ZenML** (pipeline orchestration)
- **MLflow** (experiment tracking and model registry)
- **Streamlit** (dashboard interface)
- **Scikit-learn** (model building)
- **Python 3.x**

## Installation
```bash
git clone https://github.com/your-username/customer-satisfaction-prediction.git
cd customer-satisfaction-prediction
pip install -r requirements.txt
```

## How to Run
1. **Initialize ZenML repository:**
    ```bash
    zenml init
    ```
2. **Run the pipeline:**
    ```bash
    python run_pipeline.py
    ```
3. **Start the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

## Project Structure
```
customer-satisfaction-prediction/
├── pipelines/
├── steps/
├── app.py
├── run_pipeline.py
├── README.md
├── requirements.txt
```

## Tracking & Monitoring
- View experiments and model metrics in the **MLflow UI**.
- Monitor deployed models for performance drifts.

## Contribution
Pull requests are welcome! Feel free to open an issue if you want to contribute new features or fix bugs.

## License
This project is open-source under the MIT License.

---

*Built with ❤️ to enable smarter customer experience decisions.*

