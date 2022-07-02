# Week3Assignment

##	ARAŞTIRMA KONUSU (20 puan)

### Soru-1 : Symfony kullanmanın avantajları nedir? Kendi cümlelerinizle açıklayınız.

- Normal, pür php ile yazdığımız kodu daha kısa sürede yazabiliriz. Hazır kütüphaneleri tek satır kod ile projeye dahil edebiliriz. 
- Güvenlik açısından güncel olarak kendini tazeler örnek olarak xss, SQL injection gibi vs. saldırılara karşı koruma sağlar. 
- Front-end alanını (CSS, JS) dosyalarını kolaylıkla kontrol edebilir ve güncelleyebiliriz.
- Bir proje içerisinde birden çok yazılımcının entegre bir şekilde çalışmasını sağlar.

### Soru-2 : 

### Soru-3 : Yeni bir Symfony projesi oluşturmak için kullanılan composer komutu nedir? Alternatif bir komutla Symfony projesi oluşturabilir miyiz?
```
composer create-project symfony/skeleton:"6.1.*" my_project_directory
cd my_project_directory
composer require webapp         
```
Alternatif bir komutla symfony projesi oluşturabiliriz;
```symfony new my_project_directory --version="6.0.*" --webapp```

### Soru-4 : Laravel framework ve Symfony framework arasındaki temel farklardan iki tanesini yazınız.

Laravel, önbellek görünümleri için bir dizi birleşik API'ye sahipken, Symfony varsayılan olarak kaynak kodunu ve görünümleri önbelleğe alır bundan dolayı yükleme süresi symfony'de laravele kıyasla daha fazladır.

Symfony'nin desteklediği veri tabanları;
- MySQL
- Oracle
- Drizzle
- SQL Server
- PostgreSQL
- SQLite
- SAP Sybase SQL Anywhere

Laravel'in desteklediği veri tabanları;
- MySQL
- SQLite
- SQL Server
- PostgreSQL
         
##	SYMFONY UYGULAMASI OLUŞTURMA (80 puan)

[Proje ziplenmiş halde bu linkte](https://github.com/EnUygunPatikaBootCamp/week-3-Blackcloud00/blob/main/enuygunWeek3Work.zip)
