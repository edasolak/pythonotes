# Dosya İşlemleri 

•Dosya Açma<br>
dosya  = open("dosyadi", "mod")<br>  

Modlar<br>
‘r’ – Okuma Modu<br>
‘w’ – Yazma Modu<br>
‘a’ – Dosyanın Sonuna Ekleme Modu<br>

----------------------------------------------------------------------
dosya = open("test.txt","w") <br>
dosya.write("Hello World") <br>
dosya.close()<br>

----------------------------------------------------------------------

dosya = open(“test.txt”, “r”) <br>
print file.read() #Dosya içeriğini döndürür<br>
print file.read(5) #İlk 5 karakteri döndürür<br>
print file.readline(): #İlk satırı döndürür<br>
print file.readline(3): #Üçüncü satırı döndürür<br>
print file.readlines() #Bütün satırları döndürür <br>
 
