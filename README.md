# Обнаружение болезни Паркинсона с использованием XGBoost

Этот проект использует классификатор XGBoost для обнаружения болезни Паркинсона на основе различных биомедицинских голосовых измерений. Используется набор данных `parkinsons.data`.

## Установка

1. Клонируйте репозиторий:
    ```sh
    git clone https://github.com/yourusername/parkinsons-detection.git
    ```
2. Перейдите в каталог проекта:
    ```sh
    cd parkinsons-detection
    ```
3. Установите необходимые зависимости:
    ```sh
    pip install -r requirements.txt
    ```

## Использование

1. Запустите Jupyter Notebook:
    ```sh
    jupyter notebook parkinsons_XGBClassifier_with_explanations.ipynb
    ```
2. Следуйте шагам в блокноте для предобработки данных, обучения модели и оценки её производительности.

## Структура проекта

- `parkinsons_XGBClassifier_with_explanations.ipynb`: Jupyter Notebook, содержащий код для предобработки данных, обучения модели и оценки её производительности.
- `parkinsons.data`: Набор данных, используемый для обучения и тестирования модели.
- `requirements.txt`: Список зависимостей, необходимых для запуска проекта.

## Зависимости

- numpy
- pandas
- scikit-learn
- seaborn
- matplotlib
- xgboost


