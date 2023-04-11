Pixel_ML
==============================

Using ML in UI/UX development

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>


--------
Pixel_ML
==============================

Использование ML в разработке UI/UX

Организация проекта
------------

    ├── LICENSE
    ├── Makefile         <- Makefile с командами типа `make data` или `make train`. instrumental
    ├── data
    │ ├── external         <- Data из сторонних источников.
    │ ├── interim         <- Промежуточные данные, которые были преобразованы.
    │ ├── processed         <- Финальные, канонические наборы данных для моделирования.
    │ └──── raw         <- Исходный, неизменяемый дамп данных.
    │
    ├──── docs         <- Проект Sphinx по умолчанию; подробности см. на sphinx-doc.org.
    │
    ├──── models         <- Обученные и сериализованные модели, предсказания моделей или сводки моделей
    │
    ├──── блокноты          <- блокноты Jupyter. Именное соглашение - это номер (для упорядочивания),
    │                     инициалы создателя и короткое описание, ограниченное `-`, например.
    │                     ``1.0-jqp-initial-data-exploration``.
    │
    ├──── references         <- Словари данных, руководства и все другие пояснительные материалы.
    │
    ├──── reports         <- Сгенерированный анализ в формате HTML, PDF, LaTeX и т.д.
    │ └──── figures        <- Сгенерированные графики и рисунки для использования в отчетах
    │
    ├──── requirements.txt           <- Файл требований для воспроизведения среды анализа, например.
    │ сгенерированный с помощью `pip freeze > requirements.txt`
    │
    ├──── setup.py <- делает проект pip installable (pip install -e .), чтобы src можно было импортировать
    ├──── src           <- исходный код для использования в этом проекте.
    │ ├── __init__.py           <- превращает src в модуль Python
    │ │
    │ ├──── data           <- Скрипты для загрузки или генерации данных
    │ │ └──── make_dataset.py
    │ │
    │ ├──── features           <- Скрипты для преобразования необработанных данных в характеристики для моделирования
    │ │ │ └──── build_features.py
    │ │
    │ ├──── models <- Скрипты для обучения моделей и последующего использования обученных моделей для получения
    │ │ │ │           предсказаний
    │ │ │ ├──── predict_model.py
    │ │ │ └── train_model.py
    │ │
    │ └──── visualization  <- Скрипты для создания исследовательских и ориентированных на результаты визуализаций
    │ └──── visualize.py
    │
    └── tox.ini <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>