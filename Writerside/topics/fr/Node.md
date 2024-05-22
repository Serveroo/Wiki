# Node

## Qu'est-ce que Node ?

NodeJS est une plateforme logicielle qui permet d'exécuter du JavaScript côté serveur.

## Comment utiliser mon service Node ?

1. Création de votre compte sur le site serveroo.fr .
2. Rendez-vous sur la page *Produits*, sélectionnez votre pack Starter ainsi que le produit Node.
   Le renouvellement automatique n'est pour l'instant pas disponible. Dans le cas où vous souhaitez prolonger votre expérience, il sera possible de prolonger le service à partir de sa page.

3. Après avoir effectué l'achat, vous serez directement redirigé vers la page de vos différents services. Vous pouvez donc avoir une visualisation de la congiguration de votre service.

4. Pour pouvoir utiliser votre service, vous devez charger votre projet dans la partie fichier du service.
   ![Texte Alternatif](upload.png)

> **Astuce**
>
> Pour faciliter le déploiement de votre projet, vous pouvez le zipper et le charger.
>
{style="note"}

Vous pouvez ensuite extraire votre projet depuis la zone fichier du service.
![Texte Alternatif](zip_node.png)

> **Attention**
> 
> Ne pas mettre le dossier node modules.
> 
> Les noms de fichiers n'acceptent pas les caractères spéciaux ni les espaces.
>
{style="warning"}

Il se peut que le chargement du projet prenne du temps. Nous vous conseillons de redémarrer votre serveur. Vous pouvez également consulter le chargement dans la partie log.
![log.png](log.png)


5. Pour accéder à votre site, il suffit de rentrer l'url de connexion, se trouvant en haut de la page de votre service.
   ![Lien de connexion](lien_connexion_node.png)
   Cela tombera sur le fichier index.js de votre projet.
   Pour accéder à d'autres pages, il suffit de rentrer l'arborescence des fichiers.

> **Attention**
>
> Pour que vous puissez accéder à votre projet, il faut configurer le lancement de votre node sur le port 80
> ou bien ajouter dans la section *Port* de la page de votre service, le port sur lequel votre node fonctionne.
> Si vous ajoutez un nouveau port, alors le lien d'accès de votre service sera constitué du nouveau port externe.
> 
>
{style="warning"}

![Ajout port](ajout_port.png)