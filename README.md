# 📊 Data Science Assignments with PyCaret

Welcome to the repository containing a variety of data science assignments. This repository aims to showcase different methodologies and approaches using the PyCaret library.

## 📌 Table of Contents
1. [📱 Smartphone Models Dataset Analysis](#smartphone-models-dataset-analysis)
2. [🤖 Machine Learning Assignments](#machine-learning-assignments)
3. [⏳ Time Series Assignments](#time-series-assignments)
4. [❗ Issues Faced with Kaggle Datasets for Time Series](#issues-faced-with-kaggle-datasets-for-time-series)
5. [🎥 View the Recordings](#view-the-recordings)

### 📱 Smartphone Models Dataset Analysis
- **Dataset**: [Smartphone Models](https://www.kaggle.com/datasets/abdurrahman22224/smartphone-new-data)
- **Recording**: [Watch here](https://drive.google.com/file/d/1bjXlc1SSiTkOvHI7x7ElgCdRWiTTbQi5/view?usp=sharing)

### 🤖 Machine Learning Assignments
1. **Binary Classification** - [Email Spam Classification 📧](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv)
2. **Multiclass Classification** - [Instagram Play Store Reviews 📸](https://www.kaggle.com/datasets/saloni1712/instagram-play-store-reviews)
3. **Linear Regression** - [Airbnb Price Prediction 🏠](https://www.kaggle.com/datasets/stevezhenghp/airbnb-price-prediction/)
4. **Clustering** - [Bank Customer Segmentation 🏦](https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation)
5. **Association Rule** - [Groceries dataset 🛒](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset)
6. **Anomaly Detection** - [Credit Card Transaction 💳](https://www.kaggle.com/datasets/ybifoundation/credit-card-transaction)

### ⏳ Time Series Assignments
1. **With Exogenous Factors** - Lynx Dataset from PyCaret
   - [Recording 🎥](https://drive.google.com/file/d/19cmCIUFNbCep0EpXnOd60Yz0bJpHRvA9/view?usp=sharing)
2. **Without Exogenous Factors** - uschange Dataset from PyCaret
   - [Recording 🎥](https://drive.google.com/file/d/1VF3WPwU5Pk2Eqob_-J5CW7PyMcONVc5C/view?usp=sharing)

### ❗ Issues Faced with Kaggle Datasets for Time Series
I encountered challenges 🚧 with various Kaggle datasets for forecasting. A persistent error prevented us from proceeding. I've documented my experience and provided recordings for a more in-depth look.

**Error Faced**:
```
TypeError: X must be either None, or in an sktime compatible format, of scitype Series, Panel or Hierarchical, for instance a pandas.DataFrame with sktime compatible time indices, or with MultiIndex and last(-1) level an sktime compatible time index. See the forecasting tutorial examples/01_forecasting.ipynb, or the data format tutorial examples/AA_datatypes_and_datasets.ipynbIf you think X is already in an sktime supported input format, run sktime.datatypes.check_raise(X, mtype) to diagnose the error, where mtype is the string of the type specification you want for X. Possible mtype specification strings are as follows. "For Series scitype: ['pd.DataFrame', 'np.ndarray', 'pd.Series']. , "For Panel scitype: ['nested_univ', 'df-list', 'pd-multiindex', 'numpy3D', 'pd-long']. , "For Hierarchical scitype: ['pd_multiindex_hier'].
```

**Datasets Initially Tried from Kaggle**:
1. [Future Passengers Forecasting 🧳](https://www.kaggle.com/code/caesarmario/forecasting-future-passengers-w-pycaret/input)
2. [Crypto Forecasting 💹](https://www.kaggle.com/competitions/g-research-crypto-forecasting/data)
3. [Energy Consumption 🌆](https://www.kaggle.com/code/songulerdem/energy-consumption-forecasting-with-pycaret/input)
4. [Starbucks Stock Price ☕](https://www.kaggle.com/code/kalilurrahman/starbucks-stock-price-performance-analysis/notebook)

### 🎥 View the Recordings
For a deeper dive, watch our sessions where we discuss methodologies and results:
   - [Smartphone Models Dataset 📹](https://drive.google.com/file/d/1bjXlc1SSiTkOvHI7x7ElgCdRWiTTbQi5/view?usp=sharing)
   - [Time Series with Exogenous Factors 📹](https://drive.google.com/file/d/19cmCIUFNbCep0EpXnOd60Yz0bJpHRvA9/view?usp=sharing)
   - [Time Series without Exogenous Factors 📹](https://drive.google.com/file/d/1VF3WPwU5Pk2Eqob_-J5CW7PyMcONVc5C/view?usp=sharing)
---

Feedback and contributions are always welcome! 👋
