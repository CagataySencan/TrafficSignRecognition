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

![image](https://user-images.githubusercontent.com/44377977/152049121-cfa19643-c73b-4041-8186-76aaf0f31802.png)

Proje Danışmanı: Dr. Öğretim Üyesi Nilgün Güler Bayazıt <br />
Şencan, Çağatay <br />
Öztürk, Gizem <br />
Ocak 2022
