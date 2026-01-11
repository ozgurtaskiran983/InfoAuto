# 🚗 InfoAuto: Yapay Zeka Destekli Otomobil Servis Rehberi ve Fiyat Analiz Platformu

[cite_start]Bu proje, **Gazi Üniversitesi Teknoloji Fakültesi Bilgisayar Mühendisliği Bölümü** "Yazılım Mühendisliği" dersi kapsamında geliştirilmiştir[cite: 1, 2, 3, 4]. [cite_start]**InfoAuto**, araç sahiplerinin servis süreçlerinde karşılaştığı fiyat dengesizliği ve bilgi asimetrisini ortadan kaldırmayı hedefleyen yenilikçi bir mobil platformdur[cite: 5, 71, 77].

---

## 🎯 Projenin Amacı ve Problem Tanımı
* [cite_start]**Fiyat Şeffaflığı:** Türkiye'de servisler arasında görülen %50 ile %150 arasındaki fiyat farklarının önüne geçmek amaçlanmıştır[cite: 87].
* [cite_start]**Bilgi Asimetrisi:** Kullanıcıların teknik bilgi eksikliği nedeniyle yaşadığı mağduriyetleri ve kandırılma riskini önler[cite: 77, 88].
* [cite_start]**Dijital Rehber:** Kullanıcılara sanayiye gitmeden önce dijital bir ön inceleme, arıza tahmini ve adil fiyat rehberi sunar[cite: 78, 101].

## 🚀 Öne Çıkan Özellikler
* [cite_start]**YZ Tabanlı Arıza Tespiti:** Görüntü işleme (CNN) ve ses analizi (LSTM/CNN) teknolojileriyle araçtaki arızaları fotoğraf veya motor sesi üzerinden tahmin eder[cite: 79, 104, 208, 209].
* [cite_start]**Adil Fiyat Hesaplama:** Parça maliyeti, işçilik ve sanayi odası resmi tarifelerinin entegrasyonuyla makul bir "adil piyasa fiyatı" aralığı belirler[cite: 112, 114].
* [cite_start]**Kullanıcı Katılımlı Fiyat Havuzu:** Anonim veri paylaşımı ve yapay zeka destekli aykırı değer analizi (Outlier Detection) ile güncel bir fiyat veritabanı oluşturur[cite: 82, 83, 116, 204].
* [cite_start]**Konum Tabanlı Servis Önerileri:** PostGIS desteği ile yakındaki güvenilir ustaların, servislerin ve semt bazlı fiyat karşılaştırmalarının harita üzerinde gösterilmesini sağlar[cite: 122, 124, 205].

## 💻 Teknik Mimari ve Teknoloji Yığını
* [cite_start]**Frontend:** Flutter (Android & iOS)[cite: 187, 188].
* [cite_start]**Backend:** Python (Django/Flask) veya Node.js[cite: 196].
* [cite_start]**Veritabanı:** PostgreSQL (Konumsal analizler için PostGIS eklentisi ile)[cite: 197, 205].
* **Yapay Zeka:** CNN tabanlı görüntü işleme; [cite_start]MFCC, Spectrogram ve LSTM tabanlı ses analizi modelleri[cite: 208, 209].

## 📊 Proje Yönetimi ve Analizler
* [cite_start]**Ekonomik Fizibilite:** Projenin başlangıç maliyeti 1.330.000 TL olarak öngörülmüş olup, ilk yıl sonunda toplumsal bazda 15.000.000 TL'lik bir tasarruf sağlaması hedeflenmektedir[cite: 323, 324, 325].
* [cite_start]**Risk Yönetimi:** Veri manipülasyonu, KVKK uyumu ve YZ analiz hataları gibi riskler için teknik ve yasal önleyici faaliyetler planlanmıştır[cite: 341, 346, 356].
* [cite_start]**İş Takvimi:** Proje; planlama, analiz, AR-GE/Geliştirme ve test aşamalarını kapsayan toplam 15 haftalık bir süreci takip etmektedir[cite: 229, 230].

## 📂 Depo İçeriği
Depo içerisinde projeye ait şu dokümantasyonlar yer almaktadır:
* [cite_start]**infoauto_fizibilite_raporu.docx:** Teknik, ekonomik ve operasyonel uygulanabilirlik analizi[cite: 71, 74].
* **infoauto_isterler_raporu.docx:** Sistemin işlevsel ve işlevsel olmayan gereksinimleri.
* **infoauto_teydeb_raporu.docx:** Projenin Ar-Ge niteliği ve yenilikçi yönlerinin dökümü.
* **infoauto_sunumu.pdf:** Genel proje tanıtımı ve çözüm önerilerini içeren görsel sunum.

---
[cite_start]**Ekip Üyeleri:** Serdar Kafalı, Özgür Taşkıran, Eren Büyükaşık, Nehir Uzunçakmak[cite: 7, 8, 9, 10].
