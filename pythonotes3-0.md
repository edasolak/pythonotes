# Python Veri Tipleri 

•Numbers <br>
•String <br>
•List <br>
•Set <br>
•Dictionary <br>
•Tuple <br>

----------------------------------------------------------------------------

•Numbers <br>

Binary	'0b' yada '0B' şeklinde gösterilir.Örn: print(0b1101011),Çıktı:107 <br>
Octal	'0o' yada '0O' şeklinde gösterilir.Örn: print(0xFB + 0b10),Çıktı:253 <br>
Hexadecimal	'0x' yada '0X' şeklinde gösterilir.Örn: print(0o15),Çıktı:13 <br>

import decimal <br>
print(0.1) #Çıktı:0.1 <br>
print(decimal.Decimal(0.1)) #Çıktı:Decimal('0.1000000000000000055511151231257827021181583404541015625')<br>

from decimal import Decimal as D <br>
print(D('1.1') + D('2.2')) #Çıktı:Decimal('3.3') <br>
print(D('1.2') * D('2.50')) #Çıktı:Decimal('3.000')<br>

import fractions<br>
print(fractions.Fraction(1.5)) #Çıktı:3/2 <br>
print(fractions.Fraction(5)) #Çıktı:5 <br>
print(fractions.Fraction(1,3) #Çıktı:1/3 <br>

import fractions <br>
print(fractions.Fraction(1.1)) #Çıktı:2476979795053773/2251799813685248 <br>
print(fractions.Fraction('1.1')) #Çıktı:11/10 <br>


---------------------------------------------------------------------------------

•String <br>

 x = "mystring" <br>
 m y s t r i n g <br>
 0 1 2 3 4 5 6 7 8 <br>
-8-7-6-5-4-3-2-1 <br>

x[0:4] -> 0,1,2,3. karakter <br>
x[0:] -> ilk karakter <br>
x[-1] -> son karakter <br>
x[:] -> bütün karakterler <br>


string.upper()    #harfleri büyük harf yap <br>
string.lower()    #harfleri küçük harf yap <br>
string.capitalize() #ilk harfi büyük yap <br>
string.title()    #kelimlerin'in ilk harfini büyük yap <br>
string.swapcase() #string'deki küçük harfleri büyük,büyük harfleri küçük yap <br>
string.strip()    #boşlukları sil <br>
string.lstrip()   #string'in solundaki boşlukları sil <br>
string.rstrip()   #string'in sağındaki boşlukları sil <br>
string.split()    #kelimeleri böl <br>
string.split(',') #kelimeleri'leri virgülle böl <br>
string.count('l')   #string'deki l sayısı <br>
string.find('ing') # stringde kelime arar varsa ilk karakterin index'ini döndürür. <br>
string.index("o")  # stringde harf arar varsa index döndürür <br>
":".join(string)  # her karakter arasına : ekler <br>
" ".join(string)  # her karakter arasına boşluk ekler <br>
len(string)   #stringin'in uzunluğunu bulur <br>

--------------------------------------------------------------------------------

•Liste <br>
mylist=[] <br>
mylist2=[1,2,3] #Erişirken,mylist2[1]=2 <br>
mylist3=[1,2,"merhaba",2.3] #Erişirken,mylist3[2]="merhaba" <br>
my_list4=["Ola", [8, 4, 6], ['E']] #Erişirken,mylist4[0]="Ola",mylist4[0][1]="l",mylist4[1][1]=4 <br>
mylist5=[1,2,3,4] #Erişirken mylist5[-2]=3 <br>

Liste ile ilgili methodlar <br>
append() - sonuna eleman ekler <br>
extend() - listenin sonuna başka bir liste ekler <br>
insert() - indexle eleman ekler <br>
remove() - listeden eleman siler.Paremetre olarak değer alır ve o değeri siler <br> 
pop()    - belirtilen dizindeki bir elemanı siler ve sildiği elemanı döndürür <br>
clear()  - listeyi temizler <br>
index()  - gönderilen indexteki elemanı verir <br>
count()  - gönderilen değerden listede kaç tane var <br>
sort()   - sıralar <br>
reverse() - listeyi ters çevirir <br>
copy()    - listenin kopyasını alır <br>
del listeadı[index] -listede index ile eleman siler <br>

Liste ile ilgili Built-in Functions <br>
all()	-listenin bütün elemanları True döndürüyorsa ise True döndürür<br>
any()	-listenin hiçbir elemanı True döndürmüyor ise True döndürür<br>
enumerate()	-numaralandırılmış bir nesneyi döndürür<br>
len() -eleman sayısını döndürür <br>
list()	-tuple, string, set, dictionary yapılarını listeye çevirir <br>
max()	-listedeki max değeri döndürür<br>
min()	-listedeki min değeri döndürür<br>
sorted() -sıralanmış listeyi döndürür<br>
sum()	-listedeki elemanların toplamını döndürür <br>











  






