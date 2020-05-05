## Kitap Referans Takip Programı

#### 1. Programın ana amacı :
Kitapların referanslarını kontrol ve takibini kolaylaştırmaktır. Kitap ekleme alanındaki verileri referans ekleme alanında kitap adını aktarıp, kitaplara istediğimiz referans türüne göre kayıt tutabiliyoruz ve sorgulama kolaylığı sağlıyoruz.
#### 2. Program Nesneleri ve İlişkileri :
#### 2.1	“kitap”, “dergi” ve “web” nesnelerinin temel amacı
Nesneleri Entity Beans teknolojisinin sağladığı fayda ile kolaylıkla veritabanı ile ilişkilendiriyoruz.
#### 3. Ekranlar ve temel bileşenleri
#### 3.1	Kitap Ekleme Ekranı 
•	Ekranda veritabanına erişim JDBC teknolojisi kullanılarak oluşturulmuştur.<br>
•	Text alanlarından alınan girişler veritabanında tutularak aynı anda tabloya aktarılır.<br>
![1](https://github.com/ibrahimyyildirim/BookReferenceManagement/blob/master/img/1.png)<br>
#### 3.2	Referans Ekleme Ekranı
•	Ekranda veritabanına erişim Entity Beans teknolojisi kullanılarak sağlanmıştır.<br>
•	Veriler veritabanında ki referans türlerine göre tablolara kaydedilir ve aynı anda jTable ekranına aktarılır.<br>
![2](https://github.com/ibrahimyyildirim/BookReferenceManagement/blob/master/img/2.png)<br>
#### 3.3	Referansları Gör (Sorgulama) Ekranı 
•	Kitaplara ait isteğimiz referans türünü tek bir tür veya daha fazla tür şeklinde görebilme.<br>
•	Referans bazında toplu olarak sorgulama yapabilme.<br>
![3](https://github.com/ibrahimyyildirim/BookReferenceManagement/blob/master/img/3.png)<br>
#### 4. Çapraz İşlemler 
•	Kitap ekleme ekranından veritabanındaki kayıtlar JDBC teknolojisi kullanılarak ile tüm ekranlardan aynı anda silinir.<br>
![3](https://github.com/ibrahimyyildirim/BookReferenceManagement/blob/master/img/4.png)<br>
