# Обучение с учителем

Задача заключалась в прогнозировании покупательской активности клиентов на основе истории их взаимодействия с интернет-магазином. 

- Были загружены и объединены данные об истории покупок, сессиях на сайте и других факторах в 4 датафрейма. Проведена их предобработка: чистка данных, приведение типов, стандартизация названий.

- Для поиска оптимальной модели был создан пайплайн с предобработкой данных и встроенными классификаторами. Методом рандомизированного поиска были найдены лучшие параметры.

- Лучшей моделью оказался алгоритм KNN с точностью 0.997 по AUC ROC. 

- Анализ важности признаков методом SHAP показал наиболее информативные признаки. 

- Были выделены сегменты с высокой и низкой активностью. Исследован сегмент с наименьшей активностью и прибылью. Рекомендованы мероприятия по его стимулированию.

Таким образом, реализован комплексный подход к анализу данных, построению модели и выявлению целевого сегмента для повышения лояльности и прибыли.