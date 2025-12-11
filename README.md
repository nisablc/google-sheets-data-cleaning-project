# google-sheets-data-cleaning-project
[Google Sheets](https://docs.google.com/spreadsheets/d/13-p-0HnnEDs7CYGKm3BKQmTOb8facGblqn_-gEMfGDI/edit?gid=1210785768#gid=1210785768)
Google
1. Raw Dataset (Ham Veri)
Kullanıcı ID
Aktivite tarihleri (farklı formatlarda, hatalı ve düzensiz)
Amount (para değerleri, $ işaretiyle)
Büyük/küçük harf karmaşası
Boşluk hataları
Veri özellikle temizlenebilir halde oluşturulmuştur.

2. Cleaned Dataset (Temiz Veri)
Veri Google Sheets fonksiyonları kullanılarak temizlendi:
TRIM() → gereksiz boşluklar temizlendi
PROPER() → büyük-küçük harf düzenlemesi
SUBSTITUTE() → tarih formatlama
DATEVALUE() → tarih formatlarını standartlaştırma
VALUE() → amount alanını sayıya çevirme
Ek olarak "activity_month" değişkeni oluşturulmuştur.

3. Analizler
A) En Aktif Kullanıcılar Analizi (Top 10 Users)
Pivot Table + COUNTA ile kullanıcı aktivite sayıları hesaplandı.
Sonrasında Top 10 listesi çıkarıldı ve bar chart ile görselleştirildi.

B) Aktivite Miktarı (Amount) Analizi
Kullanıcı bazında toplam tutarlar incelenebilir hale getirildi.

C) Pivot Tablolar ve Grafikler
Toplam aktivite sayısı
Kullanıcı başına aktivite
Top kullanıcı grafiği
Temizlenmiş veri üzerinde sorgulamalar

Bu çalışma, Google Sheets üzerinde veri temizleme ve temel analiz yürütme süreçlerini göstermektedir.

