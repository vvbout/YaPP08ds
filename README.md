# YaPP08ds
Determining the toxicity of user edits
# Определение токсичности правок пользователей
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Задача пректа:
* на основе набора данных с разметкой о токсичности правок обучить модель классифицировать комментарии на позитивные и негативные.
* Построить модель со значением метрики качества F1 не меньше 0.75.

## Инструкция по выполнению проекта:
1. Загрузите и подготовьте данные.
2. Обучите разные модели.
2. Сделайте выводы.

## Описание данных:
* Данные находятся в файле toxic_comments.csv.
* Столбец text содержит текст комментария.
* Столбец toxic содержит целевой признак.
