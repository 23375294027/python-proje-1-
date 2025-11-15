# python-proje-1-
E-ticaret satış veri analizi projesi Proje Amacı: Bu proje, e-ticaret veri setini analiz ederek satış yapıyor, popüler ürünler ve müşteri satın almayı hedefliyor. Analiz sonucu “hangi ürüne odaklanmalı” ve “müşteri kitlesi hakkında bilgiler” gibi öngörüler sunulmuştur.

1️⃣ Veri Seti ve Ön İşleme

Veri kitapları: basket_details.csv ve customer_details.csv

İki veri seti customer_id üzerinden birleştirilmiş (sol birleştirme).

basket_count ve Fiyat sütunları kısmından Gelir (gelir) hesaplandı.

basket_date sütunu tarih formatına dönüştürüldü.

2️⃣ Temel Analiz Bulguları a) Müşteri Dağılımı

Toplam müşteri sayısı: X

Cinsiyete göre Dağıtım:

Erkek: Y

Kadın: Z

b) Sepet ve Satış Bilgileri

Toplam sepet sayısı: T

ortalama sepet başına ürün sayısı: A

Sepetin yapısındaki histogram dosyası görselleştirilir.

c) En Popüler Ürünler

Top 10 ürün (satış adedi bazında):

Ürün ID Toplam Satış Adı … …

En çok gelir getiren ürün: Ürün ID: X

💡 Öneri: Şirketin bu ürüne odaklanmalı, reklam ve stok yatırımı artırılabilir.

d) Zaman Trendleri

Sepete eklenerek incelenerek aylık satış trendi gözlemlendi.

Gelir artışı/düşüşleri grafiği iletildi (isteğe bağlı matplotlib kullanımı).

3️⃣ Görselleştirmeler

En Popüler 10 Ürün – Bar grafiği
<img width="1000" height="600" alt="Figure_1" src="https://github.com/user-attachments/assets/7fc79e19-b4e3-42f6-aa33-19678fae4f43" />


Cinsiyete Göre Kullanımı
<img width="600" height="400" alt="Figure_2" src="https://github.com/user-attachments/assets/4948701a-4d82-49ba-94c1-abf8a8f771c6" />

Sepet Sayısı Dağılımı – 
<img width="600" height="400" alt="Figure_3" src="https://github.com/user-attachments/assets/af6ba707-9060-4ab2-b8fe-db71dcd8dc69" />

(Grafikler Jupyter/Matplotlib dosya sayısı.)

4️⃣ Özet ve Öneriler

Hangi ürüne odaklanmalı: En çok gelir getiren ürün, şirket için seçilir.

Müşteri hedefleme: Cinsiyet ve sepet sayıları analizlerine göre reklam ve kampanyalar optimize edilebilir.

Stok ve reklam: Popüler ürünler için stratejik stok ve pazarlama yatırımı önerilir.

Kampanya fırsatları: Daha az satan ürünler için paket ve indirim kampanyaları planlanabilir.
