Предобработка и влияние на модель.

Для данного задания была использована модель с алгоритмом XGBoost с набором данных wine.
Предобработка проводилась нормализацией и стандартизацией, оценивалась модель с помощью таких метрик как:
- Precision (точность модели при определении класса Positive), 
- Recall (полнота), 
- Accuracy (общая точность предсказания модели по всем классам),
- RMSE (среднеквадратичная ошибка).

Без использования предобработки:

![image](https://user-images.githubusercontent.com/39708272/159753574-311bd855-86f7-49f7-9c49-a9d5a672e5e9.png)


![image](https://user-images.githubusercontent.com/39708272/159753710-5a2b3344-22b5-4fac-804a-f4581d8f568c.png)

С использованием стандартизации:

![image](https://user-images.githubusercontent.com/39708272/159753974-5d30acf9-eede-49eb-b372-a9e13c7d46fd.png)

![image](https://user-images.githubusercontent.com/39708272/159753985-e83f37ac-282e-497c-9244-539da2729e2f.png)

С использованием нормализации:

![image](https://user-images.githubusercontent.com/39708272/159754121-1d2332f2-a2a9-4d27-9f91-bec33dd25dc2.png)

![image](https://user-images.githubusercontent.com/39708272/159754178-c8c0692c-eff4-477d-add6-f6503d489be7.png)

Как видно из результатов, использование предобработки не влияет на результат, что показывает, то что алгоритм не чувствителен к данным.
