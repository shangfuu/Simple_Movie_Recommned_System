# Simple movie recommendation system
> NTUST CSIE Data Science final project

> DataBase used : https://www.kaggle.com/tmdb/tmdb-movie-metadata

## 資料集
![credits.csv](https://github.com/shungfu/Simple_Movie_Recommned_System/raw/master/Image/credits_csv.png)

<img src="https://github.com/shungfu/Simple_Movie_Recommned_System/raw/master/Image/movies_csv.png" width="898" height="645"/>

## 以電影類型排名
<img src="https://github.com/shungfu/Simple_Movie_Recommned_System/raw/master/Image/crime.png" width="613" height="744"/>

## 以卡斯、團隊、關鍵字、類型建立推薦
<img src="https://github.com/shungfu/Simple_Movie_Recommned_System/raw/master/Image/recomand1.png" width="816" height="480"/>

## Collaborative Filtering
* 利用使用者的評分紀錄來推薦電影
* 使用者評分資料集
* 不是所有電影，使用者都會看過並且評分，所以需要預測
### 預測使用者評分
* 使用已知的評分去預測可能成績
<img src="https://github.com/shungfu/Simple_Movie_Recommned_System/raw/master/Image/colla.png" width="442" height="756">


## Hybrid Recommend
* 結合”相似電影”和”使用者喜好”來推薦
* 使用第一個方法，可以使用卡斯、導演、關鍵詞等，計算模擬分數，找出推薦的電影。
* 使用上述得到結果，再利用使用者喜好，即可推算出特定使用者的電影喜好

### User1 喜歡的前五種電影類型
* Action
* Adventure
* Comedy
* Family
* Drama

### User1 電影評分表
<img src="https://github.com/shungfu/Simple_Movie_Recommned_System/raw/master/Image/user1_rate.png" width="630" height="579">

### User1 推薦電影
<img src="https://github.com/shungfu/Simple_Movie_Recommned_System/raw/master/Image/user1_hybrid.png" width="677" height="329">
<img src="https://github.com/shungfu/Simple_Movie_Recommned_System/raw/master/Image/user1_hybrid2.png" width="1111" height="480">



