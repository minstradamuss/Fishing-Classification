# Fishing-Classification

Dataset доступен по ссылке: https://drive.google.com/file/d/1f_ys3L2Y9cIi-IN0v314H656DOwYbCu8/view?usp=sharing

Телеграм для связи: @mariialoskutova

Цели:
1) Реализация модели классификации - обернуть ее в tflite
Задачи в рамках цели: 
- обучаем с точность > 0.99, tflite-формат и вес файла модели < 20Мб.
- взять несколько архитектур: современную архитектуру и легковесные для сравнения (будем сравнивать по метрикам);
- обучаем модель;
- скорим набор данных;
- ранжируем негативных кандидатов (не фишинг) по убаванию скора модели. Смотрим на скрин, пытаемся понять, почему считает фишингом негатив (или не фишингом позитив).
- дебажим датасет.

2) GPT для оценки фишинга:
- найти одну или несколько GPT для анализа;
- реализация промта (инструкции) для оценки кандидатов;
- модель отвечает скором уверенности в кандидате;
- ранжируем негативных кандидатов (не фишинг) по убаванию скора модели. Смотрим на скрин, пытаемся понять, почему считает фишингом негатив (или не фишингом позитив).
Оцениваем результаты.
