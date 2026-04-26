# 📊 Türkiye'deki İlçelerin Okuma Yazma Durumu ve Cinsiyete Göre Analizi

Bu proje, Türkiye'deki ilçelerdeki okuma yazma durumu verilerini incelemeyi amaçlamaktadır. Veriler, TÜİK'ten alınan ve Türkiye'deki tüm ilçelere ait okuma yazma durumu hakkında bilgiler içermektedir. 

Amaç, okuma yazma durumu ile cinsiyet arasındaki ilişkiyi ve ilçeler arasındaki farklılıkları incelemektir. Proje, aynı zamanda toplumsal cinsiyet eşitsizliği ve eğitim düzeyi arasındaki bağlantıları anlamaya yönelik bir analiz sunmaktadır.

## 🚀 Proje Adımları ve Kullanılan Teknolojiler

* **Veri Çekme (Web Scraping):** `Tuik_Veri_Cekme.py` dosyası ile Selenium kullanılarak TÜİK veri tabanından otomatik olarak ilçe bazlı eğitim verileri çekilmiştir.
* **Veri Analizi ve Görselleştirme:** `İstatiktik_Veri_Analizi.py` dosyasında Python kütüphaneleri (Pandas, Matplotlib, Seaborn) kullanılmıştır. Proje kapsamında, bu veriler kullanılarak tanımlayıcı istatistikler (ortalama, medyan, mod), korelasyon analizi yapılmış ve çeşitli görselleştirmeler (grafikler) oluşturulmuştur.

## 📂 Veri Kaynağı ve Toplama Yöntemi

Veriler, Türkiye İstatistik Kurumu (TÜİK) tarafından sağlanan "Okuma Yazma Durumu" verileri kullanılarak toplanmıştır. Veriler, TÜİK'in resmi web sitesinden alınmış ve CSV formatında indirilmiştir.

### Veri Seti Hakkında Bilgi
Veri setinde 6 ana değişken bulunmaktadır:
1. Okuma yazma bilen erkekler
2. Okuma yazma bilmeyen erkekler
3. Okuma yazma durumu bilinmeyen erkekler
4. Okuma yazma bilen kadınlar
5. Okuma yazma bilmeyen kadınlar
6. Okuma yazma durumu bilinmeyen kadınlar

**Sayısal Veriler:** Her bir değişkenin değeri, belirli bir ilçedeki erkek ve kadınların okuma yazma durumu ile ilgili sayısal verilerdir.
