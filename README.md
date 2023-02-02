# project_predict_leave_client
 
*В проекте используются модели Логистической регрессии, Дерева решений и Случайного леса, методы баланса классов - самообучение (class_weight=balanced) и ownsampling*

**ЗАДАЧИ ПРОЕКТА**

1. **Главная задача**
 - Спрогнозировать, уйдёт ли клиент из банка в ближайшее время. 
 - Построить модель с предельно большим значением F1-меры - 0.59 и выше. Дополнительно измерить AUC-ROC, сравнивая её значение с F1-мерой.
 
2.
 - Обучить модель вначале без учёта дисбаланса классов, затем учитывая дисбаланс.

_В проекте используются библиотеки pandas, numpy, sklearn_
