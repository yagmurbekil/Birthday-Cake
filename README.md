🎂 Interactive Birthday Cake (Web Audio API Experiment)

 Bu proje, sevdiklerim için hazırladığım interaktif bir dijital kutlama sayfasıdır. Kullanıcının mikrofon aracılığıyla "üfleme" sesini algılayarak mumları söndüren basit ama etkileşimli bir web deneyimi sunar.

🚀 Özellikler

* Gerçek Zamanlı Ses Analizi: Tarayıcı üzerinden mikrofon verilerini işleyerek belirli bir ses eşiğinin (threshold) üzerindeki frekansları algılar.

* Dinamik DOM Yönetimi: Ses seviyesine göre mum alevlerini (CSS animasyonları) anlık olarak kontrol eder.

* Responsive Tasarım: Farklı ekran boyutlarına uyumlu, tamamen CSS ile oluşturulmuş pasta tasarımı.

🛠️ Teknik Detaylar

* Bu projede aşağıdaki teknolojiler ve API'lar kullanılmıştır:

*  Web Audio API: AudioContext ve AnalyserNode kullanılarak ses verisi Uint8Array formatında işlenmiştir.

*  JavaScript (ES6+): Asenkron mikrofon erişimi ve ses frekans hesaplamaları için.

*  CSS3: Mum alevi titreşimleri (flicker) için keyframe animasyonları ve pasta katmanları için modern CSS teknikleri.

⚠️ Önemli Notlar (Tarayıcı Uyumluluğu)

  Tarayıcıların güvenlik protokolleri gereği deneyimin sorunsuz çalışması için:

1. Sayfa yüklendikten sonra herhangi bir yere bir kez tıklanması gerekmektedir (AudioContext'in aktifleşmesi için).

2. Tarayıcının mikrofon erişimine izin verilmelidir.

3. Bazı mobil tarayıcılar (iOS Safari vb.) Web Audio API kısıtlamalarına sahip olabileceği için masaüstü tarayıcılarda (Chrome, Edge, Firefox) kullanılması önerilir.

📸 Ekran Görüntüsü
<img src="ekran-goruntusu1.png" alt="Ekran Görüntüsü" width="500">
<img src="ekran-goruntusu2.png" alt="Ekran Görüntüsü" width="500">
<img src="ekran-goruntusu3.png" alt="Ekran Görüntüsü" width="500">
