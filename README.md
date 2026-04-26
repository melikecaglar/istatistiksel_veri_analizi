# [cite_start]📊 Türkiye'deki İlçelerin Okuma Yazma Durumu ve Cinsiyete Göre Analizi [cite: 1]

[cite_start]Bu proje, Türkiye'deki ilçelerdeki okuma yazma durumu verilerini incelemeyi amaçlamaktadır[cite: 2]. [cite_start]Veriler, TÜİK'ten alınan ve Türkiye'deki tüm ilçelere ait okuma yazma durumu hakkında bilgiler içermektedir[cite: 3]. 

[cite_start]Amaç, okuma yazma durumu ile cinsiyet arasındaki ilişkiyi ve ilçeler arasındaki farklılıkları incelemektir[cite: 6]. [cite_start]Proje, aynı zamanda toplumsal cinsiyet eşitsizliği ve eğitim düzeyi arasındaki bağlantıları anlamaya yönelik bir analiz sunmaktadır[cite: 7].

## 🚀 Proje Adımları ve Kullanılan Teknolojiler

* **Veri Çekme (Web Scraping):** `Tuik_Veri_Cekme.py` dosyası ile Selenium kullanılarak TÜİK veri tabanından otomatik olarak ilçe bazlı eğitim verileri çekilmiştir.
* **Veri Analizi ve Görselleştirme:** `İstatiktik_Veri_Analizi.py` dosyasında Python kütüphaneleri (Pandas, Matplotlib, Seaborn) kullanılmıştır. [cite_start]Proje kapsamında, bu veriler kullanılarak tanımlayıcı istatistikler (ortalama, medyan, mod), korelasyon analizi yapılmış ve çeşitli görselleştirmeler (grafikler) oluşturulmuştur[cite: 5].

## [cite_start]📂 Veri Kaynağı ve Toplama Yöntemi [cite: 8]

[cite_start]Veriler, Türkiye İstatistik Kurumu (TÜİK) tarafından sağlanan "Okuma Yazma Durumu" verileri kullanılarak toplanmıştır[cite: 8]. [cite_start]Veriler, TÜİK'in resmi web sitesinden alınmış ve CSV formatında indirilmiştir[cite: 9].

### [cite_start]Veri Seti Hakkında Bilgi [cite: 11]
[cite_start]Veri setinde 6 ana değişken bulunmaktadır[cite: 12]:
1. [cite_start]Okuma yazma bilen erkekler [cite: 13]
2. [cite_start]Okuma yazma bilmeyen erkekler [cite: 14]
3. [cite_start]Okuma yazma durumu bilinmeyen erkekler [cite: 15]
4. [cite_start]Okuma yazma bilen kadınlar [cite: 16]
5. [cite_start]Okuma yazma bilmeyen kadınlar [cite: 17]
6. [cite_start]Okuma yazma durumu bilinmeyen kadınlar [cite: 18]

[cite_start]Sayısal Veriler: Her bir değişkenin değeri, belirli bir ilçedeki erkek ve kadınların okuma yazma durumu ile ilgili sayısal verilerdir[cite: 20].
