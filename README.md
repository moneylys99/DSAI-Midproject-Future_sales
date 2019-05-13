## DSAI-Mid. Project: Predict Future Sales ##
### 數據所 錢信諺 ###
#### 以https://www.kaggle.com/dhimananubhav/feature-engineering-xgboost 做參考學習

1. 以Kaggle上的參考資料跑一遍：由於我們的資料為第二版資料，可能和第一版有些不同，跑出來的結果為0.91XXX
2. 一般認為特徵過多的情況下容易導致Overfitting，因此我選取部分參考資料所使用的特徵、對類別資料做One-Hot Encoder轉換、以及對數值資料標準化後進行測試，其說明及Leader board結果如下:  
    a. 0.94xxx  
    https://nbviewer.jupyter.org/github/moneylys99/DSAI-Midproject-Future_sales/blob/master/sales-xgboost-094.ipynb  
    b. 0.92718  
    https://nbviewer.jupyter.org/github/moneylys99/DSAI-Midproject-Future_sales/blob/master/sales-xgboost-092718.ipynb 
    c. 0.92030
    https://nbviewer.jupyter.org/github/moneylys99/DSAI-Midproject-Future_sales/blob/master/sales-xgboost-092030.ipynb
