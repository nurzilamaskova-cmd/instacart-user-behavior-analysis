# Данные

В проекте используется открытый датасет **Instacart Online Grocery Basket Analysis**.

Источник:  
https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset

Исходные CSV-файлы не загружаются в репозиторий GitHub из-за их большого размера.

Для запуска ноутбука необходимо скачать датасет и поместить следующие файлы в эту папку:

```text
data/
├── aisles.csv
├── departments.csv
├── orders.csv
├── products.csv
├── order_products__prior.csv
└── order_products__train.csv
```

### Описание файлов

- `aisles.csv` — категории товаров;
- `departments.csv` — крупные товарные группы;
- `orders.csv` — информация о заказах и пользователях;
- `products.csv` — информация о товарах;
- `order_products__prior.csv` — товары из предыдущих заказов;
- `order_products__train.csv` — товары из обучающей выборки.

После загрузки файлов ноутбук `../notebooks/instacart_user_behavior.ipynb` использует их для подготовки единой аналитической таблицы и дальнейшего анализа.
