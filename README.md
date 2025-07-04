# 🚗 İnsansız Kara Aracı (İKA) Projesi

**Alavan Teknoloji Takımı** olarak geliştirmekte olduğumuz İnsansız Kara Aracı (İKA) projesi, zorlu arazi şartlarında otonom görev icra edebilen, çevresini algılayan ve verilen görevleri başarıyla tamamlayabilen modüler bir kara aracı sistemidir.

Projemiz, görüntü işleme, otonom navigasyon, sensör füzyonu ve gerçek zamanlı karar alma sistemlerini entegre eden **profesyonel bir mühendislik altyapısına** sahiptir.

---

## 🎯 Proje Amacımız

İKA projemizin temel hedefleri şunlardır:
- Otonom sürüş kabiliyeti ile parkur görevlerini başarıyla tamamlamak  
- Gerçek zamanlı görüntü işleme ile duba, engel ve hedef tespiti yapmak  
- Lidar, kamera ve diğer sensörlerden gelen verileri birleştirerek çevre farkındalığı oluşturmak  
- TEKNOFEST İKA Yarışması için teknik yeterliliği yüksek, modüler ve geliştirilebilir bir platform sunmak

---

## 🧠 Kullanılan Teknolojiler

| Alan               | Teknoloji                        |
|--------------------|----------------------------------|
| **Programlama**    | Python, ROS (Robot Operating System) |
| **Görüntü İşleme** | YOLOv8 ile nesne tespiti         |
| **Donanım**        | Raspberry Pi / Jetson Nano, Lidar, IMU, Ultrasonik sensörler |
| **Modelleme**      | 3D baskı ile özel şasi ve gövde tasarımı |
| **Haberleşme**     | UART / I2C / GPIO tabanlı modül entegrasyonu |

---

## 🔧 Yazılım Özellikleri

- YOLOv8 ile nesne (duba) tespiti ve iki duba arasından geçiş  
- Lidar ve Ultrasonik sensörlerle dinamik engelden kaçınma  
- Kamera görüntüsünden hedefe yönelim ve park etme  
- ROS mimarisi ile modüler node yapısı ve paralel işlem yönetimi  
- PID kontrollü yol takip algoritmaları

---

## 🧱 Sistem Mimarisi

Kamera / Lidar / IMU
↓
ROS Sensor Nodes
↓
Görüntü İşleme ve Karar Verme
↓
Motor Kontrol (PWM)
↓
Araç Hareketi

---

## 📌 Yarışma Süreci

- Projemiz, **TEKNOFEST 2025 İnsansız Kara Aracı Yarışması** kapsamında geliştirilmiştir.  
- Takımımız, yarışmanın **Kritik Tasarım Raporu** aşamasına kadar başarılı bir şekilde ilerlemiş ancak bu aşamada elenmiştir.  
- Teknik kabiliyetimizi ve sistem entegrasyonumuzu ileri seviyeye taşımak için analizler yapılmış, eksikler belirlenmiş ve proje yeniden yapılandırılmıştır.  

### 🎯 Hedefimiz:  
**TEKNOFEST 2026** İKA Yarışmasında tam otonom bir sistemle, tüm görevleri eksiksiz yerine getirmek ve final aşamasına ulaşmak.

---

## 👥 Takımımız

> **Alavan Teknoloji Takımı** — Pamukkale Üniversitesi  
> Projede farklı mühendislik disiplinlerinden öğrenciler yer almaktadır.  

**Yazılım ve Otonomi Geliştirici:**  
-🧑‍💻 *Mahir Berat Menteş*  
Görüntü işleme sistemleri otonom sürüş algoritmalarından sorumludur.

-🧑‍💻 *Halil Aydın*  
ROS tabanlı yazılım mimarisi ve otonom sürüş algoritmalarından sorumludur.

---

## 📷 Görseller (Yakında)

- Aracın CAD tasarımları  
- Parkur test videoları  
- Geliştirme sürecinden fotoğraflar  

---

## 📁 Kurulum ve Çalıştırma (Yakında)

> Gerekli dosyalar ve çalıştırma yönergeleri proje tamamlandığında buraya eklenecektir.

---

## 📬 İletişim

📧 mahirberatmentes@gmail.com  
💬 İş birliği teklifleri ve teknik sorular için bizimle iletişime geçebilirsiniz.

---

> Bu proje, **Türkiye Teknoloji Takımı Vakfı (T3 Vakfı)** ve **TEKNOFEST** çatısı altında yürütülmekte olup, mühendislik yetkinliğimizi artırmak, takım çalışması bilincimizi geliştirmek ve ülkemiz için katma değer üretmek amacıyla geliştirilmektedir.
