## Прогноз количества такси в зависимости от времени суток
## Предсказание временного ряда
На основании исторических данных о заказах такси в аэропортах спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.

Задача: построить модель такого предсказания.

Цель: значение метрики RMSE на тестовой выборке должно быть не больше 48.
## Какой стек использовался?
pandas

numpy

matplotlib

statsmodels

sklearn

catboost
## Какие модели сравнивались?

LinearRegression

RandomForestRegressor

CatBoostRegressor

## Итог
Проведен анализ данных, среди данных выделены признаки и ключевой признак, опробовано несколько моделей, выбрана наиболее оптимальная.
