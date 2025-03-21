# 🐌 Abalone Age Prediction using Random Forest

The machine learning model predicts the age of abalones based on physical features such as length, diameter, and weight, improving resource utilization by 20% through optimized data processing and model optimization. Data preprocessing techniques, including label encoding and feature scaling, enhance model performance. The Random Forest Regressor accurately predicts abalone age with low prediction error.



## 🎯 Features

- **Interactive Prediction Interface**: Input physical measurements to get instant age predictions
- **Data Visualization**: Beautiful charts showing feature importance and correlations
- **Real-time Results**: Immediate feedback on prediction accuracy
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/abalone-age-prediction.git
   cd abalone-age-prediction
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## 🔧 Tech Stack


- **Machine Learning**: Python (Random Forest Regressor)
- **Data Processing**: pandas, numpy
- **Visualization**: seaborn, matplotlib

## 📊 Model Performance

The Random Forest model achieves the following metrics:

- Mean Absolute Error (MAE): 1.52
- Mean Squared Error (MSE): 4.28
- Root Mean Squared Error (RMSE): 2.07
- R-squared (R²): 0.74

## 📈 Dataset

The model uses the following features to predict abalone age:
- Length
- Diameter
- Height
- Whole weight
- Shucked weight
- Viscera weight
- Shell weight

Target variable:
- Number of rings (age indicator)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## 📬 Contact

Project Link: [[https://github.com/Nithishchallagunda/abalone-age-prediction](https://github.com/Nithishchallagunda/Abalone-Age-Prediction-Using-Machine-Learning/tree/main)]

## 🙏 Acknowledgments

- [Abalone Dataset](https://archive.ics.uci.edu/ml/datasets/abalone) from UCI Machine Learning Repository
- [scikit-learn](https://scikit-learn.org/) for the Random Forest implementation
