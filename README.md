# Анализ тональности отзывов о телефонах

Инструкция по запуску:

Сохранить папку на компьютер

Для работы необходима библиотека Flask:
$ pip install flask

Для запуска демо:
1. Введите в командную строку
$ python run_me.py

2. Откройте в браузере страницу:
http://127.0.0.1:5000/

Что еще в этой папке:

model.ipynb - ноутбук с обучением модели
model.pickle - сохраненная обученная модель https://yadi.sk/d/W-v2GYZ9xdG_tg
reviews.txt - обучающая выборка
sentiment_analysis.py - модуль, аналогичный sentiment_analysis.ipynb с сответствующими функциями парсинга, обучения модели и предсказывания по новым данным
test.ipynb - ноутбук для проверки запуска работы модели по новым данным с использованием модуля sentiment_analysis.py# phone_sentiment_analysis
