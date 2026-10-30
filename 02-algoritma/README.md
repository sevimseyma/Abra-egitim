# Temel Algoritma ve Akış Şemaları

Bu depoda temel algoritma yapılarını içeren sözde kodlar ve akış şemaları yer almaktadır.


############
1 ile 100 arasındaki (100 dahil) çift sayıları adım adım toplayıp sonucu ekrana yazdıran döngü algoritması.
A1: Başla
A2: x = 0, Toplam = 0 
A3: Toplam = x + Toplam
A4: x = x + 2
A5: x <= 100 ise A3'e git
A6: Toplam yaz
A7: Bitir

############
Klavyeden girilen 3 basamaklı sayının basamaklarını yazdırma algoritması
A1:Başla
A2:x sayısını giriniz
A3:x<100  || x>999 ise A2'ye git
A4:Yüzler=x\100
A5:Z=(x-(Yüzler*100))
A6:Onlar=Z\10
A7:Birler=(Z-(Onlar*10))
A8:Ekrana yazdır. Yüzler,Onlar,Birler
A9:Bitir

############
Haftalık 40 saatin altında ve 40 saati aşan çalışmalar için mesai saatini 2 katı katsayı ile hesaplayan koşullu algoritma.
A1:Başla
A2:Saat giriniz
A3:Saat ücreti giriniz
A4:Saat<=40 ise A6'ya git
A5:Saat=((Saat-40)*2)+40
A6:Maaş=Saat*Saat Ücreti
A7:Maaş ekrana yaz
A8:Bitir
