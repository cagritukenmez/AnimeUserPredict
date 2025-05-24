#Giriş
- Bu projenin amacı animeye ait verilerden yola çıkarak IMDb puanını tahmin eden bir makine öğrenmesi modelinin geliştirilmesidir. Projenin veriseti Kaggle sitesinde bulunan Anime Recommendations Database verisetidir. Kullanılan verisetinde 2 farklı veriseti var: Birisi Animeler hakkında bilgi içerek veriseti olup diğeri ise Kullanıcıların animelere verdikleri puanları tutan verisetidir. Bu proje dahilinde Animeler hakkında bilgi içeren veriseti kullanılmıştır.Farklı algoritmalar denendi ve denemelerin sonucunda algoritmalar karşılaştırılmıştır. Uygun olan model ile devam edilmiştir. Bu projeyi geliştirirken kaggle üzerindeki notebook'dan çalıştım.

#Metrikler
- Root Mean Squared Error (RMSE): Bu metrik, hataları orijinal puan biriminde yorumlamamıza olanak tanır. RMSE’nin yaklaşık 0.63 olması, modelimizin ortalama olarak gerçek IMDb puanından en fazla ±0.63 civarında sapma gösterdiğini ifade eder.

- Mean Absolute Error (MAE): Modelin tahminlerinin ortalama olarak yaklaşık yarım puan (0.45) kadar sapma gösterdiğini görüyoruz. MAE, RMSE’ye kıyasla daha “affedici” bir ölçümdür çünkü hataların karesini almaz. Gerçek hayatta bir animenin puanının 8.2 yerine 7.8 olarak tahmin edilmesi çoğu kullanıcı için fark edilmeyecek kadar küçük bir hata olabilir. 

- R² Skoru: R² skoru, modelin hedef değişkendeki toplam varyansın ne kadarını açıkladığını gösterir. %61’lik bir açıklama oranı, verideki IMDb puanlarını etkileyen faktörlerin büyük bir kısmının model tarafından öğrenilebildiğini, yani modelin sadece tahmin değil, anlamlandırma konusunda da başarılı olduğunu ifade eder.

#Linkler
https://www.kaggle.com/code/artkenmez/anime-puan-tahmini
