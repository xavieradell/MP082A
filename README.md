# MP082A

Moodle

Per a començar cal desarregar el paquet de moodle de la pàgina oficial moodle en el meu cas la versió que usaré serà la 4.1 l'enllaç de decarrega és el següent: https://download.moodle.org.

![image](https://user-images.githubusercontent.com/118992579/205091573-5242b436-c29f-45df-adde-1f2ad87b1929.png)

Un cop descarregat tenim que descomprimir-ho i moure la carpeta resulant a /var/www/html.

![image](https://user-images.githubusercontent.com/118992579/205092112-886d425b-449c-4f95-9f61-6a99bca948f9.png)

![image](https://user-images.githubusercontent.com/118992579/205092248-4d72d667-c352-44dc-81cf-7762fc9288e1.png)

Un cop fet aixó crearem una carpeta on vulguem (preferiblement separada de la propia carpeta del moodle) que es dirà moodledata, aquesta carpeta serà el nostre repositori.

![image](https://user-images.githubusercontent.com/118992579/205092781-3c18f16a-6c62-4199-914d-5edf3f059db8.png)

un cop creades aquesta carpeta canviarem el propietari i el grup propietari a www-data.

![image](https://user-images.githubusercontent.com/118992579/205093418-d77670ec-2265-47b3-aa88-ceff995ebb7a.png)

També canviarem el propietari i el grup propietari de la carpeta moodle situada a /var/www/html.

![image](https://user-images.githubusercontent.com/118992579/205094184-7a3405e2-dce0-4c93-b289-64e827196a21.png)

Despres he procedit a instalar el php7.4, MySQL i Apache2.

![image](https://user-images.githubusercontent.com/118992579/205096924-15b7beee-a7bc-4a61-8209-4e00f21933cb.png)

![image](https://user-images.githubusercontent.com/118992579/205097277-6bce82ec-108b-4e55-a23c-2ac0a686281e.png)

![image](https://user-images.githubusercontent.com/118992579/205096469-ac1c7629-b575-46df-888f-ddc69dc59e83.png)

