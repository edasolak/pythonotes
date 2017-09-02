•Python'da Döngüler ve Karar Yapıları<br>
•if a < b : <br>
•if True:<br>
•elif:  #else if<br>
•else:  <br>
•for i in range(1, 5):<br>
#range(1,5)->1'den 5'e kadar->1,2,3,4 <br>
#range(1,5,2)->1'den 5'ekadar 2 artışla->1,3 <br>
#range(3) = range(0,3)<br>
•for val in "kelime": <br>  
•break<br>
•continue<br>
•while a < b: <br>
•while True: <br>

-------------------------------------------------------------------------------------
 
•Python'da Fonksiyon<br>

-def myfonk():<br>
-def myfonk(name1,name2): #argument olarak iki parametre alan fonksiyon<br>
-def myfonk(*names): #argument olarak tuple alan fonksiyon<br>
-def myfonk(message, times=1): #fonksiyon içinde parametre değeri verilebilir eğer fonksiyon çağrılırken sadece 1.parametre gönderilirse times parametresi 1 olur.Eğer fonksiyon çağrılırken iki parametre gönderilirse times parametresi gönderilen değerdir.<br>

-double = lambda x: x * 2 #lambda fonksiyonu(tek ifadeli fonksiyonlar),<br>
örnekteki double fonksiyonu double(deger) şeklinde çalışır ve gelen değeri, ikiyle çarparak döndürür.<br>

----------------------------------------------------------------------------------------

•Pyhthon'da Docstring<br>
Python, dokümantasyon dizeleri olarak adlandırılan bir özelliğe sahiptir.DocStrings, programı daha iyi belgelemenize yardımcı olması ve anlaşılmasını kolaylaştırır.Fonksiyon tanımlandıktan sonra üç tırnaklar içine yazılan açıklama,docstringdir. <br>

def myfonk(x, y):<br>
&nbsp;&nbsp;&nbsp;&nbsp;'''Bu fonksiyon şunu<br>
&nbsp;&nbsp;&nbsp;&nbsp;yapar.''' 
     
<label>print(myfonk.&#95;&#95;doc&#95;&#95;) #şeklinde fonksiyonun docstringini görülebilir.</label><br> 

-Modüllerin Docstringleri

<label>>>> import mymodule<br>
<label>>>> help(mymodule.MyClass)<br>
class'ın docstringi<br>

<label>>>> help(mymodule.MyClass.my_method)<br>
methodun docstringi<br>

<label>>>> help(mymodule.my_function)<br>
fonksiyonun docstringi<br>

----------------------------------------------------------------------------------------------

•Modüller<br>
-Temelde zaten yazılı olan bir dosyalardır.

import sys #sys modülüne erişim,örn: >>>sys.version

from sys import version #sys modülünde version'a erişim,örn:>>>version()

from sys import &#42; #sys modülündeki tüm sınıf ve fonksiyonlara başına modülün ismini yazmadan erişim,örn:>>>version()<br>

import sys as s #sys modülünü artık s ismi ile kullanabiliriz. örn:>>>s.version

<label>>>> dir(sys) #sys modülünün sahip olduğu nitelikleri(fonksiyonlar,değişkenler) gösterir.

