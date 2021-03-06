# Reccurent Breast Cancer Prognosis

**Цель данного проекта** - построение алгоритма для прогнозирования развития рецидива у пациентов с подтвержденным раком молочной железы после проведения оперативного лечения. Модель должна возвращать вероятности классов, эта информация должна быть обработана врачом-онкологом, ему же необходимо сделать выводы о дальнейшей тактике лечения. Результаты работы планируется использовать для написания научных статей.
При работе над исследовательским анализом данных, предобработкой данных и написанием результатов и выводов я консультировался с действующим врачом-патоморфологом.

**Описание признаков:**   
`age` - возраст пациентки   
`menopause` - менструальный статус   
`tumor-size` - размер опухоли (мм)   
`inv-nodes` - количество выявленных метастатических лимфатических узлов   
`node-caps` - наличие экстракапсулярного распространения метастаза лимфатического узла   
`deg-malig` - степень злокачественности рака молочной железы (G1-G3)   
`breast` - локализация опухолевого узла (правая или левая молочная железа)   
`breast-quad` - квадрант, в котором расположен опухолевый узел   
`irradiat` - проводилась ли пациентке лучевая терапия (адъювантная или неоадъювантная - не уточняется)   
`Class` - целевой признак   

*Citation Request: This breast cancer domain was obtained from the University Medical Centre, Institute of Oncology, Ljubljana, Yugoslavia. Thanks go to M. Zwitter and M. Soklic for providing the data. Please include this citation if you plan to use this database.*

**To-Do-List:**
- [ ] - Используя shap предоставить визуализацию feature importance для каждой из моделей 
- [ ] - Улучшить предсказания и метрику, используя ансамблевые методы обучения (XGBoost, CatBoost, LightGBM)
- [ ] - Написание выводов и рекомендаций для улучшения прогноза модели
