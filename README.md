# Задача
Определить стоимость автомобиля

Цель: построить модель, которая умеет определять стоимость автомобиля на основании тех.характеристик, комплектации и цен других автомобилей.

# Выводы
Наилучшей моделью стала LGBMRegressor с OHE, которая на финальном тестировании показала RMSE 1302, несмотря на требуемое большее время на обучение и предсказание. То есть если есть время, то лучше пользоваться данной моделью.

# Стек технологий
Pandas, Python, LightGBM

# Статус проекта
Завершен
