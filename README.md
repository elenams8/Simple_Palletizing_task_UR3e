# Simple_Palletizing_task_UR3e
En aquest repositori, es proporcionen els fitxers necessaris per realitzar una tasca simple de paletització.

L'eina utilitzada és la Robotiq E-pick. Cal comentar que el robot disposa d'un raspall de dents elèctric fixat a l'extrem de l'element terminal (per realitzar altres tasques) i per això, el fitxer d'instal·lació es configura els paràmetres en conseqüència.
L’objectiu del programa és manipular objectes en un palet irregular que conté 5 elements. Hi ha dos objectes que s’han de moure, i l’objectiu és trobar aquests objectes en la seqüència 1 i reposicionar-los en la seqüència 2. 
Per assolir aquesta tasca es pot enfocar de dues maneres diferents:
* Programació per bucle: Aquest enfocament es basa a crear un bucle per recórrer la primera seqüència i el programa itera els elements, movent-se entre diferents posicions amb distàncies especificades. El programa continua fins a trobar els dos objectes  i els ha reposicionat en la seqüència 2.
* Ús de la plantilla paletització que ofereix el programa: com a alternativa, es pot utilitzar la plantilla de paletització proporcionada pel programa. Aquesta plantilla simplifica la tasca de l'usuari. Primer cal definir la primera paleta (seqüència 1) seguint els passos específics dins de la plantilla. A continuació, es crea un subprograma per a la segona paleta (seqüència 2). Al programa principal, quan l'ordre de la paleta per a la seqüència 1 detecta un objecte, crida al subprograma per a la seqüència 2. Aquest procés es repeteix fins que els dos objectes es troben i es reposicionen.

Per acompanyar cadascun dels codis, es comparteix un vídeo explicatiu del programa. Podeu observar que el resultat és el mateix.
El podeu veure en el següent enllaç:
* Enllaç programació per Bucle: https://youtu.be/Qu46bOYWBGQ 
* Enllaç Programació per Plantilles: https://youtu.be/a2i_U8Gam3c



