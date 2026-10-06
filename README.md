# BOZ213d01a02-IDLEnedenkisayolda
#"IDLE'ı neden sadece kısayolda çalıştırabiliyoruz?"

Aslında IDLE kendi başına bağımsız bir masaüstü uygulaması değildir. IDLE, Python'un standart kütüphanesi olan Lib içinde yer alan ve Tkinter arayüz aracıkullanılarak bizzat Python ile yazılmış bir scripttir. Adı idlelib olarak geçer.
Kısayola tıklandığında şu komutu çalıştırır: "pythonw.exe -m idlelib" Buradaki "pythonw.exe", standart CMD penceresini gizleyerek sadece görsel arayüzün açılmasını sağlayan özel bir çalıştırıcıdır. Bu yüzden onu standart bir program gibi değil, Python yorumlayıcısı üzerinden kısayolla kullanırız.

#"Python dosya sistemi nasıl biçimlenmiştir?"

Python bilgisayara kurulduğunda dosya sistemi şu hiyerarşiyle biçimlenir:

Kök Dizin: Yorumlayıcının ana beyni olan python.exe buradadır.
Lib: Python ile birlikte gömülü gelen standart kütüphaneleri barındırır.
Lib/site-packages: pip komutu ile internetten indirdiğin üçüncü parti tüm paketler doğrudan bu klasöre kurulur.
Scripts: pip gibi yardımcı araçların çalıştırılabilir dosyalarını tutar.
