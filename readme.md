## DSR Mini-Competition

Rossman Kaggle Mini-Competition: Forecast sales using store, promotion, and competitor data

This is a Kaggle competition and can be found [here](https://www.kaggle.com/competitions/rossmann-store-sales/overview)

### Setup

1 - Create a conda environment

2 - Install Pip
```conda install pip```

3 - ```pip install -r requirements.txt```

4 - Run the `minicomp.ipynb` Notebook to fit the model

5 - Run the `make_pred.ipynb` Notebook to make predictions




### Feature

In the model we selected the following features:

- `Promo`: Mean encoding (including `Store`) [new var: `PromoStoreMean`]
- `DayofWeek`: Mean encoding
- `Date`: extract `Month` and then Mean encoding [new var: `MonthMean`]
- `Storetype`: Mean encoding
- `StateHoliday`: Mean encoding
- `SchoolHoliday`: Mean encoding
- `Promo2`: Mean encoding
