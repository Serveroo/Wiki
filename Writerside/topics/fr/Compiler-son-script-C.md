# Compiler son script C

Le but de cette page est de vous permettre de compiler votre script C.

- Activation du sous-sytème Windows pour Linux

Ouvrez la fenêtre 'Activer ou désactiver des fonctionnalités Windows' et cochez la case *Sous-sytème Windows pour Linux*
![fonctionnalites.png](fonctionnalites.png)

- Mise à jour de WSL

Ouvrez une fenêtre Powerhsell en tant qu'administrateur. Rentrez la commande suivante :
![wsl.png](wsl.png)

- Installation d'Ubuntu 24.04

Dans Microsoft Store, installez Ubuntu 24.04.
![ubuntu.png](ubuntu.png)


- Set up d'un compte Ubuntu

Lancez l'application Ubuntu 24.04 puis créez votre compte en rentrant un nom d'utilisateur et un mot de passe.
![compte.png](compte.png)

- Installation de GCC

Déplacez-vous dans le dossier tmp en exécutant la commande suivante : ```` cd /tmp/ ````.
Ensuite, installez gcc :
![gcc.png](gcc.png)

- Ajout du script C

Allez dans l'explorateur de fichier, dans Ubuntu 24.04, puis dans Linux, ensuite tmp et copiez votre fichier C.
![doc.png](doc.png)

- Compilation du script

Executez la commande suivante : ```` gcc main.c -o main ````

> **Explication**
>
> main.c correspond au nom du script en C
> -o main permet de nommer le fichier de sortie, ici main
>
{style="note"}

Vous pouvez retrouver le fichier compilé dans le même dossier que votre sript :
![compiler.png](compiler.png)


