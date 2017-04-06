# Python Temelleri
•Python Teknolojileri <br/>
-Python paket yöneticisi -> pip (Python modüllerini kolayca yüklememizi sağlar) <br/>
-Python Web Frameworkleri -> djhango,web2py,flask,grok,tornado,turbogears.. <br/>
-Python Debugging araçları -> Pychecker,pudb,pdb,pylint.. <br/>
-Python Shell ->ipython,dreampie.. <br/>
-Python Game -> PyWeek,Pygame.. <br/>
-Python CMS -> Skeletonz,Mezzanine,Ikaro,Django.. <br/>
-Python GUI frameworkleri -> Tkinter,PyQT,WxPython.. <br/>

--------------------------------------------------------------------------------

•Python yükle,Python çalıştır.<br/>
Bilgisayarda hazırda kurulu bir Python var mı? -> terminal ekranında : python -V <br/>
Varsa:terminalde python yazarak pyhon etkileşimli kabuğa gidilir.(Python etkileşimli kabuk Python kodlarını 
çalıştırmamıza yarayan katmandır.)<br/>
Yoksa : sudo apt-get install python3 (Debian tabanlı Linux dağıtımları için)<br/>
python yazarak : >>> (etkileşimli kabuk),etkileşimli kabuktan çıkmak için : Ctrl+D<br/>
chmod +x firstprog.py -> python kodumuza çalıştırma yetkisi verir.<br/>
Python için editör : PyCharm(kurulum için-> https://www.jetbrains.com/pycharm-edu/quickstart/installation.html#linux)<br/>

--------------------------------------------------------------------------------

•Değişkenler ve Veri Tipleri<br/>

 <label>>>></label>5+5<br/> 
 10<br/>

<label>>>></label>'5''5'<br/>
 55<br/>
<label>>>></label>4*5<br/>
20<br/>
<label>>>></label>'4'*5<br/>
44444<br/>
<label>>>></label>"a"+"b"<br/>
ab<br/>
<label>>>></label>"a"*3<br/>
aaa<br/>
<label>>>></label>3**2<br/>
9<br/>

<label>>>></label>x=1==1<br/>
True<br/>

<label>>>></label>sayi = 1 + 2+\\<br/>
...3 + 4<br/>
<label>>>></label>sayi<br/>
10<br/>

<label>>>></label>sayi2 = (1 + 2 + <br/>
...3 + 4)<br/>
<label>>>></label>sayi2<br/>
10<br/>

<label>>>></label>a=1;b=1;c=1 #kullanılabilir<br/>
<label>>>></label>a, b, c = 5, 3.14, "Ola" #kullanılabilir<br/>
<label>>>></label>x = y = z = "same"  #kullanılabilir<br/>

-Degişken ismi olarak kullanamayacaklarımız: False,class,finally,is,return,None,continue,for,lambda,try,True,def,from,nonlocal,while,and,del,global,not,<br/>
with,as,elif,if,or,yield,assert,else,import,pass,break,except,in,raise<br/>

-type(degisken) : değişkenin tipini verir<br/>
-int(degisken) : Değişkenin tipini int yapar<br/>
-float(degisken) : Değişkenin tipini float yapar<br/>
-degiskenstr='kelime' : String tanımlama<br/>
-len(degiskenstr) : String uzunluğunu verir<br/>
-degiskenstr.find('karakter') : karakteri ilk bulduğ yerin indisini verir<br/>
-degiskenstr.replace('kelime1', 'kelime2') : karakter dizisinde kelime1 gördüğü yerleri kelime2 ile değiştirir<br/>
-degiskenstr.strip(): karakter dizisindeki başdaki ve sondaki boşlukları siler<br/> 
-degiskenstr.lower() : karakter dizisindeki bütün karakterleri küçük harfe dönüştürür<br/>
-degiskenstr[0:3] : 0.indis 1.indis 2.indis'teki karakterleri alır<br/>
-degiskenstr[5:8] : 5.indis 6. indis 7.indis'teki karakterleri alır<br/>
-degiskenstr[5:] : 5.indis'den sonuncu indise kadar kadar olan karakterleri alır<br/>
-max(a,b) : max değer<br/>
-min(a,b) : min değer<br/>
-liste tanımlama: a= [1,"merhaba",3.7]<br/>
-tuple(değiştirelemeyen liste) tanımlama: a = (1,"merhaba",3.7)<br/>
-set(tek olan değerleri tutan bir yapı,indexle erişilemez) tanımlama: a={1,2,3,4}<br/>
-dictionary tanımlama: a = {key:'value1',key2:'value2'}<br/>

 Print Fonksiyonu<br/>
-sep ve end parametreleri:<br/>
<label>>>></label>print("honki","ponki","torino",sep='#',end='!')<br/>
honki#ponki#torino!<br/>

-format<br/>
<label>>>></label>a=5<br/>
<label>>>></label>b=10<br/>
<label>>>></label>print('1. sayı: {} ,2. sayı: {}'.format(a,b))<br/>
1. sayı: 5,2. sayı: 10<br/>
<label>>>></label>print('1. sayı: {0} 2. sayı: {1}'.format(a,b))<br/>
1. sayı: 5,2. sayı: 10<br/>
<label>>>></label>print('1. sayı: {1} 2. sayı: {0}'.format(a,b))<br/>
1. sayı: 10,2. sayı: 5<br/>

<label>>>></label> print('Selam {kelime1}, {kelime2}'.format(kelime1 = 'Sana', kelime2 = 'Dünyalı'))<br/>
Selam Sana Dünyalı<br/>

-input<br/>
<label>>>></label>deger=input("Giriş yapınız:")<br/>
