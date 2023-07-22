## DSR Mini-Competition

Rossman Kaggle Mini-Competition: Forecast sales using store, promotion, and competitor data

This is a Kaggle competition and can be found [here](https://www.kaggle.com/competitions/rossmann-store-sales/overview)

### Setup

1 - Create a conda environment

2 - Install Pip
```conda install pip```

3 - ```pip install -r requirements.txt```

4 - Run the `4._random_forest.ipynb` Notebook to fit the model

5 - Run the `make_pred_2.ipynb` Notebook to make predictions




### Feature

In the model we selected the following features:

- `SchoolHoliday`: binary variable
- `StoreType`: One-Hot encoding
- `Assortment`: One-Hot encoding
- `Promo2`: Mean impute + standard scaler
- `Date`: extract `Month` and then Mean encoding + mean impute + standard scaler [new var: `Month_mean`]
- `Store`: Mean encoding + mean impute + standard scaler [new var: `Store_mean`]
- `DayOfWeek`: Mean encoding + mean impute + standard scaler [new var: `DayOfWeek_mean`]
- `Promo`: Mean encoding (including `Store`) + mean impute + standard scaler [new var: `PromoStore_mean`]
- `CompetitionDistance`: Clip (upper=10000) + bins (10) [new variable: `CD_clip_bins_clip`]

