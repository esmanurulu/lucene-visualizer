# Apache Lucene Visual Dashboard & Inverted Index Simulator

BIL 401 Büyük Veri ve Dağıtık Veri İşleme dersi kapsamında geliştirilen, **Apache Lucene** arama motoru mimarisini ve **Inverted Index (Ters İndeks)** yapısını görselleştiren interaktif bir web simülatörüdür.

## Projenin Amacı
Geleneksel ilişkisel veri tabanlarının (SQL) metin aramalarında kullandığı kaba kuvvet tam tablo taramalarının (`LIKE` sorguları) kısıtlarını aşmak ve modern arama motorlarının arka planda veriyi nasıl indeksleyip milisaniyeler içinde sorguladığını görsel olarak kanıtlamaktır.

## Temel Özellikler
1. **Document & Fields Yönetimi:** E-ticaret verileri üzerinden `Title`, `Author` ve `Content` alanlarıyla doküman yönetimi.
2. **Text Analysis Pipeline:** - **Tokenization:** Metinlerin kelimelere ayrıştırılması.
   - **Lowercase:** Küçük harf dönüşümü.
   - **Stop Words Removal:** Anlamsız bağlaçların (durak kelimelerin) temizlenmesi.
3. **Inverted Index (Ters İndeks) & TF (Term Frequency):** Terimlerin hangi dokümanlarda geçtiğini ve frekanslarını gösteren disk depolama haritası.
4. **Anlık Arama ve Eşleşme Vurgulama:** Arama çubuğuna yazılan terimin indeks üzerinden O(1) hızında sorgulanarak ilgili dokümanları yeşil renkle öne çıkarması.

   !Bu istemci tabanlı arayüzde kök ayrıştırma adımı bilinçli olarak hariç tutulmuştur.

## Kurulum ve Çalıştırma
Proje tamamen saf HTML, CSS ve JavaScript ile geliştirildiği için herhangi bir sunucu veya ek kütüphane kurulumu gerektirmez.
