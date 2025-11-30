

### **Proje Özeti**

Bu proje, 5 kişilik ekibimizin veri setinden en doğru sonucu almak için güçlerini birleştirdiği bir makine öğrenmesi çalışmasıdır. Amacımız, farklı teknikleri deneyerek en az hatayla tahmin yapan modeli bulmaktır.

Ekipteki görev dağılımımız şu şekildedir:

* **1. Kişi (Güçlü Modeller):** Hata payını düşürmek için en popüler ve güçlü algoritmalar olan **Random Forest** ve **LightGBM**'i kullandı.
* **2. Kişi (Referans ve Analiz):** Projenin başlangıç (baz) puanını belirledi (**Bayesian Ridge**) ve benzerlik tabanlı tahminler (**KNN**) yaptı.
* **3. Kişi (Klasik vs Modern):** En temel yöntem (**Linear Regression**) ile en gelişmiş yöntemlerden birini (**XGBoost**) kıyasladı.
* **4. Kişi (Veri Optimizasyonu):** Modellerin daha iyi çalışması için gereksiz verileri ayıkladı ve veri setini sadeleştirdi (**SFS ve PCA**).
* **5. Kişi (Esnek Yöntemler):** Karar ağacı yapılarını (**Decision Tree**) ve karmaşık verileri ayırabilen vektör makinelerini (**SVR**) test etti.

**Sonuç:** Tüm bu yöntemlerin performansları kıyaslanarak veri seti için en uygun çözüm belirlenmiştir.
