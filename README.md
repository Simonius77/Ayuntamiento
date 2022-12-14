# Ayuntamiento
Ejercicio de creación archivo xml
Pràctica avaluable UF1NF1
Som els responsables del departament de noves tecnologies de l’Agència Tributària. El seu president ha decidit que vol recopilar la informació del cens dels seus 25.000 habitants. Per fer-ho s’ha pensat que cada un dels ajuntaments del país facin arribar a l’agència un fitxer digital amb les dades dels seus habitants. Això comporta un problema, i és que cada ajuntament ha pres nota del seu cens amb les eines informàtiques que ha cregut més adient, i per tant les dades no estan en un format homogeneïtzat. Com a cap de departament has parlat amb el president de l’Agència Tributària i li has transmès amb seguretat que no hi haurà cap problema per obtenir les dades. Has pensat a demanar a cada un dels ajuntaments que converteixin les seves dades a format XML i te les facin arribar en un fitxer.
Tots els fitxers que t’enviïn hauran de tenir una estructura similar per tal que posteriorment es puguin introduir les dades a la base de dades.
En concret per a cada persona es vol incloure la següent informació:
- Nom i Cognoms
- Telèfon
- Sexe
- Edat
- Correu electrònic
- DNI
En funció de l’edat de les persones es classifiquen en quatre grups dels quals necessitarem diferents informacions:
Bressol – Menys de 6 anys
- Escoles bressol: nom de totes les escoles bressols a les que ha anat (existeix la possibilitat de que no vagi a cap).
- Escoles: escoles a les que ha assistit la persona. De cada escola necessitem la data d’inici i la data que va deixar d’anar. En cas de que sigui l’actual no hi haurà data de finalització.
- Pares: nom dels pares o tutors. Hi poden haver 1, 2 o 3 noms diferents.
Departament d’Informàtica
Sistemes Microinformàtics i Xarxes | M04 Llenguatges de marques
Pàgina 2
Primària – Entre 6 i 18 anys
- Escoles: de l’escola actual de la persona cal tenir la següent informació:
o Curs que realitza
o Classe a la que assisteix
o Assignatures a les que està matriculat (per a cada assignatura en volem saber, el nom, el professor/a i la nota de l’assignatura.
Adult – Entre 18 i 60 anys
- Empresa en la que treballa i sucursal si en té.
- El càrrec que ocupa dintre de l’empresa i el sou
- Data inici i data finalització de les seves vacances.
Sènior – Més de 60 anys
- Volem saber si està jubilat o no
- Del jubilat volem saber la seva pensió.
- En cas de no estar jubilat volem saber la seva ocupació.
01. Genera un codi XML que contingui la informació de quatre persones. Aquestes quatre persones han de ser una de cada tipus especificat.
