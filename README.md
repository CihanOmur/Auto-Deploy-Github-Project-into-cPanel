
# Cpanel-Outomatic-Deploy

1- Öncelikle 'Cpanel Ftp Acounts' bölümünden bir adet FTP hesap oluşturmalısınız.

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/1.png)

2- Oluşturduğunuz FTP hesap bilgileri 'Configure FTP Client' sekmesi altında gösterilir. 

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/2.png)

3- Github hesabımızda yeni bir repo oluşturuyoruz.

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/3.png)

4- Cpanel'de  oluşturduğumuz FTP hesap ayarlarını 'New repository secret' sekmesinde kaydediyoruz.
 
![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/4.png)

5- FTP_PASSWORD : FTP hesabınızın şifresi.

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/5.png)

6- FTP_SERVER : FTP hesabınızın sunucu bilgisi.

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/6.png)

7- FTP_USERNAME : FTP hesabınızın kullanıcı adı.

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/7.png)

8- Actions sekmesinden "set up workflow yourself" alanı ile kendi deploy kodumuzu oluşturalım.

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/8.png)

9- Actions Code.txt dosyası içindeki kodu buraya kopyalayalım ve hangı branch ile işlem yapılması gerekli ise değiştirelim.

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/9.png)

10- Son olarak Acitons bölümünden işlemlerimizin başarılı olup olmadığını kontrol edelim.
    Eğer başarısız ise FTP nilgilerini kontol edin.

![img](https://github.com/CihanOmur/Auto-Deploy-Github-Project-into-cPanel/blob/main/images/10.png)