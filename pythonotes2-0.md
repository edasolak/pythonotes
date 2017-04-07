•Python'da Döngüler ve Karar Yapılar
•if a < b : <br>
•if True:<br>
•elif:  #else if<br>
•else:  <br>
•for i in range(1, 5):#range(1,5)->1'den 5'e kadar->1,2,3,4 #range(1,5,2)->1'den 5'ekadar 2 artışla->1,3 #range(3) = range(0,3)<br>
•for val in "kelime":    
•break<br>
•continue<br>
•while a < b: <br>
•while True: <br>
 
•Python'da Fonksiyon<br>

-def myfonk():<br>
-def myfonk(name1,name2): #argument olarak iki parametre alan fonksiyon<br>
-def myfonk(*names): #argument olarak tuple alan fonksiyon<br>
-def myfonk(message, times=1): #fonksiyon içinde parametre değeri verilebilir eğer fonksiyon çağrılırken sadece 1.parametre gönderilirse times parametresi 1 olur.Eğer fonksiyon çağrılırken iki parametre gönderilirse times parametresi gönderilen değerdir.

-double = lambda x: x * 2 #lambda fonksiyonu(tek ifadeli fonksiyonlar),<br>
örnekteki double fonksiyonu double(deger) şeklinde çalışır ve gelen değeri, ikiyle çarparak döndürür.<br>

•Pyhthon'da Docstring
Python, dokümantasyon dizeleri olarak adlandırılan bir özelliğe sahiptir.DocStrings, programı daha iyi belgelemenize yardımcı olması ve anlaşılmasını kolaylaştırır.Fonksiyon tanımlandıktan sonra üç tırnaklar içine yazılan açıklama,docstringdir. <br>

def myfonk(x, y):<br>
&nbsp;&nbsp;&nbsp;&nbsp;'''Bu fonksiyon şunu<br>
&nbsp;&nbsp;&nbsp;&nbsp;yapar.''' 
    
print(myfonk.<label>__doc__</label>) #şeklinde fonksiyonun docstringini görülebilir.    

-Modüllerin Docstringleri

<label>>>> import mymodule<br>
<label>>>> help(mymodule.MyClass)<br>
class'ın docstringi<br>

<label>>>> help(mymodule.MyClass.my_method)<br>
methodun docstringi<br>

<label>>>> help(mymodule.my_function)<br>
fonksiyonun docstringi<br>

•Modüller




    





