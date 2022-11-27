# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #5 выполнил:
- Просеков Михаил Павлович
- НМТ-210509
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Научиться интегрировать экономическую систему в Unity и обучить ей пользоваться Ml Agent.

## Задание 1
### Интегрировать экономическую систему в проект Unity и обучить Ml Agent.
Открываем проект в Unity
![image](https://user-images.githubusercontent.com/113620568/204133032-b9c131a5-e3fa-4c2f-a5c4-8cee931ddb2f.png)
Устанавливаем нужные библиотеки и запускаем проект
![image](https://user-images.githubusercontent.com/113620568/204134160-d23ebfec-a636-4113-abf6-4ac592a4593d.png)
![image](https://user-images.githubusercontent.com/113620568/204134173-05a3eba3-935b-424f-aaf1-4d2d0a610b9b.png)
![image](https://user-images.githubusercontent.com/113620568/204134180-38677e69-a48e-42c3-9d33-1a718ded7d84.png)
![image](https://user-images.githubusercontent.com/113620568/204134188-0a2abf01-8994-40d9-9760-9cde30bb8ef5.png)




## Задание 2
### Измените параметры файла. yaml-агента и определить какие параметры и как влияют на обучение модели
Устанавливаем все нужные библиотеки для работы TensorBoard.
![image](https://user-images.githubusercontent.com/113620568/204134376-feceaab2-8fba-455b-b108-4824e3ff7176.png)
![image](https://user-images.githubusercontent.com/113620568/204134407-0b994403-5e41-42a2-ba9f-d443785abd08.png)
Графики агента без изменений
![image](https://user-images.githubusercontent.com/113620568/204134438-ad425d03-4152-4bd8-94fb-99e7f97e41d1.png)
Меняю параметр num_layers с 2 до 4
![image](https://user-images.githubusercontent.com/113620568/204134969-7d0fb3fa-e17a-4a63-be60-3180db093eee.png)
Меняю параметр batch_size с 10 до 20
![image](https://user-images.githubusercontent.com/113620568/204135097-9a498d6c-8dea-4fbf-919a-6e09bff13f4d.png)
Меняю параметр epsilon с 0,2 до 0,5
![image](https://user-images.githubusercontent.com/113620568/204135193-c019aa55-c09c-42b0-a5ad-46efe9d602c5.png)
Меняю параметр lambd с 0,99 до 0,85
![image](https://user-images.githubusercontent.com/113620568/204135302-d9943f3f-6e8f-4086-b6ba-32112b6ed9d1.png)


## Выводы

В ходе выполнения данной лабораторной работы я научился интегрировать экономическую систему в Unity и обучать с ней работать MLAgent. Я узнал, что при изменении lambd значение entropy радикально понижалось на графике. Также, при изменении остальных значений график entropy растет значительное быстрее чем при оригинальных значениях. Самым удачным можно выделить изменение batch_size, т.к все графики растут больше чем при других изменениях и даже больше чем при оригинальных значениях.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
