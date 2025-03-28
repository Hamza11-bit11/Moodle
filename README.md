# Pràctica UF4 - Instal·lació i configuració de moodle
## Objectius generals de la pràctica
* Instal·lar i configurar gestors de continguts, concretament `moodle`.
* Aprende a utilitzar `moodle` com a administrador.

## Desenvolupament de la pràctica

Aquesta pràctica consisteix en fer un portal de temàtica lliure. El portal haurà d’estar fet en `moodle`.

* Heu d’instal·lar `moodle` en un nou escriptori a `IsardVDI`. Seguiex els passos que indica el [manual d'instal·lació d'aplicacions web](installacio-aplicacions-web.md)
* Descarrega la última versió de moodle des de la pàgina oficial https://moodle.org![image](https://github.com/user-attachments/assets/249805a5-f420-4601-9d82-74405cb43ba0)

![image](https://github.com/user-attachments/assets/68532bc9-e9ab-446a-8891-bb7977ea00cf)


* Heu de configurar `moodle` amb els requisits mínims que s'indiquen a continuació:

![image](https://github.com/user-attachments/assets/c7bab385-e747-4666-81a1-5c1dcb318d29)
![image](https://github.com/user-attachments/assets/3ce96561-3637-4668-8937-20266ee7fb59)
![image](https://github.com/user-attachments/assets/9548ccac-109c-4fb9-8ecc-7c392d28e440)

## Configuració

**1.** Inicia sessió com a administrador del teu Moodle i realitza les següents tasques prèvies d'administració.
![image](https://github.com/user-attachments/assets/66fe9fd4-1946-4ba3-8162-7f7c92ba26b3)


   **a)** Canvia la teva direcció de correu electrònic i també la teva contrasenya per una altra. Afegeix-te a més un avatar. Tot això es pot fer anant al teu perfil (opció que apareix sota el teu nom que es veu a la part superior dreta de la finestra del Moodle) i clicant sobre l'enllaç `Editar` (o també anant a l'opció `Preferències`, situada al mateix lloc).
   ![image](https://github.com/user-attachments/assets/a3a3286d-841c-4929-9602-14a61d219e9d)

   **b)** Canvia el nom del teu lloc (tant llarg com curt) i fes que la pàgina principal no mostri res pels usuaris que no estiguin autentificats. Això es pot fer anant a l'opció `Administració del lloc > Primera plana > Paràmetres`
   ![image](https://github.com/user-attachments/assets/5c8f65b3-8083-4285-a4a7-dc9e1ac0327e)

   **c)** Comprova que la franja horària del teu lloc sigui la correcta. Això es pot fer anant a l'opció `Administració del lloc > Ubicació > Paràmetres`.
   
   **NOTA:** Aquesta configuració és important, per exemple, per les hores límit d'entregues d'exercicis
   
   **d)** Canvia l'idioma del teu lloc. Això es pot fer anant a l'opció `Administració del lloc > Idioma > Paràmetres` i tenint en compte tant el checkbox `Detecció automàtica de l'idioma` com el desplegable `Idioma per defecte`.
![image](https://github.com/user-attachments/assets/899cf96a-8f8f-4120-9c73-379de6dd02cb)

   
   **NOTA:** Per disposar d'un determinat idioma, primer cal instal.lar-lo des de `Administració del lloc > Idioma > Paquets d'idioma`
   
   **e)** Canvia la política de contrasenyes de manera que els usuaris que es creiïn tinguin una contrasenya de com a mínim 4 caràcters incloent-hi, majúscules, minúscules i xifres. Això es pot fer anant a l'opció `Administració del lloc > Seguretat > Normatives del lloc`.

![imagen_2025-03-28_173202195](https://github.com/user-attachments/assets/5d1d8d79-22cb-4363-9349-4bf77d347401)

**2.** Crea els següents cursos: un curs anomenat A que estigui format per 3 temes i un altre anomenat B que estigui format per 5 temes. Tot això ho pots fer des de `Administració del lloc > Gestiona cursos i categories` o també des del quadre `Navegació` anant a `Cursos > Afegeix curs`
![image](https://github.com/user-attachments/assets/784d1773-1559-490b-8857-29d899fc3d87)
![image](https://github.com/user-attachments/assets/825c6d7a-dee1-430f-8947-d7b65f17d157)


**3.** Vés a algun dels cursos creats al punt anterior (simplement seleccionant-lo dins del quadre `Navegació`) i fes que contingui en algun del seus temes algun tipus de material (un document PDF, per exemple), canvia el títol d'algun tema i, en general, investiga les possibilitats que et dóna el botó `Activar edició` en un curs.
![image](https://github.com/user-attachments/assets/ad922223-f349-4278-9f99-6f21a1947397)


   **NOTA:** Aquestes possibilitats no les estudiarem a fons perquè són una tasca més pròpia del professor que no pas de l'administrador del Moodle, però sempre va bé tenir-ne alguna idea.

**4.** Creació d’usuaris i alumnes. 
   
   **a)** Crea manualment un usuari anomenat `Bob` que ha de fer servir el `mètode d'autenticació manual`. Això es pot fer des de `Administració del lloc > Usuaris > Comptes > Afegeix un usuari`
   ![image](https://github.com/user-attachments/assets/0a56c364-70b0-4974-a337-69fb65c5fc42)

   **b)** Genera deu alumnes que ho seran dels dos cursos A i B . Fes servir un arxiu CSV per realitzar aquesta creació en bloc. Vés a `Administració del lloc > Usuaris > Comptes > Carrega usuaris` i segueix els passos que et marca. 
   ![image](https://github.com/user-attachments/assets/f0d55160-af25-42aa-9e9e-70ff87a4364b)
![image](https://github.com/user-attachments/assets/ef84f651-3b8b-4df4-b449-29523f40ea7a)

   **NOTA:** Per saber el contingut que hauria de tenir aquest fitxer, consulteu més abaix a la secció `Usuaris`.
   
   **c)** Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció `Administració del lloc > Usuaris > Accions amb usuaris en bloc`
![image](https://github.com/user-attachments/assets/a2a3e20b-6757-405d-aa07-c59dd83ae4b6)

**5.** Ara matricula aquests usuaris als diferents cursos.
![image](https://github.com/user-attachments/assets/af3cb111-9189-4e8d-b708-0aa1455790df)


   **a)** Fes que al curs A no hi hagi possibilitat d'inscripció (és a dir, que només es permeti l'accés de visitant de manera que el curs sigui totalment públic sense control d'usuaris -ni alumnes ni professors-). D'altra banda, fes que al curs B es necessiti registre manual d'usuaris (és a dir, que sigui l'administrador -tu- qui matriculi cada usuari al curs, ja sigui com a professor o com a alumne). Tot això ho pots fer des de `Administració del curs > Ususaris > Mètodes d'inscripció`. Si no surt algun mètode d'inscripció disponible, has d'activar-lo a: `Administració de lloc > Connectors > Autenticació > Gestió de l'autenticació`
![imagen_2025-03-28_173843570](https://github.com/user-attachments/assets/a9e6b62e-8201-4524-a05e-183c370fe454)

   **b)** Assigna com a professor del curs B l'usuari "Bob" i com a alumnes a tots els que fas afegir des de l'arxiu CSV Tot això ho pots fer anant a `Administració del curs > Usuaris inscrits > Inscriure`.
![image](https://github.com/user-attachments/assets/0eabbb83-a431-455c-af78-85fdeb6cc790)

   **c)** Comprova que efectivament, el contingut del curs A (afegit per l'administrador del sistema -és a dir, tu- estigui disponible públicament i que per accedir al curs B s'hagi d'iniciar sessió amb un usuari registrat (alumne o professor)
![imagen_2025-03-28_174228136](https://github.com/user-attachments/assets/91013dc3-55c4-448f-9836-4bb767677001)

**6.** Canvia l'aparença estètica del teu lloc. Concretament, descarrega't i activa un tema diferent dels que venen per defecte i prova de canviar també la capçalera i el peu de pàgina del lloc. Això ho pots fer primer anant a `Administració del lloc > Connectors > Instal·lar complement` i després a `Administració del lloc > Aparença > Temes > Selector de temes` Sempre pots fer servir l'enllaç `Canvi de rol` del menú de la dreta per observar com es veuria el lloc sent alumne, professor, etc.
![image](https://github.com/user-attachments/assets/8f854410-33de-453d-87bd-74b63d522d61)

**7.** Assigna un professor i matricula alumnes al curs A.
![image](https://github.com/user-attachments/assets/e0e3c7f5-9ebb-4a08-9005-58a449ef4bc4)


**8.** Amb el professor afegeix contingut al curs A. Afegeix diferents tipus d’activitats i recursos. Crea una tasca amb data d’entrega oberta que demani la càrrega d’un fitxer PDF.
![image](https://github.com/user-attachments/assets/f9534a84-7e5b-45e2-a8a4-a722ed9ea7fa)
![imagen_2025-03-28_174456775](https://github.com/user-attachments/assets/1d3f529d-5214-46e8-8a4d-ab79fa7c4193)

**9.** Entra amb un alumne i comprova que pots lliurar la tasca.
![{1A51201D-BAB6-4CBC-9B45-96F474D42A4E}](https://github.com/user-attachments/assets/88021c31-300a-4b27-9c60-9103001d0e10)

## Continguts
En el curs A crea una UF amb 2 NF dintre. En aquesta UF crea diverses activitats.
![image](https://github.com/user-attachments/assets/d9699761-3db2-4a86-8582-5dae72de60b1)

Botó Activar Edició (a dalt a la dreta). Una UF es pot crear amb una etiqueta i movent a la dreta el seu contingut. Es pot canviar el Format del curs a `Temes` a `Administració del Curs > Editar Curs > Format del Curs`

Fes servir el moodle del puig com a referència. Han d’haver tant activitats magistrals com evaluables (com a mínim una entrega i un questionari). Clona (importa) el curs sencer al curs B `Administració del Curs > Importar` (des del curs B)
![{80FA4EF4-1429-405F-8C13-2298C7B2FD01}](https://github.com/user-attachments/assets/00407885-1cab-407d-ac1e-617a71c23bea)
![{2F357D0D-70D5-41BE-B22B-AFDF93D74771}](https://github.com/user-attachments/assets/9e370855-c83e-4378-ac82-969b504649e0)
![{24734FB8-0BED-4FE2-B487-DFA32A17EB74}](https://github.com/user-attachments/assets/b5ae4d48-e6fe-41d4-848b-cd8e7c6c92a7)
![{1786EB43-F1FD-44CF-97B7-C14E31797E29}](https://github.com/user-attachments/assets/766ff460-7d13-4423-8281-bc5c1db152e5)

## Qualificació
En el curs A fes que un alumne completi totes les tasques evaluables (entrant amb la seva compta). Calificales amb el professor i configura el calificador per a que doni una nota de la UF automàticament a `Administració del Curs > Configuració de qualificacions`.
![{6D06784E-4342-4118-98FF-DC8D69A9BD9F}](https://github.com/user-attachments/assets/fdf4923a-c4db-4276-a95f-ab4c64c4ee98)

Crea una insignia i atorga-la a aquest alumne des de `Administració del Lloc > Insígnies`
![image](https://github.com/user-attachments/assets/07458e92-9a4b-45ec-b60f-1a4233b76700)
![{80B433F3-05D8-4746-ACFA-2BF791DBDFF7}](https://github.com/user-attachments/assets/e135bd90-5e8e-497b-bdbf-505bb6539eaa)

## Qüestionaris
Crea un qüestionari i afegeix preguntes del banc de preguntes. Crea diferents categories dintre del banc de preguntes i diverses preguntes en cada categoria. A l'hora de crear el qüestionari has de seleccionar les preguntes del banc de preguntes. Respon les preguntes del qüestionari amb un usuari estudiant i mira les qualificacions amb l'usuari professor.
![image](https://github.com/user-attachments/assets/761e9d00-a607-47bd-ba74-8323c5222f3e)
![{BBEE714C-B834-4DD7-96C8-E4E06A1B6BD2}](https://github.com/user-attachments/assets/811d8944-e8e8-4280-8585-66a3e2ccf9b7)
![{AF956CAC-098A-457E-8D33-1F599AE79097}](https://github.com/user-attachments/assets/5345d9d6-31ac-4a6f-9908-d7e8e2957ce8)

## Importar i exportar un curs
Entra a la zona `Administració > Cursos > Còpies` i fes una còpia de seguretat del teu curs. Després envia aquest fitxer a un company i que l'importi al seu moodle. Has d'importar al teu moodle un altre curs d'un company. 

## Personalització
Descarrega i aplica un tema nou al teu LMS.
![image](https://github.com/user-attachments/assets/d3316667-8cc8-4768-87d9-9dd71317631b)

Edita també tant la capçalera (header) com el peu (footer) i la pàgina principal (Front page) Posa-li un logotip al teu moodle.

## Seguretat
Baneja una IP i aplica una política de seguretat. Pots posar la que vulguis però l’hauràs de justificar.
![{D123B993-AB3D-4310-9661-9711DFE4B0A3}](https://github.com/user-attachments/assets/d1fdd427-8d8f-4e3b-a68b-2606580d112c)


## Usuaris
Crea 10 usuaris alumnes i un usuari professor posant-li dades.
`Administració del Lloc > Usuaris > Crear Usuari / Pujar Usuaris` (de cop amb un arxiu csv, hi ha un model de csv al final del document).

![image](https://github.com/user-attachments/assets/191f1805-4529-444e-86cc-0427b6fb1a75)
