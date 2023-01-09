
# Cpanel-Outomatic-Deploy

1- Öncelikle 'Cpanel Ftp Acounts' bölümünden bir adet FTP hesap oluşturmalısınız.

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

2- Oluşturduğunuz FTP hesap bilgileri 'Configure FTP Client' sekmesi altında gösterilir. 

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

3- Github hesabımızda yeni bir repo oluşturuyoruz.

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

4- Cpanel'de  oluşturduğumuz FTP hesap ayarlarını 'New repository secret' sekmesinde kaydediyoruz.
 
![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

5- FTP_PASSWORD : FTP hesabınızın şifresi.

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

6- FTP_SERVER : FTP hesabınızın sunucu bilgisi.

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

7- FTP_USERNAME : FTP hesabınızın kullanıcı adı.

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

8- Actions sekmesinden "set up workflow yourself" alanı ile kendi deploy kodumuzu oluşturalım.

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

9- Actions Code.txt dosyası içindeki kodu buraya kopyalayalım ve hangı branch ile işlem yapılması gerekli ise değiştirelim.

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

10- Son olarak Acitons bölümünden işlemlerimizin başarılı olup olmadığını kontrol edelim.
    Eğer başarısız ise FTP nilgilerini kontol edin.

![img](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)