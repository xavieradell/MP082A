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

Ara un cop instalat tot el nombrat anteriorment cal obrir el navegador que usis per accedir a la part final de l'instalació, al navegador cal posar: "ip del servidor"/moodle i ens sortirà la pàgina d'instalació de moodle.

![image](https://user-images.githubusercontent.com/118992579/205099100-baff9fa1-5013-4d7b-ae00-e0172fb77673.png)

En aquesta pàgina seleccionarem l'idioma que vulguem en el meu cas he seleccionat català.

Al premer continuar la següent pàgina ens demanarà els paquets php.

![image](https://user-images.githubusercontent.com/118992579/205100064-fa7d04ba-f3aa-4730-b97f-6155d1aad184.png)

![image](https://user-images.githubusercontent.com/118992579/205100173-7b6fad8b-8eee-4085-aca0-868daba065a8.png)

![image](https://user-images.githubusercontent.com/118992579/205100241-4dc8f5b1-aa9f-4e76-b5d5-174154e14fde.png)

Un cop intalat tot sol caldrà reiniciar apache2.

![image](https://user-images.githubusercontent.com/118992579/205100394-7a8701c8-6ee4-481d-be1a-f7715fbb5a06.png)

Acabat aixó ens demanarà les dades de la nostra base de dades que crearem ara amb la següent comanda:

![Selecció_455](https://user-images.githubusercontent.com/118992579/212108117-509f4869-a61b-4911-8709-932b138dd938.png)

Un cop crada la base de dades crearem un usuari i a aquest usuari li donarem permissos sobre la base de dades de moodle.

![Selecció_457](https://user-images.githubusercontent.com/118992579/212108469-fe22a7c8-af12-49b7-900e-5df4248a78f3.png)

![Selecció_458](https://user-images.githubusercontent.com/118992579/212108494-997f01f6-1ebc-4e65-971b-8dcd1f2029b3.png)

Un cop creada la base de dades entrarem al següent enllaç:

![image](https://user-images.githubusercontent.com/118992579/213024820-dde145d2-4779-4bee-9065-503ed9d7c02c.png)

Segons la ip del nostre servidor variarà.

Aquí començarem la instalació del moolde.

Instalarem les dependencies que ens demana el propi moodle.

Ens demana la base de dades amb l'usuari administrador i la carpeta on penjaran els usuaris els seu arxius "moodle data".

Instalat ja el moodle anirem a la creació de categories i els cursos:
![Selecció_463](https://user-images.githubusercontent.com/118992579/213025903-35b2627d-6b0d-4c45-aab6-4a17d1908e57.png)

