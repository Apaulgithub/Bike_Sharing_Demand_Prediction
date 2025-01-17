# Bike Sharing Demand Prediction - Regression

**AlmaBetter Verified Project** - [**Credentials**](https://certificates.almabetter.com/en/verify/41359872655923)

![MasterHead](https://sophiesu.net/wp-content/uploads/2021/01/Bike-Sharing-Demand-1194x501.jpg)

<font size="1">Image Courtesy: https://sophiesu.net/wp-content/uploads/2021/01/Bike-Sharing-Demand-1194x501.jpg</font>

Click on the following link to checkout the video presentation and the colab file.
- [Colab](https://colab.research.google.com/drive/1RanEXeLm1goP8qva3cOMCIkeOqkb9vMQ?usp=sharing)
- [Video](https://drive.google.com/file/d/14owF1K6Yc-36-YZRDL1kluYbLzfNuoCr/view?usp=sharing)


---

## Problem Statement

Currently Rental bikes are introduced in many urban cities. The business problem is to ensure a stable supply of rental bikes in urban cities by predicting the demand for bikes at each hour. By providing a stable supply of rental bikes, the system can enhance mobility comfort for the public and reduce waiting time, leading to greater customer satisfaction.

To address this problem, i need to develop a predictive model that takes into account various factors that may influence demand, such as time of day, seasonality, weather conditions, and holidays. By accurately predicting demand, the bike sharing system operators can ensure that there is an adequate supply of bikes available at all times, which can improve the user experience and increase usage of the bike sharing system. This can have a positive impact on the sustainability of urban transportation, as it can reduce congestion, air pollution, and greenhouse gas emissions.

---

## Project Summary

Bike Seoul is a bike sharing service in the city of Seoul, South Korea. It is part of the city's efforts to promote sustainable transportation and reduce traffic congestion. The service allows residents and visitors to rent bicycles at various stations across the city and return them to any other station, providing a convenient and eco-friendly mode of transportation. In recent years, the demand for bike rentals in Seoul has increased, leading to the need for a more efficient and effective way to manage the bike sharing operations. Accurately predicting bike demand is crucial for optimizing fleet management, ensuring the availability of bikes at high-demand locations, and reducing waste and costs.

The main objective of this project is to develop a machine learning model that can accurately predict the demand for bike rentals in Seoul, South Korea, based on historical data and various relevant factors such as weather conditions, time of day, and public holidays. In this project we have used regression analysis techniques to model the bike demand data. The model trained on a large dataset of past bike rental information, along with relevant weather and time data. The model then be tested and evaluated using metrics such as mean squared error and r-squared values. The actual data is from the Seoul city government's open data portal, and this dataset is also available on Kaggle.

So, our main goal was to achieve an accuracy of at least 85% in the bike demand predictions, which would help the city's bike sharing service providers plan their fleet operations more effectively and respond to demand changes in real-time. We have performed lots of regression algorithms like linear regression, random forest, decision tree, gradient boosting , Xtreme gradient boosting, also we tried to do hyperparameter tuning and cross validation to improve the accuracy of the model. And finally we have decided to select Xtreme gradient boosting algorithm because it gave us high accuracy around 97% and 92% on train and test data respectively.

This project not only provided valuable insights into bike demand patterns in Seoul but also demonstrated the practical applications of machine learning in addressing real-world problems. The findings could potentially be extended to other cities with similar bike sharing systems, leading to improved services for bike users and more sustainable transportation systems.

---

## Conclusion

The project successfully demonstrated the feasibility of using machine learning techniques to predict bike demand in Seoul.

Some of the key points are:-

- High demand in the morning and evening.
- Less Demand in the winter season.
- Highest demand in june.
- Found multicollinearity between temperature and dew point temperature.
- Perform linear regression, decision tree, random forest, gradient boosting, Extreme gradient boosting. & got highest accuracy i.e 97% on train and 92% on test on Xtreme gradient boosting.
- There is no use of removing outliers, it affects negatively on model performance.

Overall, the project highlights the potential of machine learning in solving real-world problems and provides a roadmap for future research in this area. The findings of this project can be extended to other cities with similar bike sharing systems, leading to more effective and efficient bike sharing operations, and better outcomes for all stakeholders.

---

## Author

- [Arindam Paul](https://www.linkedin.com/in/arindam-paul-19a085187/)
