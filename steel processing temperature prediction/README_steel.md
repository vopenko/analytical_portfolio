# Модель предсказания оптимальной температуры обработки стали

Цель исследования - построение модели, которая предскажет оптимальную температуру обработки стали с заданным MAE <= 6

__Форма отчета:__  ноутбук .ipynb 

## Стек/используемые библиотеки
- python
- sklearn (models, metrics, cross validation, standard scaler)
- lightgbm
- pandas
- matplotlib
- seaborn
- модели предсказания: LinearRegression, DecisionTreeRegressor, import RandomForestRegressor, lightGBM, KNeighborsRegressor,
    GradientBoostingRegressor, KNeighborsRegressor, ExtraTreesRegressor, RandomForestRegressor, DecisionTreeRegressor,
    LinearRegression, Lasso, Ridge

## Источник:
csv-файлы, содержащие: данные об электродах, данные о подаче сыпучих материалов (объём, время), данные о продувке сплава газом, результаты измерения температуры,
данные о проволочных материалах (объём, время).

## Разделы исследования (оглавление):

1. Краткое описание проекта

2. Обзор и предобработка данных

3. Исследовательский анализ данных

4. Построение, выбор и улучшение модели предсказания оптимальной температуры
    
    4.1. Подготовка данных
    
    4.2. Выбор модели
   
    4.3. Изучение features_importances
    
    4.4. Подбор параметров лучшей модели с GridSearchCv
   
    4.5. Сравнение с константной моделью

5.  Выводы 
