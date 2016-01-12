##Codi font, codi objecte i codi executable; màquines virtuals.

Un cop s’ha acabat d’escriure el programa, el conjunt de fitxers de text resultants, on es troben les instruccions, es diu que contenen el **codi font.** Aquest codi font pot ser des d’un nivell molt alt, molt a prop del **llenguatge humà**, fins a un de nivell més baix, més proper al **codi de les màquines**, com ara el codi assemblador

La tendència actual és fer ús de llenguatges d’alt nivell.

El procés anomenat **compilació** és la traducció del codi font dels fitxers del programa en fitxers en format binari que contenen les instruccions en un format que el processador pot entendre. El contingut d’aquests fitxers s’anomena **codi objecte**. El programa que fa aquest procés s’anomena **compilador**.

El **codi objecte** és el codi font traduït (pel compilador) a codi màquina, però aquest codi encara no pot ser executat per l’ordinador

El **codi executable** és la traducció completa a codi màquina, duta a terme per l’enllaçador (en anglès, linker). El codi executable és interpretat directament per l’ordinador.

**L’ enllaçador** és l’encarregat d’inserir al codi objecte les funcions de les llibreries que són necessàries per al programa i de dur a terme el procés de muntatge generant un arxiu executable.

####La màquina virtual Java 

La màquina virtual Java (JVM) és l’entorn en què s’executen els programes Java.
És un programa natiu, és a dir, executable en una plataforma específica, que és
capaç d’interpretar i executar instruccions expressades en un codi de bytes
