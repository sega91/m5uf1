##___1.2. Codi font, codi objecte i codi excutable: màquines virtuals___

Un cop s’ha acabat d’escriure el programa, el conjunt de fitxers de text
resultants, on es troben les instruccions, es diu que contenen el **codi font**.
Aquest codi font pot ser des d’un nivell molt alt, molt a prop del llenguatge
humà, fins a un de nivell més baix, més proper al codi de les màquines, com
ara el codi assemblador

El **codi objecte** és el codi font traduït (pel compilador) a codi màquina, però
aquest codi encara no pot ser executat per l’ordinador
 
El **codi executable** és la traducció completa a codi màquina, duta a terme per
l’enllaçador (en anglès, linker). El codi executable és interpretat directament
per l’ordinador

L’ **enllaçador** és l’encarregat d’inserir al codi objecte les funcions de les llibreries
que són necessàries per al programa i de dur a terme el procés de muntatge
generant un arxiu executable

Una **llibreria** és un col·lecció de codi predefinit que facilita la tasca del programador
a l’hora de codificar un programa.

La **compilació** consta de dues fases:

• La primera parteix del codi font a un llenguatge intermedi obtenint un
programa equivalent amb un menor nivell d’abstracció que l’original i que
no pot ser directament executat.

• La segona fase tradueix el llenguatge intermedi a un llenguatge comprensible
per la màquina.
