# Python Temelleri
•Python Teknolojileri <br/>
Python paket yöneticisi -> pip (Python modüllerini kolayca yüklememizi sağlar) <br/>
Python Web Frameworkleri -> djhango,web2py,flask,grok,tornado,turbogears.. <br/>
Python Debugging araçları -> Pychecker,pudb,pdb,pylint.. <br/>
Python Shell ->ipython,dreampie.. <br/>
Python Game -> PyWeek,Pygame.. <br/>
Python CMS -> Skeletonz,Mezzanine,Ikaro,Django.. <br/>
Python GUI frameworkleri -> Tkinter,PyQT,WxPython.. <br/>

--------------------------------------------------------------------------------

•Python yükle,Python çalıştır.<br/>
Bilgisayarda hazırda kurulu bir Python var mı? -> terminal ekranında : python -V <br/>
Varsa:terminalde python yazarak pyhon etkileşimli kabuğa gidilir.(Python etkileşimli kabuk Python kodlarını<br/> 
çalıştırmamıza yarayan katmandır.)<br/>
Yoksa : sudo apt-get install python3 (Debian tabanlı Linux dağıtımları için)<br/>
python yazarak : >>> (etkileşimli kabuk),etkileşimli kabuktan çıkmak için : Ctrl+D<br/>
chmod +x firstprog.py -> python kodumuza çalıştırma yetkisi verir.<br/>
Python için editör : PyCharm(kurulum için-> https://www.jetbrains.com/pycharm-edu/quickstart/installation.html#linux)<br/>

--------------------------------------------------------------------------------

•Değişkenler ve Veri Tipleri

>>>5+5 
10
>>>'5''5'
55
>>>4*5
20
>>> '4'*5
44444
>>> "a"+"b"
ab
>>>"a"*3
aaa
>>>3**2
9

>>>x=1==1
True

>>>sayi = 1 + 2+ \
...3 + 4
>>>sayi
10

>>>sayi2 = (1 + 2 +
...3 + 4)
>>>sayi2
10

>>>a=1;b=1;c=1 #kullanılabilir
>>>a, b, c = 5, 3.14, "Ola" #kullanılabilir
>>>x = y = z = "same"  #kullanılabilir

-Degişken ismi olarak kullanamayacaklarımız: False,class,finally,is,return,None	 continue,for,lambda,try,True,def,from,nonlocal,	while,and,del,global,not,with,as,
elif,if,or,yield,assert,else,import,pass,break,except,in,raise

-type(degisken) : değişkenin tipini verir
-int(degisken) : Değişkenin tipini int yapar
-float(degisken) : Değişkenin tipini float yapar
-degiskenstr='kelime' : String tanımlama
-len(degiskenstr) : String uzunluğunu verir
-degiskenstr.find('karakter') : karakteri ilk bulduğ yerin indisini verir
-degiskenstr.replace('kelime1', 'kelime2') : karakter dizisinde kelime1 gördüğü 
 yerleri kelime2 ile değiştirir
-degiskenstr.strip(): karakter dizisindeki başdaki ve sondaki boşlukları siler 
-degiskenstr.lower() : karakter dizisindeki bütün karakterleri küçük harfe dönüştürür
-degiskenstr[0:3] : 0.indis 1.indis 2.indis'teki karakterleri alır
-degiskenstr[5:8] : 5.indis 6. indis 7.indis'teki karakterleri alır
-degiskenstr[5:] : 5.indis'den sonuncu indise kadar kadar olan karakterleri alır
-max(a,b) : max değer
-min(a,b) : min değer
-liste tanımlama: a= [1,"merhaba",3.7]
-tuple(değiştirelemeyen liste) tanımlama: a = (1,"merhaba",3.7)
-set(tek olan değerleri tutan bir yapı,indexle erişilemez) tanımlama:a={1,2,3,4}
-dictionary tanımlama:a = {key:'value1',key2:'value2'}

 Print Fonksiyonu
-sep ve end parametreleri:
>>>print("honki","ponki","torino",sep='#',end='!')
honki#ponki#torino&!

-format
>>>a=5
>>>b=10
>>>print('1. sayı: {} ,2. sayı: {}'.format(a,b))
1. sayı: 5,2. sayı: 10
>>>print('1. sayı: {0} 2. sayı: {1}'.format(a,b))
>>>1. sayı: 5,2. sayı: 10
>>>print('1. sayı: {1} 2. sayı: {0}'.format(a,b))
>>>1. sayı: 10,2. sayı: 5

>>> print('Selam {kelime1}, {kelime2}'.format(kelime1 = 'Sana', kelime2 = 'Dünyalı'))
Selam Sana Dünyalı

-input
>>>deger=input("Giriş yapınız:")
