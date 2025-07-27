# Прогнозирование цен на дома (House Prices)

Проект решает задачу регрессии: предсказание логарифма цены продажи жилья по данным Kaggle House Prices.

## Данные  
- [🏡 House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)


## Предобработка  
- Заполнение пропусков в категориальных признаках (`None`/`No`)  
- Преобразование числовых и категориальных признаков (mapping + one‑hot)  
- Масштабирование числовых признаков (StandardScaler)

## Модели  
- Линейная регрессия (LinearRegression)  
- Гребневая регрессия (RidgeCV, CV=10)  
- Lasso (LassoCV, CV=10)  
- (опционально) ElasticNet, XGBRegressor  

## Оценка  
- Кросс‑валидация 10‑fold, метрика RMSE = 0.13

