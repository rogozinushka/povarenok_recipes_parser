# Парсер кулинарных рецептов с сайта [povarenok.ru](https://www.povarenok.ru)
Чтобы получить рецепты, стоит лишь запустить скрипт из корня репозитория

```
python ./bs4_parser/parse_povarenok_ru.py --save_path some_new_folder_with_data
```

В процессе выполнения будет выводиться прогресс бар с примерным временем выполнения. 

В итоге получится датафрейм с такой структурой

|url|name|ingredients|
|-|-|-|
|https://www.povarenok.ru/recipes/show/171921/|Омлет с сыром и ветчиной|{'Яйцо куриное': '5 шт', 'Ветчина': '150 г', 'Сыр твердый': '150 г', 'Соль': '1 щепот.', 'Масло сливочное': '10 г', 'Молоко': '50 мл'}|

Этот датасет можно найти на [Kaggle](https://www.kaggle.com/rogozinushka/povarenok-recipes) и [HuggingFace](https://huggingface.co/datasets/rogozinushka/povarenok-recipes).

# Parser of recipes from [povarenok.ru](https://www.povarenok.ru) site

If you would like to get all recipes, just run the script below from repo root

```
python ./bs4_parser/parse_povarenok_ru.py --save_path some_new_folder_with_data
```

During the execution of the script, there will be a progress bar with the approximate execution time.

Finally, this dataframe will be made

|url|name|ingredients|
|-|-|-|
|https://www.povarenok.ru/recipes/show/171921/|Омлет с сыром и ветчиной|{'Яйцо куриное': '5 шт', 'Ветчина': '150 г', 'Сыр твердый': '150 г', 'Соль': '1 щепот.', 'Масло сливочное': '10 г', 'Молоко': '50 мл'}|


This dataset was uploaded to [Kaggle](https://www.kaggle.com/rogozinushka/povarenok-recipes) and [HuggingFace](https://huggingface.co/datasets/rogozinushka/povarenok-recipes).
