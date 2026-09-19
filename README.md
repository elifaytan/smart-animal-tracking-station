# Smart Animal Tracking and Feeding Station

Bu proje, hayvanların kimliklendirilmesi, izlenmesi ve kontrollü şekilde beslenmesini sağlamak amacıyla tasarlanmış yapay zekâ ve IoT tabanlı otonom bir sistem fikridir.

Sistem; RFID ile hayvan tanıma, kamera tabanlı görüntü analizi, Edge AI, uzaktan veri aktarımı, otomatik besleme ve güneş enerjisi destekli enerji yönetimi gibi teknolojileri tek bir yapı içerisinde birleştirmeyi amaçlamaktadır.

## Proje Özellikleri

- RFID tabanlı hayvan kimliklendirme
- Kamera ile hayvan görüntülerinin alınması
- Yapay zekâ destekli görüntü analizi
- Edge AI üzerinde yerel veri işleme
- MobileNetV2 / CNN tabanlı görüntü sınıflandırma yaklaşımı
- Otomatik yemleme sistemi
- Hayvanların beslenme bilgilerinin kaydedilmesi
- IoT tabanlı veri aktarımı
- MQTT haberleşme altyapısı
- GSM / LTE-M / NB-IoT üzerinden uzaktan bağlantı
- Bulut tabanlı veri takibi
- Dashboard üzerinden sistem izleme
- Güneş enerjisi destekli çalışma
- Batarya ve enerji yönetimi
- Düşük enerji tüketimine yönelik sistem tasarımı

## Sistem Bileşenleri

Projede aşağıdaki temel bileşenlerin birlikte kullanılması planlanmıştır:

- RFID okuyucu ve RFID etiketleri
- Kamera sistemi
- Edge AI işlem birimi
- Yemleme mekanizması
- IoT haberleşme modülü
- GSM / LTE-M / NB-IoT bağlantısı
- Güneş paneli
- Batarya sistemi
- Enerji yönetim birimi
- Bulut platformu
- Web tabanlı izleme paneli

## Sistem Çalışma Mantığı

Sistem hayvanın istasyona yaklaşmasıyla çalışmaya başlar.

İlk olarak RFID etiketi okunarak hayvanın kimliği belirlenir.

Daha sonra kamera üzerinden hayvanın görüntüsü alınır ve görüntü Edge AI sistemi üzerinde analiz edilir.

Hayvanın kimliği ve analiz sonucu doğrulandıktan sonra besleme mekanizması çalıştırılır.

Besleme işlemi sırasında elde edilen bilgiler sisteme kaydedilir.

Toplanan veriler IoT haberleşme altyapısı kullanılarak bulut sistemine aktarılır.

Kullanıcılar dashboard üzerinden hayvanların kimlik, beslenme ve sistem kullanım bilgilerini takip edebilir.

## Yapay Zekâ

Projede görüntü analizi için hafif ve düşük kaynak tüketen yapay zekâ modellerinin kullanılması planlanmıştır.

Özellikle Edge AI ortamlarında çalışmaya uygun olması nedeniyle MobileNetV2 ve CNN tabanlı görüntü işleme yaklaşımları değerlendirilmiştir.

Görüntü işleme sisteminin hayvanların tanınması veya sınıflandırılması gibi görevlerde kullanılması hedeflenmiştir.

## RFID Sistemi

Her hayvana özel bir RFID etiketi tanımlanması planlanmıştır.

Hayvan besleme istasyonuna geldiğinde RFID okuyucu etiketi algılar ve hayvanın kimliğini belirler.

Bu sayede:

- Hayvana özel kayıt tutulabilir.
- Beslenme zamanı takip edilebilir.
- Aynı hayvanın gereksiz yere tekrar beslenmesi önlenebilir.
- Hayvan bazlı kullanım geçmişi oluşturulabilir.

## IoT Haberleşmesi

Sistemin uzak bölgelerde de çalışabilmesi amacıyla IoT tabanlı haberleşme mimarisi tasarlanmıştır.

Verilerin cihazlar arasında aktarılması için MQTT protokolünün kullanılması planlanmıştır.

İnternet bağlantısı için farklı kullanım alanlarına göre:

- GSM
- LTE-M
- NB-IoT

teknolojilerinden yararlanılması düşünülmüştür.

## Bulut ve Dashboard

Sistem tarafından toplanan verilerin bulut ortamında saklanması ve kullanıcıların bu verilere uzaktan erişebilmesi amaçlanmaktadır.

Dashboard üzerinden aşağıdaki bilgiler takip edilebilir:

- Hayvan kimliği
- Beslenme zamanı
- Beslenme geçmişi
- Sistem durumu
- Enerji bilgileri
- Sensör verileri
- İstasyon kullanım geçmişi

## Enerji Yönetimi

Projenin özellikle kırsal ve elektrik altyapısının sınırlı olduğu alanlarda kullanılabilmesi amacıyla enerji otonomisine önem verilmiştir.

Bu nedenle sistemin güneş paneli ve batarya ile çalışması planlanmıştır.

Enerji yönetim sistemi:

- Güneş enerjisinden elektrik üretimi
- Bataryanın şarj edilmesi
- Sistem bileşenlerinin enerji ihtiyacının karşılanması
- Düşük enerji tüketiminin sağlanması

gibi görevleri yerine getirecek şekilde tasarlanmıştır.

## Kullanılan / Planlanan Teknolojiler

- Artificial Intelligence
- Edge AI
- MobileNetV2
- Convolutional Neural Networks (CNN)
- RFID
- Internet of Things (IoT)
- MQTT
- GSM
- LTE-M
- NB-IoT
- Cloud Computing
- Solar Energy
- Battery Management
- Embedded Systems

## Kullanım Alanları

Sistem aşağıdaki alanlarda kullanılabilecek şekilde düşünülmüştür:

- Hayvancılık işletmeleri
- Çiftlikler
- Kırsal alanlar
- Hayvan bakım merkezleri
- Barınaklar
- Otomatik besleme sistemleri
- Uzaktan hayvan takip sistemleri

## Projenin Amacı

Projenin temel amacı hayvanların kimliklendirilmesi, izlenmesi ve kontrollü beslenmesi süreçlerini otomatikleştiren akıllı bir istasyon tasarlamaktır.

RFID, yapay zekâ, IoT ve yenilenebilir enerji teknolojilerinin birlikte kullanılmasıyla düşük insan müdahalesiyle çalışabilecek otonom bir sistem oluşturulması hedeflenmiştir.

## Proje Sunumu

Projeye ait detaylı sistem tasarımı ve proje önerisi aşağıdaki sunum dosyasında bulunmaktadır:

[Proje Sunumunu Görüntüle](project-presentation.pdf)

## Proje Notu

Bu çalışma Girişimcilik dersi kapsamında hazırlanmış bir takım projesidir.

Proje bir sistem ve girişim fikri olarak tasarlanmıştır. Fiziksel prototip veya tamamlanmış ticari ürün niteliğinde değildir.
