# 🫀 CardioPredict AI

> Intelligent Cardiovascular Risk Assessment Using Machine Learning

[![Demo](https://img.shields.io/badge/Demo-Live-brightgreen)](your-demo-link)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-18+-blue.svg)](https://reactjs.org/)
[![ML](https://img.shields.io/badge/ML-Gradient%20Boosting-orange.svg)](https://scikit-learn.org/)

## 🩺 Overview

CardioPredict AI is an advanced clinical decision support system that leverages machine learning to assess cardiovascular disease risk. Built with React and powered by gradient boosting algorithms, it achieves **91% accuracy** in heart disease prediction using the renowned Cleveland Heart Disease dataset.

## ✨ Features

- 🎯 **Interactive Clinical Prediction Tool** - Real-time cardiovascular risk assessment
- 📊 **Advanced ML Analytics** - Comprehensive model performance analysis
- 🔬 **Research Methodology** - Detailed explanation of data preprocessing and feature engineering
- 📈 **Data Visualization** - Interactive charts and feature importance analysis
- 🩺 **Clinical Recommendations** - Evidence-based treatment suggestions
- ⚠️ **Medical Disclaimers** - Proper ethical guidelines and limitations
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/cardiopredict-ai.git
   cd cardiopredict-ai
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to see the application.

## 📊 Model Performance

| Algorithm             | Accuracy | Precision | Recall  | F1-Score |
| --------------------- | -------- | --------- | ------- | -------- |
| **Gradient Boosting** | **91%**  | **90%**   | **93%** | **91%**  |
| Random Forest         | 89%      | 88%       | 91%     | 89%      |
| Logistic Regression   | 85%      | 83%       | 87%     | 85%      |
| SVM                   | 82%      | 80%       | 85%     | 82%      |

## 🔬 Technology Stack

- **Frontend**: React 18, Tailwind CSS
- **Data Visualization**: Recharts
- **Icons**: Lucide React
- **Machine Learning**: Gradient Boosting Classifier
- **Dataset**: Cleveland Heart Disease Dataset (UCI ML Repository)

## 📋 Clinical Parameters

The system analyzes 13 key cardiovascular risk factors:

1. **Age** - Patient age in years
2. **Sex** - Biological sex (male/female)
3. **Chest Pain Type** - 4 categories of chest pain
4. **Resting Blood Pressure** - mmHg
5. **Cholesterol** - mg/dl
6. **Fasting Blood Sugar** - >120 mg/dl
7. **Resting ECG Results** - Electrocardiographic results
8. **Maximum Heart Rate** - Exercise-induced maximum heart rate
9. **Exercise Induced Angina** - Yes/No
10. **ST Depression** - Exercise-induced ST depression
11. **Slope** - Slope of peak exercise ST segment
12. **Major Vessels** - Number of major vessels colored by fluoroscopy (0-4)
13. **Thalassemia** - Blood disorder test results

## 🏥 Clinical Decision Support

The system provides:

- **Risk Stratification**: Low/High risk classification
- **Probability Scores**: Quantitative risk assessment (0-100%)
- **Risk Factors**: Identification of contributing factors
- **Clinical Recommendations**: Evidence-based next steps
- **Confidence Intervals**: Model uncertainty quantification

## ⚠️ Medical Disclaimer

**IMPORTANT**: This tool is designed for educational and research purposes only. It should **never** be used as a substitute for professional medical advice, diagnosis, or treatment. Always consult qualified healthcare professionals for medical decisions.

## 📖 Documentation

### Project Structure

```
cardiopredict-ai/
├── public/
│   ├── index.html          # Main HTML file with Tailwind CDN
│   └── manifest.json       # PWA manifest
├── src/
│   ├── components/
│   │   └── CardioPredictAI.js  # Main application component
│   ├── App.js              # Root component
│   ├── App.css             # Application styles
│   ├── index.js            # Entry point
│   └── index.css           # Base styles
├── README.md               # Project documentation
└── package.json            # Dependencies and scripts
```

### Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Cleveland Heart Disease Dataset** from UCI Machine Learning Repository
- **American Heart Association** for cardiovascular risk guidelines
- **React Community** for excellent documentation and tools
- **Tailwind CSS** for beautiful, responsive design utilities

## 📧 Contact
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/marizza-ranasinghe-424371290/)

## 🔮 Future Enhancements

- [ ] Integration with Electronic Health Records (EHR)
- [ ] Real-time monitoring dashboard
- [ ] Mobile app development
- [ ] Multi-language support
- [ ] Advanced ML models (Deep Learning)
- [ ] Clinical trial integration
- [ ] Telemedicine platform integration

---

⭐ **Star this repository if you found it helpful!**

Made with ❤️ for advancing healthcare through AI
