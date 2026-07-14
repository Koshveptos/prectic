# Income Prediction — Прогноз дохода клиента

Модель для участия в соревновании по прогнозированию дохода клиента банка.  
Целевая метрика — **WMAE** (Weighted Mean Absolute Error).


## Требования

- Python 3.10+
- 16+ ГБ RAM (рекомендуется 32 ГБ) - если хотите optima на итераций 10 -20 то 64)

## Установка и запуск (локально)

## Создание виртуального окружения

```
# Установка uv
pip install uv

# Создание окружения
uv venv .venv

# Активация
.venv\Scripts\activate

#зависимости
uv pip install -r requirements.txt


# или напрямую 
uv pip install jupyter notebook pandas numpy scikit-learn xgboost lightgbm catboost optuna scipy


## и выбор ядра для юпитера локалка
python -m ipykernel install --user --name=v8-income --display-name="Python curnel"
```