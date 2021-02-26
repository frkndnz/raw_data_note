# Data Processing
 Veri işlemeye nasıl başlamalıyım ? Kendime notlar


<img src="https://wallpaper-mania.com/wp-content/uploads/2018/09/High_resolution_wallpaper_background_ID_77700863611.jpg" width="400"/>

## Çalışma Verisi Bulmak
[kaggle](https://www.kaggle.com/)
	
## Gerekli Kütüphaneler

 + Pandas
 	+ pip install pandas
 + Seaborn
 	+ pip install seaborn
 + Numpy
 	+ pip install numpy 

### Kütüphaneleri içeri alma
```	
import pandas as pd
import seaborn as sns 
import matplotlib.pyplot as plt

```
### veriyi alma 
```
data= pd.read_csv("temp.txt",parse_dates=["dt"])
data.head() 
data.shape() # veri boyutu
data.dtypes # verideki değişken tiplerini öğrenme

