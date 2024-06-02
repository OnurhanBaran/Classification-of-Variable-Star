Veri Seti Linki : https://drive.google.com/drive/u/0/folders/1N7wUy_yGIOLxlXXUHLchHsaYFTx64Fvy

Makine Öğrenmesi projemi All Sky Automated Survey" (ASAS) Variable Star (https://asas-sn.osu.edu/variables) verileri ile Değişen Yıldızların Makine Öğrenmesi ile sınıflaması olarak yaptım. Bu projenin amacı Astronomide Değişen Yıldız Türlerinin bazı özelliklerine göre kolaylıkla sınıflamak için bir Makine Öğrenmesi Modeli belirlemektir. Gökyüzünde yer alan yıldızların değişen parlaklık ve özelliklerine dayanarak farklı yıldız türlerine ait olanları tanımlamaktır. Astronomi alanında bilimsel araştırmaların ve gözlemlerin verimliliğini arttırmaktır. ASAS Variable Star veri seti 687695 satır 82 sütundan oluşuyor. Verileri bazı kriterlere göre önişleme yapıyorum. Bu işlemler sonucu yeni satır sayım 450372'ye düştü. Bu da verilerin yaklaşık %65.4'lik kısmını kullandığım anlamına gelir.

Çeşitli grafikler ve histogramlarla verilerimi görselleştirdim. Bu sayede hangi özellikleri modelimde kullanacağıma karar vermek daha kolay oldu. Daha sonra verilerimin  konfüzyon matrisine bakarak kendi aralarındaki ilişkilerini gördüm. 

5  tane modelden (KNN, Random Forrest, Decision Tree, XGBoost, Bagging) en iyi skoru veren modeli seçtim. Bu modeli daha iyi hale getirmek için hiperparametre optimizasyonu yaptım.
