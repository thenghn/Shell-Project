

## Dosyaların ve Dizinlerin Listesi

grup3</br>
├── sau </br>
│   ├── shell.c         #Kabuk kaynak kod dosyası</br>
│   └── test             #Test </br>
├── 1.png       # Program çıktısı</br>
├── 2.png       # Program çıktısı</br>
├── 3.png       # Program çıktısı</br>
└── README.text #Readme metin dosyası</br>

## Programı Derlemek İçin Talimatlar
`cd  Masaüstü/grup3/sau`</br>
`gcc shell.c -o test `
## Programları / Komut Dosyalarını Çalıştırmak İçin Talimatlar
` ./test `
## Geliştirme Sırasında Karşılaşılan Zorluklar
Projeyi geliştirme sırasında uygun kaynakları bulup özümseme süreci karşılaştığımız zorlukların başında yer almaktadır. Yerli ve yabancı birçok kaynağın taranmasına rağmen bazı sorulara cevap bulmakta epey güçlük çekilmiştir. Özellikle, proje dosyasındaki 5.bölümde yer alan built-in komutların yazımı sırasında özellikle `showpid` ve `cd`'yle ilişkili karşılaşılan bazı hatalar olmuş ve bu hataların büyük çoğu çözüme ulaştırılmıştır. C kitaplığı çağrısı `memset()`  kullanımında sıkıntılarla karşılaşılmıştır. Bu konu üzerine birçok inceleme ve deneme yapılsa da showpid ile `memset()` fonksiyonu birlikte çalışmamaktadır. Kabuk tarafından oluşturulmuş en az 5 yavru proses pid'sinin ekrana yazdırılmasıyla ilgili sınırlandırma da projenin geliştirilmesi sırasında zorlandırıcı bir detay olarak karşımıza çıkmıştır. 
## Programın Yazımında Kullanılan Yardımcı Kaynaklar
[1.Kaynak](http://www.cse.csusb.edu/tongyu/courses/cs460/notes/intro.php "1.Kaynak")</br>
[2.Kaynak](https://linux.die.net/man/3/execvp "2.Kaynak")</br>
[3.Kaynak](https://iq.opengenus.org/chdir-fchdir-getcwd-in-c/ "3.Kaynak")</br>
[4.Kaynak](https://stackoverflow.com/questions/28502305/writing-a-simple-shell-in-c-using-fork-execvp "4.Kaynak")</br>
[5.Kaynak](https://www.geeksforgeeks.org/making-linux-shell-c/ "5.Kaynak")</br>
[6.Kaynak](https://github.com/pranjalbajaj/NEKTech-Linux-Shell "6.Kaynak")</br>
[7.Kaynak]( https://brennan.io/2015/01/16/write-a-shell-in-c/ "7.Kaynak")
