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

Per afegir les categories cal anar a "Site administration" dins de "courses" i seleccionar "add category".
![Selecció_479](https://user-images.githubusercontent.com/118992579/213026671-235fe209-3cb8-408f-a0a8-65664bc037ce.png)

Per afegir els cursos cal anar a "Site administration" dins de "courses" i seleccionar "add a new cours".
![Selecció_480](https://user-images.githubusercontent.com/118992579/213026871-8dbf597b-8e64-45ea-b425-a3af07de433f.png)

Quins tipus d'usuaris (rols diferents) existeixen a Moodle?

-Administrador/Gestor

-Professor  amb permissos de edició

-Professor tutor

-Estudiant

Quins rols poden assignar cada tipus d'usuaris?

-Professor  amb permissos de edició

-Professor tutor

-Estudiant

Mostra l'apartat Participants de cada curs.
![Selecció_471](https://user-images.githubusercontent.com/118992579/213028029-cb064ce0-a6e2-4e00-a715-77aba5794804.png)
![Selecció_472](https://user-images.githubusercontent.com/118992579/213028038-8003bdc9-fb63-4e43-bdfc-0857440f4555.png)
![Selecció_473](https://user-images.githubusercontent.com/118992579/213028057-d3e8edec-a78e-4a79-b9e5-96dadb2c786f.png)
![Selecció_474](https://user-images.githubusercontent.com/118992579/213028066-1f8a2b80-bee7-4ac8-89ac-ef5f1320b48f.png)
![Selec![Selecció_476](https://user-images.githubusercontent.com/118992579/213028088-a941c2a0-efc3-4e3b-9739-eaede7ee29b3.png)
![Selecció_477](https://user-images.githubusercontent.com/118992579/213028096-36db204a-cc6f-4b88-ae56-6cab9b21128f.png)
ció_475](https://user-images.githubusercontent.com/118992579/213028076-08903519-dd7a-4d89-87d0-1dd1cabea2fe.png)

Què són les Cohorts?
Els Cohorts són una forma d'agrupar usuaris.

Perquè serveixen?
Ens permet tractar més ràpid un grup d'alumnes a l'hora de inscriure'ls als cursos.

Què són els grups?Perquè serveixen?
Són agrupacions de alumnes que permet dividir les diversos alumnes de les seus grups.

![image](https://user-images.githubusercontent.com/118992579/213029837-b665887f-ac23-4eb5-9e1d-66aefe3488a3.png)
