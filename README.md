# Russian Toxic Text Detector

## Project Overview

This repository contains my inaugural machine learning project, which focuses on building a neural network to classify Russian text into one or more of the following categories: normal, insult, obscenity, and threat. The project leverages the bert-multilingual-cased model for its text classification tasks.

## Dataset

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/alexandersemiletov/toxic-russian-comments) and is licensed under the CC BY-NC-SA 4.0 license. This dataset consists of various comments in Russian, each labeled with one or more toxicity categories.

## Model

The core of the project is based on the bert-multilingual-cased model, which is fine-tuned to accurately classify the input text into the specified categories.

You can download the pre-trained models from [Yandex Disk](https://disk.yandex.ru/d/YfJ8sxZOGeHr4Q). Two types of models are available:
1. Model trained for 1 epoch.
2. Model trained for 3 epochs.

## Usage

To utilize this model, input text in Russian and the neural network will output one or more labels indicating the nature of the text (normal, insult, obscenity, threat).

## License

This project is licensed under the MIT License.

---

# Детектор Токсичного Текста на Русском Языке

## Обзор Проекта

Этот репозиторий содержит мой первый проект в области машинного обучения, который направлен на создание нейронной сети для классификации текста на русском языке по одной или нескольким из следующих категорий: норма, оскорбление, непристойность, угроза. Проект использует модель bert-multilingual-cased для задач классификации текста.

## Датасет

Датасет, используемый в этом проекте, взят с [Kaggle](https://www.kaggle.com/datasets/alexandersemiletov/toxic-russian-comments) и лицензирован под лицензией CC BY-NC-SA 4.0. Этот датасет состоит из различных комментариев на русском языке, каждый из которых помечен одной или несколькими категориями токсичности.

## Модель

В основе проекта лежит модель bert-multilingual-cased, которая была дообучена для точной классификации входного текста по указанным категориям.

Вы можете скачать предобученные модели с [Яндекс Диска](https://disk.yandex.ru/d/YfJ8sxZOGeHr4Q). Доступны два типа моделей:
1. Модель, обученная за 1 эпоху.
2. Модель, обученная за 3 эпохи.

## Использование

Чтобы использовать эту модель, введите текст на русском языке, и нейронная сеть выдаст одну или несколько меток, указывающих на характер текста (норма, оскорбление или нецензурная брань, вульгарность, грозное преднамерение).

## Лицензия

Этот проект лицензирован под лицензией MIT.
