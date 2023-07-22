## DSR Mini-Competition

Rossman Kaggle Mini-Competition: Forecast sales using store, promotion, and competitor data

This is a Kaggle competition and can be found [here](https://www.kaggle.com/competitions/rossmann-store-sales/overview)

### Setup

1 - Create a conda environment

2 - Install Pip
```conda install pip```

3 - ```pip install -r requirements.txt```

4 - Run the 'minicomp.ipynb' Notebook to fit the model

5 - Run the 'make_pred.ipynb' Notebook to make predictions


### Feature

In the model we selected the following features:

- `SchoolHoliday`      385817 non-null  float64
- `StoreType`          397900 non-null  object 
- `Assortment`         397900 non-null  object 
- `Promo2`             397900 non-null  int64  
- `Month_mean`         397900 non-null  float64
- `Store_mean`         397900 non-null  float64
- `DayOfWeek_mean`     386039 non-null  float64
- `PromoStore_mean`    386000 non-null  float64
- `CD_clip_bins_clip`  396864 non-null  float64

