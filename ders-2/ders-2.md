Ders 2: Termux'u indirmek ve kurulum sonrası yapılacaklar.
=
#### Dersin kazanımları:  
#### Termux'u kurma, Play Store'daki Termuxlar F-Droid'deki Termux'un farkları, Gelecek dersler için gereken paketleri indirme.
---
## Bölüm 1: Play Store'daki Termux'la F-Droid'deki Termux'un farkları  
![image](https://github.com/13egliB/termux-temel-egitim/blob/main/ders-2/fdroid-termux-version.png "F-Droid")  
![image](https://github.com/13egliB/termux-temel-egitim/blob/main/ders-2/playstore-termux-version.png "Play Store")  
Ekran görüntülerinden de anlaşılacağı şekilde Play Store'daki Termux F-Droid'daki Termux'tan geri kalmıştır ve bunun sonucunda indireceğiniz çoğu paket bozuk çalışacaktır.  

## Bölüm 2: Termux'u kurma  
Neden Termux'u Play Store'dan indirmememiz gerektiğini de anladığımıza göre kuruluma geçebiliriz. Termux'u kurabilmemiz için öncelikle [F-droid'i](https://f-droid.org) indirmeniz gerekiyor.  
![image](https://github.com/13egliB/termux-temel-egitim/blob/main/ders-2/fdroid-download.png "F-Droid'i indir")  
F-Droid'i indirdikten sonra F-Droid'deki arama kısmına girip Termux diye aratmanız gerek.  
![image](https://github.com/13egliB/termux-temel-egitim/blob/main/ders-2/termux-download.png "Termux'u indir")  
Ekte işaretlediğim Termux'u indirdin.  

## Bölüm 3: Gelecek dersler için gereken paketleri indirme  
Termux'u indirdiğimize göre gelecek derslerimiz için gerekli olan paketleri indirelim. Herşeyden önce bu 3 komutu çalıştırmalıyız:  
1. Komut: ```termux-setup-storage``` bu komut Termux'a dosya sistemimize erişim izni verecektir.  
   
2. Komut: ```termux-change-repo``` bu komut Termux paketlerini indireceğimiz sunuculara bağlanmamızı sağlayacaktır.  

3. Komut: ```pkg update -y``` bu komut sunuculara bağlandıktan sonra tüm indirilebilir paketlerin listesini verecektir.  

Bu 3 komutu çalıştırdıktan sonra ```pkg install -y micro python3 python2 python-pip openssh git toilet neofetch busybox dnsutils wget curl zip unzip man``` bu komutu kullanarak gelecek derslerde kullanacağımız paketleri yüklemiş oluruz.
