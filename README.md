# KIZAGAN (ENGLISH EXPRESSION)
KIZAGAN is a python backdoor(Remote Access Trojan) and it can take camera pictures,screenshots,getting microphone sounds... etc.


# EDUCATIONAL PURPOSES ONLY.

I am not responsible for the crimes you may commit with this backdoor.


# New update version (1.4)
New feautures :

Optional : When the trojan executed on victim's machine,the file(you specified on code) will started and trojan will run on background.So,the trojan will be less suspicious.


# SETUP :

# python setup.py


# USAGE : 

Open the kizaganEN.py with text editor and change the ip and port according to yourself.

![kizaganEN1](https://user-images.githubusercontent.com/68844502/178123760-b3e5cc59-9f9a-48c4-9d78-e5d058d939c8.PNG)

If you want the Trojan to run simultaneously with a file you specify,change the value of Open_Added_File function.If you don't want,just convert to exe with pyinstaller.

![kizaganEN2](https://user-images.githubusercontent.com/68844502/178124236-ed9e8a5f-8482-46ef-b69b-77d160a45083.PNG)

Then,use the pyinstaller to convert exe with file to be added, with command : (Be sure the file to be added and kizaganEN.py in the same location.)(Do this converting process in windows machine.In linux,some errors may occur.)

# pyinstaller --onefile --noconsole --icon <your ico file (if you want)> --add-data "<examplefile.pdf>;." -w kizaganEN.py

![kizaganEN3](https://user-images.githubusercontent.com/68844502/178124176-4154d80e-0676-4690-bf7d-a0c00a05e141.jpg)

Send this exe file to victim and wait for the victim execute the trojan.

Finally, use this command to start listener in your machine and wait the connection.(You don't need to start listener now,because the trojan will send you connection every 5 seconds.) :

# python kizagan_listener.py -ip <ip_address_to_listen> -p <port_number_to_listen>

![kizagan3](https://user-images.githubusercontent.com/68844502/177311607-d7a61438-3e76-40bf-8663-1f09e2039aee.PNG)

![kizagan4](https://user-images.githubusercontent.com/68844502/177312014-30db5b8b-db14-4177-bf39-c102e6a88d76.PNG)


# Example usages :

Listening connections.

![kizagan5](https://user-images.githubusercontent.com/68844502/177312224-02e6f87d-d837-4f1b-b123-1e069fb9176e.PNG)

Victim executes the trojan and a connection comes.

![kizagan6](https://user-images.githubusercontent.com/68844502/177312225-16a19f54-6f81-4f90-bb25-f9eb9ec1541a.PNG)

Help menu:

![kizagan7](https://user-images.githubusercontent.com/68844502/177312228-807d54c8-d2e0-4559-b670-cadaa8a2a942.PNG)

![kizagan8](https://user-images.githubusercontent.com/68844502/177312229-59de9db9-59a2-4930-b5b1-423ed011053c.PNG)

![kizagan9](https://user-images.githubusercontent.com/68844502/177312230-6a4e6804-7c9c-4b20-9283-db87240bd36c.PNG)

Taking camera pictures,screenshots,keylogs and microphone recording...

![kizagan10](https://user-images.githubusercontent.com/68844502/177312217-cfda9dd7-5965-4735-b98f-f2602b18477f.PNG)

# Author Instagram : https://www.instagram.com/arduinocum.py/

# KIZAGAN (TÜRKÇE ANLATIM)
KIZAGAN bir python backdoorudur(Remote Access Trojan) ve bu backdoor kamera görüntüleri,ekran görüntüleri,mikrofon kayıtları vb. alabilir...


# SADECE EĞİTİM AMAÇLIDIR.

Bu backdoor ile işleyebileceğiniz suçlardan sorumlu değilim.


# Yeni güncelleme versiyon (1.4)
Yeni özellikler :

Opsiyonel : Trojan kurbanın makinesinde çalıştırıldığında, dosya (kodda belirttiğiniz) çalışacak ve trojan arka planda çalışacaktır. Böylece trojan daha az şüpheli olacaktır.


# KURULUM : 

# python setup.py


# KULLANIM :

kizaganTR.py'yi bir text editörü ile açın, ip ve portu kendinize göre değiştirin.

![kizaganTR1](https://user-images.githubusercontent.com/68844502/178124576-f5b0ba3c-55f6-440f-8a7d-57bad8e50138.PNG)

Trojan'ın belirttiğiniz bir dosya ile aynı anda açılmasını istiyorsanız,Eklenmis_Dosya_Ac fonksiyonunun değerini değiştirin. İstemiyorsanız, pyinstaller ile exe'ye dönüştürmeniz yeterlidir.

![kizaganTR2](https://user-images.githubusercontent.com/68844502/178124701-c69c566f-f0d9-48f1-bde0-a2003236a377.PNG)

Ardından, eklenecek dosya ile exe'yi dönüştürmek için pyinstaller'ı şu komut ile kullanın: (Eklenecek dosyanın ve kizaganEN.py'nin aynı konumda olduğundan emin olun.)(Bu dönüştürme işlemini Windows makinesinde yapın.Linux'ta bazı hatalar çıkabilir.)

# pyinstaller --onefile --noconsole --icon <ikon dosyaniz (eğer isterseniz)> --add-data "<ornekdosya.pdf>;." -w kizaganTR.py

![kizaganTR3](https://user-images.githubusercontent.com/68844502/178124847-ac0f515f-bc43-40b2-9872-2384b76f2ce2.jpg)

Kurbana dönüştürdüğünüz bu exe dosyasını gönderin ve çalıştırmasını bekleyin.

Son olarak,bu komutu kullanarak dinleyiciyi kendi makinenizde başlatın ve bağlantıyı bekleyin.(Dinleyiciyi şimdi başlatmanıza gerek yok, çünkü trojan size her 5 saniyede bir bağlantı gönderecektir.) :

# python kizagan_listener.py -ip <dinlemek_istediğiniz_ip_adresi> -p <dinlemek_istediğiniz_port_numarası>

![kizagan3](https://user-images.githubusercontent.com/68844502/177311743-274c9445-a8f8-4a61-9117-707205012435.PNG)

![kizagan4](https://user-images.githubusercontent.com/68844502/177312087-d96896ea-197d-404d-921b-d878b7d55985.PNG)



# Örnek kullanımlar : 

Bağlantılar dinleniyor.

![kizagan11](https://user-images.githubusercontent.com/68844502/177312667-d116c2fd-176a-4fbe-b01f-57e8c5d1fa2d.PNG)

Kurban trojanı çalıştırdı ve bir bağlantı geldi.

![kizagan12](https://user-images.githubusercontent.com/68844502/177312670-07032d9f-85c7-4b08-a3e3-ff0b6df970b7.PNG)

Türkçe yardim menüsü.

![kizagan13](https://user-images.githubusercontent.com/68844502/177312672-c4addcbc-cad7-4d77-b8d5-0b6f052f6a8d.PNG)

![kizagan14](https://user-images.githubusercontent.com/68844502/177312675-27bb1307-80d3-481c-9c38-159e1cb8944c.PNG)

![kizagan15](https://user-images.githubusercontent.com/68844502/177312680-55e49a94-f0b1-46b2-a395-4021945dde0c.PNG)

Kamera resimleri,ekran görüntüleri,kurbanin bastigi tuslar ve kurbanin mikrofon kaydini almak...

![kizagan16](https://user-images.githubusercontent.com/68844502/177312682-52f4a3a3-6d9d-4f52-ab08-f5cc6559fbf3.PNG)

# Yazarın Instagramı : https://www.instagram.com/arduinocum.py/
