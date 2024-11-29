# Siber Güvenlikte Yeni Standart: [RTBH](http://rtbh.com.tr)

## DDoS Saldırılarına Karşı Etkili Koruma

Günümüzün en büyük siber tehditlerinden biri olan Dağıtık Hizmet Reddi (DDoS) saldırıları, şirketlerin operasyonlarını kesintiye uğratabilir ve ağ güvenliğini ciddi şekilde riske atabilir. Avrupa Ağ ve Bilgi Güvenliği Ajansı (ENISA), siber saldırıları küresel ekonomiyi tehdit eden en büyük 5 riskten biri olarak tanımlıyor. 2024 yılı sonuna kadar bu saldırıların ekonomik etkisinin 9,5 trilyon Amerikan dolarına ulaşması bekleniyor.

[RTBH](http://rtbh.com.tr) (Remote Triggered Black Hole), bu saldırılara karşı geliştirilen yenilikçi bir savunma mekanizmasıdır. Bu teknoloji, kötü niyetli IP adreslerini tespit ederek, ağınızı bu tehditlerden izole eder ve güvenli bir ağ ortamı sağlar.

## RTBH: Nasıl Çalışır?

RTBH, BGP (Border Gateway Protocol) üzerinden çalışır ve kötü niyetli IP adreslerini hedef ağdan uzak tutar. Bu mekanizma, zararlı trafiği iptables gibi güvenlik araçlarıyla etkisiz hale getirerek, ağların performansını ve sürekliliğini korur.

✔ Gerçek Zamanlı İzleme: Trafik anında kontrol edilir.  
✔ Hedeflenmiş Engelleme: Zararlı trafiği filtreler.  
✔ Performans Koruması: Normal trafiği kesintiye uğratmaz.

## [RTBH.com.tr](http://rtbh.com.tr)

### [RTBH.com.tr](http://rtbh.com.tr) ile Güvenliğinizi Artırın

RTBH.com.tr, topluluk tarafından desteklenen 50'den fazla sensörden oluşan bir ağı yönetmektedir. Bu ağ, aşağıdaki tehdit türlerini tespit edebilmektedir:

- Çok Noktaya Yapılan DDoS Saldırıları
- Sıfır Gün Saldırıları
- Kaba Kuvvet Saldırıları
- Fidye Yazılımları
- Port Tarayıcıları

Toplanan veriler, list.rtbh.com.tr üzerinde derlenerek, ağ güvenliğini artırmak için kullanılabilir.

### Sensor Sponsorlarının Avantajları

RTBH sensörlerini barındıran kuruluşlar şu faydaları elde eder:

- **Gerçek Zamanlı İzleme:** Zararlı trafiği anında tespit etme.
- **Detaylı Raporlama:** Ağ güvenliği hakkında kapsamlı bilgiye erişim.
- **Artan Güvenlik:** Proaktif tehdit önleme mekanizmaları.

## RTBH BGP Sunucusu: Kolay Kurulum

RTBH BGP sunucusu, Docker Hub'da barındırılmaktadır ve kolayca aktif edilebilir:

\`

docker pull alptekinsunnetci/rtbh:istanbul
docker run -d --restart unless-stopped -p 179:179 alptekinsunnetci/rtbh:istanbul
\`

## Etkileyici Sonuçlar

RTBH.com.tr, 2024 yılı itibarıyla 2.000.000'den fazla zararlı IPv4 adresi tespit etmiştir. Bu başarı, sistemin proaktif savunma kapasitesinin bir göstergesidir.

En çok hedef alınan portlar arasında:
- 23
- 445
- 22
- 1433
- 8080

## IP Adresimi Listeden Nasıl Çıkartabilirim?

IP adresinizi manuel bir başvuru yoluyla listeden çıkarmanız mümkün değildir. Ancak, 7 gün boyunca zararlı faaliyet göstermediğiniz takdirde, sistem IP adresinizi otomatik olarak listeden kaldıracaktır. Bununla birlikte, geçmişe dönük ihlalleriniz arşivlenmeye devam edecek ve bu veriler gelecekteki analizler için kullanılacaktır.

## RTBH.com.tr Servisi Lisans Koşulları

RTBH.com.tr servisi, kişisel kullanıcılar, kurumlar ve kuruluşlar tarafından ücretsiz olarak kullanılabilir. Kullanıcılar, servisin sunduğu hizmetlerden herhangi bir ücret ödemeden faydalanabilirler.

Ancak, servisten elde edilen verilerin doğrudan veya alternatif bir ürün üzerinden ticari amaçlarla satılması yasaktır. Verilerin ticari kullanımına yönelik herhangi bir işlem yapabilmek için önceden izin alınması gerekmektedir.

Bu lisans, yalnızca kişisel ve kurumsal kullanım hakkı tanımaktadır. Ticari kullanım, lisans sahibinin onayına bağlıdır ve izinsiz ticari kullanım durumunda yasal işlem başlatılabilir.
