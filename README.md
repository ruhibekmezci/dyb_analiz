# 📝 Özet Test Analizi ve Raporlama Aracı

Bu proje, öğrencilerin ve eğitimcilerin deneme sınavı veya test sonuçlarını hızlıca analiz etmelerini, netlerini hesaplamalarını ve sonuçları raporlayarak kaydetmelerini sağlayan, tarayıcı tabanlı modern bir araçtır.

## ✨ Özellikler

* **📊 Detaylı Analiz:** Test başına Doğru, Yanlış, Boş, Net ve Başarı Yüzdesini hesaplar.
* **🧮 Net Hesabı:** Standart `(Doğru - Yanlış / 4)` formülünü kullanır.
* **💾 Raporlama:** Sonuçları detaylı bir `.txt` dosyası olarak bilgisayarınıza indirir.
* **🏷️ Akıllı Dosya İsimlendirme:** İndirilen raporları `Tarih_Ders_Konu_Yayınevi_DYB_Analizi.txt` formatında otomatik isimlendirir.
* **🎨 Modern Tasarım:** Göz yormayan Bordo/Krem renk paleti ve kart tasarımı.
* **🚀 Kurulumsuz:** Sadece HTML dosyasını açarak çalışır, internet bağlantısı gerektirmez.

## 🚀 Nasıl Kullanılır?

1.  **Projeyi Çalıştırın:** `dyb_analiz.html` dosyasına çift tıklayarak tarayıcınızda açın.
2.  **Bilgileri Girin:** Ders, Konu ve Yayınevi bilgilerini ilgili kutucuklara yazın.
3.  **Verileri Girin:** Test verilerini **"Doğru-Yanlış-Boş"** formatında alt alta girin.
    * *Örnek Format:*
        ```text
        18-6-1
        15-7-3
        20-4-1
        ```
4.  **Hesaplayın:** `⚡ Hesapla` butonuna basın.
5.  **Rapor Alın:** Sonuçlar oluştuktan sonra beliren `💾 Rapor İndir` butonuyla çıktınızı alın.

## 📂 Dosya Yapısı

Proje tek bir HTML dosyasından oluşmaktadır. Tüm CSS (Tasarım) ve JavaScript (Mantık) kodları bu dosya içerisine gömülmüştür.

* `dyb_analiz.html`: Uygulamanın tamamını barındıran dosya.

## 🛠️ Kullanılan Teknolojiler

* **HTML5:** Sayfa iskeleti.
* **CSS3:** Flexbox ve Grid yapıları ile responsive tasarım.
* **JavaScript (ES6+):** Hesaplama mantığı, DOM manipülasyonu ve dosya indirme işlemleri.

## 📥 İndirme Formatı Örneği

İndirilen `.txt` dosyası şu formatta görünür:

```text
Ders: Matematik
Konu: Türev
Yayınevi: Ruhi B. Yayınları
--------------------------------
Test Sayısı: 5
Toplam Soru: 125
Toplam Net: 79.75
Başarı Yüzdesi: %63.80
--------------------------------
Test Detayları Tablosu:

TEST NO | DOĞRU | YANLIŞ | BOŞ | TOPLAM | NET | BAŞARI
Test 1	| 18	| 6	 | 1   | 25     | 16.50	| %72.0
...
--------------------------------
Oluşturulma Tarihi: 28.11.2025 14:30:00
