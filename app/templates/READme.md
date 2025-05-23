Car Price Predictor
Веб-приложение на Flask для предсказания:
точной цены автомобиля (регрессия)
категории автомобиля: "Бюджетный" или "Дорогой" (классификация)

Модели машинного обучения обучены с использованием XGBoost и сохранены в формате .pkl.

Структура проекта:
car-price-predictor/
├── app.py
├── models/
│   ├── car_price_classifier.pkl
│   └── car_price_regressor.pkl
├── templates/
│   └── index.html
├── static/
│   └── (стили, изображения и т.д. по желанию)
├── requirements.txt
└── README.md

Используемые технологии:
Python 3.x
Flask
Pandas
scikit-learn
XGBoost
Joblib

Возможности
Классификация: определение, является ли авто дорогим
Регрессия: предсказание точной стоимости автомобиля
Веб-интерфейс с формой ввода

