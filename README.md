# CYBER SECURITY ATTACKS VERİ ANALİZİ

![cyber attack](https://github.com/user-attachments/assets/05507226-494e-4240-8325-ff9e625978b5)

Cyber Security Attacks veri seti saldırı zamanını,Kaynak Ip ,Hedef Ip,Kaynak Port,Hedef Port,Protokol,Paket Boyutu,Paket Tipi,Trafik Tipi,Taşınan Veri,
Saldırı Tipi,Yapılan Eylemler,Saldırının Önem Seviyesi,Saldırı Yapılan Ülkeler gibi verileri içeren veri setidir. Veri setine ulaşmak için aşağıda verilen Kaggle bağlantısını takip edebilir ve değişkenler hakkındaki bilgilere aşağıdan ulaşabilirsiniz.

Cyber Security Attacks Veri Seti: [https://www.kaggle.com/datasets/mlomuscio/pokemon](https://www.kaggle.com/datasets/teamincribo/cyber-security-attacks)

#### Değişkenler
* Timestamp: Saldırı Tarihini ve saatini belirtir.
* Source IP Address: Kaynak Ip adresini belirtir.
* Destination IP Address: Hedef Ip adresini belirtir.
* Source Port: Kaynak bağlantı noktasını belirtir.
* Destination Port: Hedef bağlantı noktasını belirtir.
* Protocol: İnternet protokolünü belirtir.IP, paket teslim görevini paket başlıklarındaki IP adreslerine dayalı olarak kaynak adresten hedef adrese doğru gerçekleştirir
* Packet Length: Gönderilen paketin boyutunu belirtir.
*Packet Type: protokol takımı, bilgisayarlar ve ağ cihazları arasında iletişimi sağlamak amacıyla standart olarak kabul edilmiş kurallar dizisidir. Bu kurallar dizisi temel olarak verinin ağ üzerinden ne şekilde paketleneceğini ve iletilen veride hata olup olmadığının nasıl denetleneceğini belirlemektedir. 
* Traffic Type:  tüm İnternet içindeki veya onu oluşturan ağların belirli ağ bağlantılarındaki veri akışıdır.
* Payload Data: iletilen verilerde gerçek istenilen mesajın parçasıdır.
* Malware Indicators: Zararlı yazılım, kötü amaçlı yazılım anlamına gelmektedir.
* Anomaly Scores: Bireysel bir veri örneği eğer diğer normal verilerden uzaktaysa bu bir anomali veridir.
* Alerts/Warnings: Acil durum uyarı mesajları
* Attack Type: Bilgisayar sistemlerine yetkisiz erişim sağlama ve verileri çalma, değiştirme veya yok etme girişimleridir.
* Attack Signature: Bir web uygulamasına ve bileşenlerine yönelik saldırıları veya saldırı sınıflarını tanımlayan kurallar veya kalıplardır.
* Action Taken: Gerçekleştirilen eylemleri belirtir.
* Severity Level: Saldırının önem düzeyini belirtir.
* User Information: Kullanıcı Bilgisini ifade etmektedir.
* Device Information: Kullanılan cihaz hakkındaki bilgileri içermektedir.
* Network Segment: Bir bilgisayar ağının bir bölümüdür. Bir segmentin niteliği ve kapsamı, ağın niteliğine ve uç istasyonları birbirine bağlamak için kullanılan cihaza veya cihazlara bağlıdır.
* Geo-location Data: İnternet'e bağlı bir cihazın coğrafi konumunu belirtmektedir.
* Proxy Information: İnternet'e erişim sırasında kullanılan bir ara sunucudur.
* Firewall Logs: Ağın çevresindeki güvenlik tehdidi girişimleri ve güvenlik duvarına gelen-giden trafiğin yapısı hakkında birçok bilgiyi ortaya koyar.
* IDS/IPS Alerts:  IDS güvenlik sistemlerinin amacı zararlı hareketi tanımlama ve loglama yapmaktır. IPS ise ağ trafiğiniz içerisindeki zararlı hareketleri veya zararlı bağlantıların tespiti ile birlikte önlenmesi için kullanılan güvenlik sistemleridir.
* Log Source: internet vb. ağlarda istek yapan cihaz ile istek yapılan cihazın arasındaki trafik bilgilerinin kayıt altına alınmasıdır.Loglama iletişim sağlayan tüm elektronik cihazlar için önemli olduğu gibi güvenlik açısında da siber olayların tespiti için zorunludur.

## Temel Bulgular ve İşlemler
* Veri seti toplamda 25 sütun ve 40000 kayıt içermektedir.
* Source Port,Destination Port,Packet Length,Anomaly Scores sütunları numerik değere sahip, kalan sütunlar object değişkenler olarak tespit edilmiştir.
* Saldırı Seviyeleri Low,Medium ve High olarak tespit edilmiştir.
* High seviyeli saldırıları en fazla durduran ülke Jharkhand olarak tespit edilmiştir.
* Saldırı türleri DDos,Intrusion ve malware olarak gruplandırılmıştır.
* En fazla saldırı türü DDos olmakla beraber en yüksek seviyeli saldırı da yine DDos olduğu gözlemlenmiştir.
* Alınan eylemler Ignore(%33.2),Blocked(%33.8), Logged(%33.0) olarak gruplandırılmakla beraber saldırıların %33.8 'i ile bloklanma oranı en fazla olan eylem olarak gözlemlenmiştir.
* Saldırı yapılan ülke sayısı 28 olarak gözlemlenmiştir.
* En fazla saldırı yapılan ülke Manipur olarak gözlemlenmiştir.
* Saldırıların yıllara göre dağılımına bakıldığında en fazla saldırının 2022 ' de yapıldığı tespit edilmiştir.

Kaggle linki: https://www.kaggle.com/code/fatmaertrk/cyber-security-attacks-veri-analizi

Global AI Hub Ekibine bizlere vermiş oldukları desteklerinden ötürü çok teşekkür ederim.
