# 🌾 Crop Productivity Analysis

This project explores the factors influencing agricultural crop yield using data from [Kaggle's Crop Yield Dataset](https://www.kaggle.com/datasets/samuelotiattakorah/agriculture-crop-yield/data). Through a detailed EDA, we investigate how weather, farming practices, and regional conditions affect productivity.

## 🔍 Insights to Explore

🌦️ **Weather Impact**  
How do different weather conditions affect crop yield?

🌡️ **Environmental Factors**  
Study the role of temperature and rainfall on productivity.

🌱 **Agricultural Practices**  
Analyze the effectiveness of fertilizer and irrigation.

📍 **Regional Differences**  
Compare productivity across regions to identify high-yield areas.

## 📈 Key Findings

- **Yield is consistent** across most regions — possibly due to uniform agricultural methods or environmental factors.
- **Rainfall** shows a **strong positive correlation** with yield.
- **Temperature** has minimal impact on productivity.
- **Extremely low yields** in some entries may indicate data quality issues or localized failures.
- **Fertilizer + Irrigation combo** = 🚀 the most effective strategy.
- **Soil type, weather conditions**, and **days to harvest** show weak influence overall.

## 🤖 Regression Modeling

A linear regression (OLS) was used to predict crop yield:

- **Features used**: Fertilizer use, Irrigation
- **R² Score**: 0.327
- **Note**: Rainfall excluded due to multicollinearity, despite high correlation

## 📊 Visualizations

- Correlation heatmaps
- Distribution plots
- Scatter plots for key variables
- Comparative regional bar charts


## ✅ Conclusion

To improve crop productivity, focus on:
- Optimizing **rainfall management**
- Strategic **fertilizer use**
- Efficient **irrigation systems**

---

Feel free to fork or explore this repo if you're into agriculture + data science!



