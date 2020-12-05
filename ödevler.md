# Lazy Loading
Lazy Loading, sayfada yer alan bir ögenin ihtiyaç duyulmadığı takdirde çağrılmaması prensibi ile çalışır yani bir nesne örneğinin gerçekten ihtiyaç duyulacağı ana kadar
alınmaması ve bekletilmesi amacıyla kullanılır. Bu yöntemde veriler sorguya bağlı olarak çekilir ve veri setinin içindeki tüm dataları yüklemek yerine kullanılacağı
an tekrar sorgu atar ve veriyi çeker.  
# SQLite ve LocalDB kavramlarını karşılaştırınız.
Sqlite, bir veritabanı kütüphanesidir. Sqlite herhangi bir ana sunucu işlemi gerektirmez. Veritabanına erişmek için sunucuya istek göndermek ve sonuç almak için ara 
işlem iletişimi kurmak gerekmez. Bu program doğrudan diskteki veritabanı dosyalarını okur ve yazar. Bu durumun ana avantajı; kurma, yapılandırma, başlatma, yönetme ve 
sorun giderme işlemleri için ayrı bir sunucu işlemi yapmaya gerek olmamasıdır. Ancak bu durumun bir dezavantajı da vardır. Sunucu kullanan veritabanları genellikle daha güvenlidir.

Localdb Microsoft'un SQL Express'in yeni versiyonuna verdiği isimdir. SQL Express (localdb) veya SQLite gibi programlar genellikle bir veri dosyanı size SQL formatında sunar. 
Bu sayede bir SQL sunucusu (MSSQL, MySQL veya Oracle) kurmaya gerek kalmadan SQL üzerinde çalışabilinir. Bir sunucunun yeteneklerine sahip değildir fakat kod geliştirmeyi 
kolaylaştırır.

