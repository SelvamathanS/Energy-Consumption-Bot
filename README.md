# Energy Consumption Bot

* A simple web application that predicts energy consumption and provides results through a web interface.
* Energy Consumption Bot is a lightweight web application that predicts energy consumption using a pre-trained machine learning model.
* Users enter energy-related inputs through a simple web interface.

## Features

* **Web UI** to input features and get energy consumption predictions
* **Pretrained model** (`electricity_model.pkl`) and scaler (`scaler.pkl`) included
* Built with Python (Flask) and HTML/CSS templates

## How It Works

1. User opens the web app in a browser
2. Inputs energy-related values on the form
3. The app loads a pretrained model and scaler
4. Predicts energy consumption and displays the result on the UI

## Tech Stack

* **Backend:** Python (Flask)
* **Frontend:** HTML, CSS (in `templates/` and `static/`)
* **Model:** Scikit-learn machine learning model stored as pickle

```

## Notes

* Make sure all required files (`.pkl`, templates) remain in place.
* You can retrain or replace the existing model if needed.
* Add error handling, input validation, and security before production use.

---
