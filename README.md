# Forecasting Fashion Color Trends Using Social Media

This project uses machine learning and Pinterest image data to forecast fashion color trends. It was developed as part of an MSc Data Science dissertation at Middlesex University.

## 📌 Objective
To identify and predict upcoming fashion color trends by extracting dominant colors from Pinterest fashion posts and modeling their popularity using Random Forest regression.

## 🔍 Dataset
- Pinterest Fashion Dataset (1,000+ images)
- Features: Product category, price, click rate, image URLs, ratings

## 🧠 Methodology
- Extracted dominant colors using KMeans clustering (OpenCV + Pillow)
- Feature engineering with product details and engagement metrics
- Model: Random Forest Regression (MSE: 1155.06, R²: 0.78)

## 🧪 Tools Used
Python, Pandas, scikit-learn, KMeans, Random Forest, Seaborn, Matplotlib

## 📊 Results
- Top colors: Lavender, Mint Green, Coral
- Most predictive features: Dominant color, click rate, product category

## 📁 Folder Structure
- /data → Dataset files
- /notebook → Jupyter notebook (.ipynb)
- /visuals → Color palette and output images
- README.md → This file

## 📈 Future Work
- Expand dataset (50K+ images, include Instagram/TikTok)
- Add LSTM model for seasonality
- Deploy real-time trend dashboard

---
🎓 Author: Amna (M00993181) | Middlesex University MSc Data Science Dissertation
