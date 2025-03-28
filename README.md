# Pràctica UF4 - Instal·lació i configuració de moodle
## Objectius generals de la pràctica
* Instal·lar i configurar gestors de continguts, concretament `moodle`.
* Aprende a utilitzar `moodle` com a administrador.

## Desenvolupament de la pràctica

Aquesta pràctica consisteix en fer un portal de temàtica lliure. El portal haurà d’estar fet en `moodle`.

* Heu d’instal·lar `moodle` en un nou escriptori a `IsardVDI`. Seguiex els passos que indica el [manual d'instal·lació d'aplicacions web](installacio-aplicacions-web.md)

* Descarrega la última versió de moodle des de la pàgina oficial https://moodle.org

* **IMPORTANT:** Documenta tot el que facis amb captures de pantalla i explicacions. Crea un repositori a github per a guardar el teu manual de configuració amb captures de pantalla i explicacions dins d'un fitxer MarkDown.

* Heu de configurar `moodle` amb els requisits mínims que s'indiquen a continuació:

## Configuració

**1.** Inicia sessió com a administrador del teu Moodle i realitza les següents tasques prèvies d'administració.

   **a)** Canvia la teva direcció de correu electrònic i també la teva contrasenya per una altra. Afegeix-te a més un avatar. Tot això es pot fer anant al teu perfil (opció que apareix sota el teu nom que es veu a la part superior dreta de la finestra del Moodle) i clicant sobre l'enllaç `Editar` (o també anant a l'opció `Preferències`, situada al mateix lloc).
   
   **b)** Canvia el nom del teu lloc (tant llarg com curt) i fes que la pàgina principal no mostri res pels usuaris que no estiguin autentificats. Això es pot fer anant a l'opció `Administració del lloc > Primera plana > Paràmetres`
   
   **c)** Comprova que la franja horària del teu lloc sigui la correcta. Això es pot fer anant a l'opció `Administració del lloc > Ubicació > Paràmetres`.
   
   **NOTA:** Aquesta configuració és important, per exemple, per les hores límit d'entregues d'exercicis
   
   **d)** Canvia l'idioma del teu lloc. Això es pot fer anant a l'opció `Administració del lloc > Idioma > Paràmetres` i tenint en compte tant el checkbox `Detecció automàtica de l'idioma` com el desplegable `Idioma per defecte`.
   
   **NOTA:** Per disposar d'un determinat idioma, primer cal instal.lar-lo des de `Administració del lloc > Idioma > Paquets d'idioma`
   
   **e)** Canvia la política de contrasenyes de manera que els usuaris que es creiïn tinguin una contrasenya de com a mínim 4 caràcters incloent-hi, majúscules, minúscules i xifres. Això es pot fer anant a l'opció `Administració del lloc > Seguretat > Normatives del lloc`.

**2.** Crea els següents cursos: un curs anomenat A que estigui format per 3 temes i un altre anomenat B que estigui format per 5 temes. Tot això ho pots fer des de `Administració del lloc > Gestiona cursos i categories` o també des del quadre `Navegació` anant a `Cursos > Afegeix curs`

**3.** Vés a algun dels cursos creats al punt anterior (simplement seleccionant-lo dins del quadre `Navegació`) i fes que contingui en algun del seus temes algun tipus de material (un document PDF, per exemple), canvia el títol d'algun tema i, en general, investiga les possibilitats que et dóna el botó `Activar edició` en un curs.

   **NOTA:** Aquestes possibilitats no les estudiarem a fons perquè són una tasca més pròpia del professor que no pas de l'administrador del Moodle, però sempre va bé tenir-ne alguna idea.

**4.** Creació d’usuaris i alumnes. 
   
   **a)** Crea manualment un usuari anomenat `Bob` que ha de fer servir el `mètode d'autenticació manual`. Això es pot fer des de `Administració del lloc > Usuaris > Comptes > Afegeix un usuari`
   
   **b)** Genera deu alumnes que ho seran dels dos cursos A i B . Fes servir un arxiu CSV per realitzar aquesta creació en bloc. Vés a `Administració del lloc > Usuaris > Comptes > Carrega usuaris` i segueix els passos que et marca. 
   
   **NOTA:** Per saber el contingut que hauria de tenir aquest fitxer, consulteu més abaix a la secció `Usuaris`.
   
   **c)** Elimina dos dels deu alumnes creats a l'apartat anterior fent servir l'opció `Administració del lloc > Usuaris > Accions amb usuaris en bloc`

**5.** Ara matricula aquests usuaris als diferents cursos.

   **a)** Fes que al curs A no hi hagi possibilitat d'inscripció (és a dir, que només es permeti l'accés de visitant de manera que el curs sigui totalment públic sense control d'usuaris -ni alumnes ni professors-). D'altra banda, fes que al curs B es necessiti registre manual d'usuaris (és a dir, que sigui l'administrador -tu- qui matriculi cada usuari al curs, ja sigui com a professor o com a alumne). Tot això ho pots fer des de `Administració del curs > Ususaris > Mètodes d'inscripció`. Si no surt algun mètode d'inscripció disponible, has d'activar-lo a: `Administració de lloc > Connectors > Autenticació > Gestió de l'autenticació`

   **b)** Assigna com a professor del curs B l'usuari "Bob" i com a alumnes a tots els que fas afegir des de l'arxiu CSV Tot això ho pots fer anant a `Administració del curs > Usuaris inscrits > Inscriure`.

   **c)** Comprova que efectivament, el contingut del curs A (afegit per l'administrador del sistema -és a dir, tu- estigui disponible públicament i que per accedir al curs B s'hagi d'iniciar sessió amb un usuari registrat (alumne o professor)

**6.** Canvia l'aparença estètica del teu lloc. Concretament, descarrega't i activa un tema diferent dels que venen per defecte i prova de canviar també la capçalera i el peu de pàgina del lloc. Això ho pots fer primer anant a `Administració del lloc > Connectors > Instal·lar complement` i després a `Administració del lloc > Aparença > Temes > Selector de temes` Sempre pots fer servir l'enllaç `Canvi de rol` del menú de la dreta per observar com es veuria el lloc sent alumne, professor, etc.

**7.** Assigna un professor i matricula alumnes al curs A.

**8.** Amb el professor afegeix contingut al curs A. Afegeix diferents tipus d’activitats i recursos. Crea una tasca amb data d’entrega oberta que demani la càrrega d’un fitxer PDF.

**9.** Entra amb un alumne i comprova que pots lliurar la tasca.

## Continguts
En el curs A crea una UF amb 2 NF dintre. En aquesta UF crea diverses activitats.

Botó Activar Edició (a dalt a la dreta). Una UF es pot crear amb una etiqueta i movent a la dreta el seu contingut. Es pot canviar el Format del curs a `Temes` a `Administració del Curs > Editar Curs > Format del Curs`

Fes servir el moodle del puig com a referència. Han d’haver tant activitats magistrals com evaluables (com a mínim una entrega i un questionari). Clona (importa) el curs sencer al curs B `Administració del Curs > Importar` (des del curs B)

## Qualificació
En el curs A fes que un alumne completi totes les tasques evaluables (entrant amb la seva compta). Calificales amb el professor i configura el calificador per a que doni una nota de la UF automàticament a `Administració del Curs > Configuració de qualificacions`.

Crea una insignia i atorga-la a aquest alumne des de `Administració del Lloc > Insígnies`

## Qüestionaris
Crea un qüestionari i afegeix preguntes del banc de preguntes. Crea diferents categories dintre del banc de preguntes i diverses preguntes en cada categoria. A l'hora de crear el qüestionari has de seleccionar les preguntes del banc de preguntes. Respon les preguntes del qüestionari amb un usuari estudiant i mira les qualificacions amb l'usuari professor.

## Importar i exportar un curs
Entra a la zona `Administració > Cursos > Còpies` i fes una còpia de seguretat del teu curs. Després envia aquest fitxer a un company i que l'importi al seu moodle. Has d'importar al teu moodle un altre curs d'un company. 

## Personalització
Descarrega i aplica un tema nou al teu LMS.

Edita també tant la capçalera (header) com el peu (footer) i la pàgina principal (Front page) Posa-li un logotip al teu moodle.

## Seguretat
Baneja una IP i aplica una política de seguretat. Pots posar la que vulguis però l’hauràs de justificar.

**NOTA:** Capturar per a cada pregunta, les imatges que han de mostrar la resposta, i tenir-les a mà, farà que sigui molt més fàcil contestar les preguntes el dia de l’avaluació!

## Usuaris
Crea 10 usuaris alumnes i un usuari professor posant-li dades.
`Administració del Lloc > Usuaris > Crear Usuari / Pujar Usuaris` (de cop amb un arxiu csv, hi ha un model de csv al final del document).

Assigna al professor a A i B. Matricula els alumnes a A mitjançant `Administració del Curs > Usuaris > Usuaris Matriculats` i connectat amb un alumne i matricula'l a B amb la contrassenya.




![Captura de pantalla de 2025-03-13 10-34-34](https://github.com/user-attachments/assets/2b1cffb9-c47e-4095-8720-d1c549c48bc8)


![Captura de pantalla de 2025-03-13 10-34-34](https://github.com/user-attachments/assets/91971394-ebfa-484a-a591-2e16d04bc84e)

![imatge](https://github.com/user-attachments/assets/23633f0d-32f1-4969-8d3a-44a8490edb6b)
![Captura de pantalla de 2025-03-13 10-34-34](https://github.com/user-attachments/assets/b0488d9d-8160-4415-bf2a-b2f6ca18fe15)

![Captura de pantalla de 2025-03-14 14-20-53](https://github.com/user-attachments/assets/631a3aa0-6783-4d40-8f06-d42dcdbdc411)
![Captura de pantalla de 2025-03-14 14-35-55](https://github.com/user-attachments/assets/77d7bf0d-35f3-4d22-a048-08c71369ac27)
![Captura de pantalla de 2025-03-13 10-41-17](https://github.com/user-attachments/assets/9dbfa80c-c828-41f3-a169-9372747af144)
![Captura de pantalla de 2025-03-13 10-41-49](https://github.com/user-attachments/assets/583ecc84-6e11-40bd-96dd-05a5bc57dac6)
![Captura de pantalla de 2025-03-13 10-42-25](https://github.com/user-attachments/assets/d466ce2f-13ba-4e5a-9d16-a286fee2db61)
![Captura de pantalla de 2025-03-13 10-45-54](https://github.com/user-attachments/assets/b82ea113-deb7-4e98-9e52-d45c14e6c405)
![Captura de pantalla de 2025-03-13 10-48-03](https://github.com/user-attachments/assets/05972501-23e6-4564-967c-296f239647f6)
![Captura de pantalla de 2025-03-13 10-48-09](https://github.com/user-attachments/assets/79d02706-f223-4adb-b3d6-e532d4df52bd)
![Captura de pantalla de 2025-03-13 10-50-22](https://github.com/user-attachments/assets/0859f0d6-e93b-49fc-b169-339c7770207f)
![Captura de pantalla de 2025-03-13 10-57-00](https://github.com/user-attachments/assets/52c88349-8491-4fef-a6bd-7f6342355053)
![Captura de pantalla de 2025-03-13 11-02-36](https://github.com/user-attachments/assets/8dc37c21-ea98-480e-9f8e-a240af1b6ec7)
![Captura de pantalla de 2025-03-13 11-03-22](https://github.com/user-attachments/assets/590b4f93-e767-49ab-b2dc-e8b37ecd8506)
![Captura de pantalla de 2025-03-13 11-03-41](https://github.com/user-attachments/assets/e0d809df-2dde-4b71-b766-e582373ae9a9)
![Captura de pantalla de 2025-03-13 11-04-17](https://github.com/user-attachments/assets/47119b7d-2746-4a86-b30e-5e53f69ad362)
![Captura de pantalla de 2025-03-13 11-04-26](https://github.com/user-attachments/assets/eace3ce3-49b0-43b3-8940-4862d26d46ec)
![Captura de pantalla de 2025-03-13 11-05-31](https://github.com/user-attachments/assets/8e1ab748-e674-4020-8e81-7254c0da9525)
![Captura de pantalla de 2025-03-13 11-06-12](https://github.com/user-attachments/assets/732cb07f-6833-4c24-9eec-326ed4de9071)
![Captura de pantalla de 2025-03-13 11-06-50](https://github.com/user-attachments/assets/2576f060-bb21-4d8f-a733-f62c4615cff9)
![Captura de pantalla de 2025-03-14 12-46-59](https://github.com/user-attachments/assets/7f1eea6c-727a-4a73-a203-43c3abcaebff)
![Captura de pantalla de 2025-03-14 13-47-31](https://github.com/user-attachments/assets/bedfc9a9-f6bb-4386-a2ae-d1e5fdde2949)
![Captura de pantalla de 2025-03-14 13-54-41](https://github.com/user-attachments/assets/91dc3089-35bc-4a40-9633-61a85fe06d6c)
![Captura de pantalla de 2025-03-14 14-05-30](https://github.com/user-attachments/assets/b5ff7471-096b-4c6a-81c4-7256f4131660)
![Captura de pantalla de 2025-03-14 14-06-19](https://github.com/user-attachments/assets/3ffb1a91-b82e-4590-bebe-3de55b89d33b)
![Captura de pantalla de 2025-03-14 14-19-44](https://github.com/user-attachments/assets/f8a4ef7a-a577-4865-947e-0edbe8b5d695)
![Captura de pantalla de 2025-03-14 14-19-57](https://github.com/user-attachments/assets/c92df75c-c536-444c-9c6f-6e90c24d554f)
![Captura de pantalla de 2025-03-14 14-20-22](https://github.com/user-attachments/assets/a9559d65-895e-47f5-bbdb-5abc6d40b5ad)
![imatge](https://github.com/user-attachments/assets/c4a9156f-7c72-4333-b3f3-4dde6aac3a0d)

![Captura de pantalla de 2025-03-28 14-12-47](https://github.com/user-attachments/assets/3fd94813-5a54-46b2-8552-19e9715dc706)
![Captura de pantalla de 2025-03-27 13-27-39](https://github.com/user-attachments/assets/61f3f25e-c51b-4567-915b-d7858fb28544)
![Captura de pantalla de 2025-03-28 14-12-47](https://github.com/user-attachments/assets/d05b648c-5596-47e1-adfb-8242b8e73908)
![Captura de pantalla de 2025-03-28 14-18-31](https://github.com/user-attachments/assets/a9350b7e-096e-43af-b1d2-f51fb83eb35c)![Imatge enganxada](https://github.com/user-attachments/assets/c4c1b875-52cf-46e7-ad0f-175eda77d661)
![Captura de pantalla de 2025-03-19 12-28-30](https://github.com/user-attachments/assets/0f5de96f-8b87-44bf-ac06-55e904110133)
![Captura de pantalla de 2025-03-20 13-44-53](https://github.com/user-attachments/assets/4907a20a-6110-4f24-918e-fb2a27f57060)
![Captura de pantalla de 2025-03-20 13-46-16](https://github.com/user-attachments/assets/06d42c9c-1da5-4152-b624-b662977b37e2)
![Captura de pantalla de 2025-03-20 13-46-40](https://github.com/user-attachments/assets/cf0148ae-5b1c-45bf-bc11-017890469d8d)
![Captura de pantalla de 2025-03-20 13-47-30](https://github.com/user-attachments/assets/33b7d213-e65e-4656-9116-7c91143d4536)
![Captura de pantalla de 2025-03-20 13-56-20](https://github.com/user-attachments/assets/e1f9f649-6583-4a75-83c9-c0edc8322119)
![Captura de pantalla de 2025-03-20 14-07-34](https://github.com/user-attachments/assets/379aa575-231a-41ae-933c-0a0a4b239ecd)
![Captura de pantalla de 2025-03-20 14-10-57](https://github.com/user-attachments/assets/df7807c5-b3d4-4035-ba07-04c6439654ba)
![Captura de pantalla de 2025-03-20 14-13-41](https://github.com/user-attachments/assets/b2dec655-8506-4b28-b554-392cc095e330)
![Captura de pantalla de 2025-03-20 14-16-46](https://github.com/user-attachments/assets/4b1c009a-622a-496f-b39e-4cb426b02a09)
![Captura de pantalla de 2025-03-20 14-34-04](https://github.com/user-attachments/assets/b5504f0a-6c46-4716-8ce7-f62a3b6aac36)

![Captura de pantalla de 2025-03-28 14-26-07](https://github.com/user-attachments/assets/5f725926-b827-4c84-8248-d7623382e04a)

![Captura de pantalla de 2025-03-28 14-26-07](https://github.com/user-attachments/assets/c1eb09ec-2846-4396-93d3-fef2be8c4d44)
![Captura de pantalla de 2025-02-21 14-25-45](https://github.com/user-attachments/assets/c38d23a7-a144-445f-bc29-81d6ef81c78c)![Captura de pantalla de 2025-02-21 14-17-22](https://github.com/user-attachments/assets/7f47033c-2dad-4907-8343-f3d7f8eb82e5)
![Captura de pantalla de 2025-02-21 14-24-56](https://github.com/user-attachments/assets/6eae30d6-7706-4670-beb3-626376169e9e)

![Captura de pantalla de 2025-02-21 14-27-01](https://github.com/user-attachments/assets/57a51ca5-3c4d-4d1d-97a1-5d3a06d76892)
![Captura de pantalla de 2025-02-21 14-27-15](https://github.com/user-attachments/assets/877c29bb-0f97-40eb-af48-110d5dc5a28b)

![Captura de pantalla de 2025-02-27 14-22-34](https://github.com/user-attachments/assets/43e361cd-c6c1-4dd2-8a60-d5bc22bda4db)
![Captura de pantalla de 2025-02-27 14-28-08](https://github.com/user-attachments/assets/79702f20-a934-4c2d-8baf-c2cf03f2a7f2)
![Captura de pantalla de 2025-02-27 14-28-16](https://github.com/user-attachments/assets/4f6e9ea1-6475-4e4d-abda-44af2de5e1e8)
![Captura de pantalla de 2025-02-27 14-28-29](https://github.com/user-attachments/assets/0bbd1eb7-81d0-42bd-b314-1110ad38c4ef)
![Captura de pantalla de 2025-02-27 14-35-03](https://github.com/user-attachments/assets/1a2fee80-447d-42f2-984c-1d6e2e62cc9f)



