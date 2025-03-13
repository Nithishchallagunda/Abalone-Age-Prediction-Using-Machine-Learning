# 🐌 Abalone Age Prediction using Random Forest

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev/)

An interactive web application that predicts the age of abalones using Random Forest Regression. This project demonstrates the practical application of machine learning in marine biology research.

![Abalone Shell](https://images.unsplash.com/photo-1570368294249-55d0a6b6c82c?auto=format&fit=crop&q=80)

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

- **Frontend**: React + TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
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

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com

Project Link: [https://github.com/yourusername/abalone-age-prediction](https://github.com/yourusername/abalone-age-prediction)

## 🙏 Acknowledgments

- [Abalone Dataset](https://archive.ics.uci.edu/ml/datasets/abalone) from UCI Machine Learning Repository
- [scikit-learn](https://scikit-learn.org/) for the Random Forest implementation
- [React](https://reactjs.org/) for the frontend framework
- [Tailwind CSS](https://tailwindcss.com/) for styling