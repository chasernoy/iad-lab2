# iad-lab2
# Лабораторная работа №2 «Обнаружение аномалий и выбросов в данных»

## Данные
Файл: `data/extreme_pollution.csv` 

## Структура репозитория
- `notebooks/lab2_outliers.ipynb` — основной ноутбук с анализом.
- `data/` — папка с исходным датасетом.

## Запуск

### 1) Клонирование репозитория
```
git clone https://github.com/chasernoy/iad-lab2.git
cd iad-lab2
```
### 2) Окружение и зависимости
```
python3 -m venv .venv
source .venv/bin/activate       
pip install -U pip
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```
### 3) Запуск ноутбука
```
python3 -m jupyter lab
```
