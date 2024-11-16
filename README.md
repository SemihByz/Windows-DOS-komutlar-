# En İyi 25+ Windows CMD Komutları
## 1. Dizin Gezintisi ve Yönetimi Windows CMD Komutları
Bu temel Windows CMD komutlarıyla dizinlerde gezinin ve klasör yapılarını verimli bir şekilde yönetin.
### 1. cd "klasör"

   Geçerli dizininizi değiştirir.
   + cd ..
   
   Geçerli dizinin bir altına iner.
   + cd/

   Geçerli dizinin köküne iner.

   ![Relative](/gorseller/1.png)

### 2. dir
Bir dizindeki dosyaların ve alt dizinlerin listesini görüntüler.

![Relative](/gorseller/2.png)

### 3. mkdir "isim" (veya md)
Geçerli dizinde yeni klasör oluşturur.

![Relative](/gorseller/3.png)

### 4. rmdir "isim"
Geçerli dizinde klasör siler.

![Relative](/gorseller/4.png)

### 5. tree
Geçerli dizinde bulunan bütün klasör ağacını gösterir.

![Relative](/gorseller/5.png)

## 2. Ağ Yapılandırması ve Tanılama Windows CMD Komutları
Ağ yapılandırma komutları, sorun giderme veya yeni ağ bağlantıları kurma sırasında faydalıdır. İşte ağ ile ilgili görevleri halletmenize yardımcı olacak bazı temel Windows yönetici CMD komutları.
### 1. ipconfig
Tüm geçerli TCP/IP ağ yapılandırma değerlerini görüntüler ve Dinamik Ana Bilgisayar Yapılandırma Protokolü (DHCP) ve Etki Alanı Adı Sistemi (DNS) ayarlarını yeniler.

![Relative](/gorseller/6.png)

### 2. ping "adres"
Belirli bir ağ cihazına ulaşma yeteneğini test eder.

![Relative](/gorseller/7.png)

### 3. netstat
Etkin bağlantıları, portları, Ethernet istatistiklerini ve IP yönlendirme tablosunu görüntüler.

![Relative](/gorseller/8.png)

### 4. netsh "modifikasyon"
Ağ ayarlarının hemen hemen her yönünün yapılandırılmasına olanak tanır.

![Relative](/gorseller/9.png)

### 5. hostname
Bilgisayarın ağ adını göstererek ağ tanımlamasına ve sorun gidermeye yardımcı olur.

![Relative](/gorseller/10.png)

### 6. pathping "adres"
Ping ve tracert özelliklerini birleştirerek ağ rotaları ve gecikme hakkında daha detaylı bilgi sağlar.

![Relative](/gorseller/11.png)

### 7. getmac
Ağ kartının MAC adresini görüntüler.

![Relative](/gorseller/12.png)

## 3. Sistem Bilgileri Windows Cmd Komutları
Kapsamlı sistem bilgilerini toplamak, güvenli modda sorun giderme, sistem izleme ve Windows kurulumunuzun optimum şekilde çalıştığından emin olmak için çok önemlidir. Ayrıntılı sistem bilgilerine erişmenizi sağlayan bazı temel Windows CMD komutları şunlardır.

### 1. systeminfo
İşletim sistemi yapılandırması, donanım ayrıntıları ve ağ bilgileri de dahil olmak üzere sisteminizin ayrıntılı bir genel görünümünü sağlar.

![Relative](/gorseller/13.png)

### 2. winver
Çalıştırdığınız Windows sürümünü hızlı bir şekilde kontrol eder.

![Relative](/gorseller/14.png)

### 3. tasklist 
Şu anda çalışan tüm işlemleri, İşlem Kimlikleri (PID) ile birlikte listeler.

![Relative](/gorseller/15.png)

### 4. taskkill /PID "pip numarısı" /F
Yanıt vermeyen veya çok fazla kaynak tüketen işlemleri zorla sonlandırır.

![Relative](/gorseller/16.png)

## 4. Disk Yönetimi Windows Cmd Komutları
Disk yönetimi komutları, depolama kaynaklarınızı doğrudan komut satırından yönetme esnekliğini sunarak grafiksel kullanıcı arayüzü araçlarına güçlü bir alternatif sunar. İşte bazı temel Windows CMD komutları ve işlevleri.

### 1. diskpart
Disk bölümlerini yönetmek için bir araç.

![Relative](/gorseller/17.png)

### 2. chkdsk
Diskte hata olup olmadığını denetler ve dosya sistemini onarır.

![Relative](/gorseller/18.png)

### 3. list disk
Bilgisayardaki tüm diskleri görüntüler.

![Relative](/gorseller/19.png)

### 4. select disk "numara"
İşlemleri yapmak istediğiniz diski seçer.

![Relative](/gorseller/20.png)

### 5. clean
Seçilen diskteki tüm bölümleri kaldırır.

![Relative](/gorseller/21.png)
