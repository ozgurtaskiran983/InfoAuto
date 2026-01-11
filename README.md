# 🚗 InfoAuto: Yapay Zeka Destekli Otomobil Servis Rehberi ve Fiyat Analiz Platformu

Bu proje, **Gazi Üniversitesi Teknoloji Fakültesi Bilgisayar Mühendisliği Bölümü** "Yazılım Mühendisliği" dersi kapsamında geliştirilmiştir. **InfoAuto**, araç sahiplerinin servis süreçlerinde karşılaştığı fiyat dengesizliği ve bilgi asimetrisini ortadan kaldırmayı hedefleyen yenilikçi bir mobil platformdur.

---

## 🎯 Projenin Amacı ve Problem Tanımı
* **Fiyat Şeffaflığı:** Türkiye'de servisler arasında görülen %50 ile %150 arasındaki fiyat farklarının önüne geçmek amaçlanmıştır.
* **Bilgi Asimetrisi:** Kullanıcıların teknik bilgi eksikliği nedeniyle yaşadığı mağduriyetleri ve kandırılma riskini önler.
* **Dijital Rehber:** Kullanıcılara sanayiye gitmeden önce dijital bir ön inceleme, arıza tahmini ve adil fiyat rehberi sunar.

## 🚀 Öne Çıkan Özellikler
* **YZ Tabanlı Arıza Tespiti:** Görüntü işleme (CNN) ve ses analizi (LSTM/CNN) teknolojileriyle araçtaki arızaları fotoğraf veya motor sesi üzerinden tahmin eder.
* **Adil Fiyat Hesaplama:** Parça maliyeti, işçilik ve sanayi odası resmi tarifelerinin entegrasyonuyla makul bir adil piyasa fiyatı aralığı belirler.
* **Kullanıcı Katılımlı Fiyat Havuzu:** Anonim veri paylaşımı ve yapay zeka destekli aykırı değer analizi ile güncel bir fiyat veritabanı oluşturur.
* **Konum Tabanlı Servis Önerileri:** PostGIS desteği ile yakındaki güvenilir ustaların, servislerin ve semt bazlı fiyat karşılaştırmalarının harita üzerinde gösterilmesini sağlar.

## 💻 Teknik Mimari ve Teknoloji Yığını
* **Frontend:** Flutter (Android & iOS).
* **Backend:** Python (Django/Flask) veya Node.js.
* **Veritabanı:** PostgreSQL (Konumsal analizler için PostGIS eklentisi ile).
* **Yapay Zeka:** CNN tabanlı görüntü işleme; MFCC, Spectrogram ve LSTM tabanlı ses analizi modelleri.

## 📊 Proje Yönetimi ve Analizler
* **Ekonomik Fizibilite:** Projenin başlangıç maliyeti 1.330.000 TL olarak öngörülmüş olup, ilk yıl sonunda toplumsal bazda 15.000.000 TL'lik bir tasarruf sağlaması hedeflenmektedir.
* **Risk Yönetimi:** Veri manipülasyonu, KVKK uyumu ve YZ analiz hataları gibi riskler için teknik ve yasal önleyici faaliyetler planlanmıştır.
* **İş Takvimi:** Proje; planlama, analiz, AR-GE/Geliştirme ve test aşamalarını kapsayan toplam 15 haftalık bir süreci takip etmektedir.

## 📂 Depo İçeriği
Depo içerisinde projeye ait şu dokümantasyonlar yer almaktadır:
* **Fizibilite Raporu:** Teknik, ekonomik ve operasyonel uygulanabilirlik analizi.
* **İsterler Raporu:** Sistemin işlevsel ve işlevsel olmayan gereksinimleri.
* **TEYDEB Raporu:** Projenin Ar-Ge niteliği ve yenilikçi yönlerinin dökümü.
* **Proje Sunumu:** Genel proje tanıtımı ve çözüm önerilerini içeren görsel sunum.

---
**Ekip Üyeleri:** Serdar Kafalı, Özgür Taşkıran, Eren Büyükaşık, Nehir Uzunçakmak.
