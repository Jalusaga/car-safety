# car-safety
> A simple linear regression model for predicting student performace based on multiple variables.

This project explores how well we can predict a car safety using related attributes. We build a simple Random Forest Classifier model and take a look at how accurately it can forecast our target feature.

## 🚀 Project Overview

We load the UCI “Car Evaluation” dataset, preprocess categorical features, then train a Random Forest Classifier model to predict the overall car safeness based on 6 input features.

The goal is to see how accurate our model’s predictions come to the real safety categories.

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository – Car Evaluation Data Set](https://archive.ics.uci.edu/dataset/19/car+evaluation)  
- **File**: `car-data.csv`   
- **Records**: 1728 cars  
- **Columns**: 7 total

## 🔧 Installation

1. **Clone** this repo:  
   ```bash
   git clone https://github.com/jalusaga/car-safety.git
   cd car-safety

2. **Install** dependencies
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn

## 📈 Results

   - Score: 0.9629629629629629

Our Random Forest Classifier shows about 96% accuracy predicting car safety. This showcases the model default effectiveness in simple problems.   

## 🤝 Credits & License

  Data source: UCI ML Repository – Car Evaluation

  Built with ❤️ Alonso Usaga Bonilla

  License: MIT © 2025
