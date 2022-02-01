## **DERİN ÖĞRENME ile TRAFİK İŞARETLERİNİ TANIMA ve SINIFLANDIRMA**
### *YTU- Matematik Mühendisliği Tasarım Uygulamaları*

![image](https://user-images.githubusercontent.com/44377977/152046461-c97fcf3b-0715-441d-9627-a3e04edbf996.png)

### **Model İçeriği**

- Darknet, YOLOv4-Tiny; tanıma ve 4 üst sınıfa ayırma   
- CNN; sınıflandırma 
- Optik karakter tanıma(OCR) 
- Adversarial attack 
- GTSDB,GTSRB Fırat Üniversitesi Trafik İşaretleri veri setleri

**Önerilen model** temel olarak iki ana başlıktan oluşmaktadır. 
1. YOLO ile tespit ve üst sınıflandırma
2. CNN ile sınıflandırma

Böylece hem YOLO’nun *hızlı tespit ve göreceli iyi sınıflandırma* yetisinden yararlanılmış hem de son bir CNN katmanı kullanılarak daha *doğru sınıflandırma* sonuçlarına erişme garantilenmiştir. 

Modelin **YOLO** ile eğitilen kısmı veriyi 4 üst kategoriye ayırır ve **CNN** 43 kategoriye tanır. Ek olarak veri setindeki 43 alt sınıfa uymayan trafik işaretleri ve yol tabelaları için **Optik Karakter Tanıma (OCR)** yöntemi ile metin algılama özelliği eklenmiştir.

Ayrıca modelin başarımını çeşitli dış etkenlere karşı modeli güçlendirmek için **Adversarial Attack** yöntemi kullanılmıştır.

![19 01 2022 21_14_47](https://user-images.githubusercontent.com/44377977/152047955-5cbb2c6e-e57f-4315-923c-920a2992ba95.png = 250x250)
Proje Danışmanı: Dr. Öğretim Üyesi Nilgün Güler Bayazıt
Şencan, Çağatay
Öztürk, Gizem
Ocak 2022

