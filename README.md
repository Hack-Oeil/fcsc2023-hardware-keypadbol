# FCSC 2023 keypadbol


Lors d'une mission de tests d'intrusion physique sur un site sécurisé, votre client vous demande d'évaluer entre autres un premier accès au site utilisant un keypad et demandant un mot de passe. Seuls 10 essais sont autorisés sinon l'alarme se déclenche.

Vous avez bien sûr pensé à filmer le mot de passe lorsque le vigile le tape, malheureusement il prend ses précautions pour cacher sa main lorsqu'il le tape.

Un accès physique rapide entre deux rondes du vigile vous permet de voir que le keypad est de type “Membrane Keypad” (https://lastminuteengineers.com/arduino-keypad-tutorial/). L'accès à la board qui le pilote étant trop complexe, et n'ayant pas beaucoup de temps, vous décidez d'implanter votre analyseur logique miniature dans un petit espace discret, en le reliant aux fils de la nappe du keypad. Malheureusement, sans accès à la board difficile d'avoir le pinout exact mais vous ferez avec !

Vous récupérez la capture sous forme d'un fichier enregistré ```capture.vcd``` entre les deux rondes suivantes, une fois que le vigile a tapé son mot de passe. Par ailleurs, du social engineering sur le vigile vous permet de savoir qu'il est né en 1980, sa fille en 2018, et qu'il a un chien qui s'appelle “Baba”. Armé de ces informations, vous êtes persuadé de pouvoir “cracker” le mot de passe !

**Note :** La chaîne (insensible à la casse) à trouver ne suit pas le format habituel. Une fois que vous l'aurez trouvée (par exemple : ```abcd```), ajoutez ```FCSC{}``` autour pour obtenir le flag (par exemple : ```FCSC{abcd}```).




Fichier:
- [capture.vcd](capture.vcd)



Auteur : rbe


Origine : [keypadbol](https://hackropole.fr/fr/challenges/hardware/fcsc2023-hardware-keypadbol/)



-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2023-hardware-keypadbol.git

> cd fcsc2023-hardware-keypadbol


-----------


## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2023-hardware-keypadbol/