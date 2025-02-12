# Insurance Premium Prediction System

## Overview

The **Insurance Premium Prediction System** is a machine learning-based project designed to predict insurance premiums based on various customer attributes. This system utilizes regression models to analyze input data and provide accurate premium cost estimations.

## Features

- **Predicts Insurance Premiums**: Uses a trained machine learning model to estimate premium costs.
- **Web-Based Interface**: Users can input their details via a user-friendly UI.
- **Data-Driven Insights**: Helps insurance providers assess customer risk factors.
- **Scalable Architecture**: Can be extended to include additional factors for prediction.
- **Easy Deployment**: Built using Flask for lightweight and efficient deployment.

## Project Structure

```
├── data/                   # Dataset used for training and testing
├── notebooks/              # Jupyter notebooks for data analysis and model training
├── models/                 # Trained models
├── static/                 # Static assets for the web app
├── templates/              # HTML templates for the web interface
├── app.py                  # Main Flask application
├── requirements.txt        # Dependencies for the project
└── README.md               # Project documentation
```

## Installation

### Prerequisites
Ensure you have the following installed:
- Python (>= 3.8)
- Flask
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for data visualization)

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/nitssa/InsurancePremium-Prediction-System.git
   cd InsurancePremium-Prediction-System
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start the Flask application:
   ```bash
   python app.py
   ```
5. Open your browser and visit `http://127.0.0.1:5000/` to use the application.

## Usage

1. Enter customer details in the web form.
2. Click the "Predict" button.
3. View the estimated insurance premium cost.

## Model Details

- The prediction model is built using **Scikit-learn** and trained on historical insurance data.
- Uses regression techniques to determine premium costs based on user input.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them.
4. Push to your branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions or support, contact Me!
