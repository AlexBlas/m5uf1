##Característiques dels llenguatges més difosos

Existeixen molts llenguatges de programació diferents, fins al punt que moltes tecnologies tenen el seu llenguatge propi. Cada un d’aquests llenguatges té un seguit de particularitats que el fan diferent de la resta.

Els llenguatges de programació més difosos són aquells que més es fan servir en cadascun dels diferents àmbits de la informàtica. En l’àmbit educatiu, per exemple, es considera un llenguatge de programació molt difós aquell que es fa servir a moltes universitats o centres educatius per a la docència de la iniciació a la programació.

La **programació estructurada** utilitza únicament tres estructures: 
* Seqüència 
* Selecció 
* Iteració

D’aquesta forma les característiques de la programació estructurada són: la claredat, el teorema de l’estructura i el disseny descendent.

**Clatetat**

Hi haurà d’haver prou informació al codi per tal que el programa pugui ser entès i verificat: comentaris, noms de variables comprensibles i procediments entenedors... Tot programa estructurat pot ser llegit des del principi a la fi sense interrupcions en la seqüència normal de lectura.

**Teorema de l’estructura**

Demostra que tot programa es pot escriure utilitzant únicament les tres estructures bàsiques de control:
* Seqüència: instruccions executades successivament, una darrere l’altra.
* Selecció: la instrucció condicional amb doble alternativa, de la forma “si condició, llavors SentènciaA, sinó SentènciaB” (IF).
* Iteració: el bucle condicional “mentre condició, fes SentènciaA”, que executa les instruccions repetidament mentre la condició es compleixi (FOR, WHILE).

**Disseny descendent**

El disseny descendent és una tècnica que es basa en el concepte de “divideix i venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un nivell més abstracte i finalitzant en un nivell de detall.

**Programació modular**
___
Quan es parla de programació modular, ens referim a la divisió d’un programa en parts més manejables i independents. 

En la majoria de llenguatges, els mòduls es tradueixen a:

* **Procediments:** són subprogrames que duen a terme una tasca determinada i retornen 0 o més d’un valor. S’utilitzen per estructurar un programa i millorar la seva claredat.
* **Funcions:** són subprogrames que duen a terme una determinada tasca i retornen un únic resultat o valor. S’utilitzen per crear operacions noves que no ofereix el llenguatge.

**Tipus abstractes de dades (TAD)**
El **tipus de dades** d’una variable és el conjunt de valors que lavariable pot assumir.

Els llenguatges de programació assumeixen un nombre determinat de tipus de dades, que pot variar d’un llenguatge a un altre; així, en Pascal tenim els enters, els reals, els booleans, els caràcters... Aquests tipus de dades són anomenats ***tipus de dades bàsics***.

Tenim  la possibilitat de poder definir *tipus abstractes* de dades, on el programador pot definir un nou tipus de dades i les seves possibles operacions.

**Característiques de la programació orientada a objectes**
___
**L’orientació a objectes(OO)** és un paradigma de construcció de programes basat en una abstracció del món real.

En un programa orientat a objectes, l’abstracció no són els procediments ni les funcions, són els objectes. Aquests objectes són una representació directa d’alguna cosa del món real, com ara un llibre, una persona, una organització, una comanda, un empleat...

**Un objecte** és una combinació de dades (anomenades atributs) i mètodes(funcions i procediments) que ens permeten interactuar amb ell. En OO, doncs, els programes són conjunts d’objectes que interactuen entre ells a través de missatges (crides a mètodes).

Els llenguatges de POO (programació orientada a objectes) són aquells que implementen més o menys fidelment el paradigma OO. La programació orientada a objectes es basa en la integració de 5 conceptes: abstracció, encapsulació, modularitat, jerarquia i polimorfisme, que és necessari comprendre i seguir de manera absolutament rigorosa.

**Abstracció**

És el procés en el qual se separen les propietats més importants d’un objecte de les que no ho són. És a dir, per mitjà de l’abstracció es defineixen les característiques essencials d’un objecte del món real, els atributs i comportaments que el defineixen com a tal, per després modelar-lo en un objecte de programari.

En la tecnologia orientada a objectes l’eina principal per suportar l’abstracció és la classe. Es pot definir una classe com una descripció genèrica d’un grup d’objectes que comparteixen característiques comunes, les quals són especificades en els seus atributs i comportaments.

**Encapsulació**

Permet als objectes triar quina informació és publicada i quina informació ésamagada a la resta dels objectes. Per això els objectes solen presentar els seus mètodes com a interfícies públiques i els seus atributs com a dades privades o protegides.

Les característiques que espoden atorgar són:

* Públic: Qualsevol classe pot accedir a qualsevol atribut o mètode declarat com a públic i utilitzar-lo.
* Protegit: Qualsevol classe heretada pot accedir a qualsevol atribut o mètode declarat com a protegit a la classe mare i utilitzar-lo.
*  Privat: Cap classe no pot accedir a un atribut o mètode declarat com a privati utilitzar-lo.

**Modularitat**

Permet poder modificar les característiques de cada una de les classes que defineixen un objecte.

**Jerarquia**

Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un sistema complex són **l’herència** i **l’agregació.**

**El polimorfisme**

És una característica que permet donar diferents formes a un mètode, ja sigui en la definició com en la implementació.

