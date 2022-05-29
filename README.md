# CloudPetProject
Dans le cadre du module "Développement d'applications sur le CLOUD", il nous a été demandé de réaliser un site internet de pétitions (en prenant comme exemple des sites comme https://www.change.org/, https://www.mesopinions.com/petition/ ou encore https://www.unepetition.fr/).
L'objectif ici est d'avoir un site internet qui passe à l'échelle, c'est à dire un site internet capable de supporter une forte affluence (des millions de personnes qui réalisent la même action au même moment par exemple).

Ce fichier README va vous présenter les fonctions réalisées dans le cadre de ce projet, ainsi que les liens pour accéder à l'application web.

Projet réalisé par ANDRE Louis, LE NY Yoann, DAVID Alexis.

# Liens d'accès
Lien d'accès vers l'API : https://petcloudproject.nw.r.appspot.com/

Lien d'accès vers le site internet : https://petcloudproject.nw.r.appspot.com/pet_site/petApp.html#!/

# Fonctions réalisées
- Ajouter une pétition
- Modifier une pétition
- Supprimer une pétition
- Signer une pétition
- Retirer la signature d'une pétition
- Parcourir les pétitions
- Parcourir les top pétitions
- Rechercher une pétition
- Se connecter via Google
- Voir mes pétitions
- Se déconnecter

# Images du datastore
Entité Petition

![image](https://user-images.githubusercontent.com/77157131/170880012-924fbf57-bacb-4eed-b085-924049c37d08.png)

Entité Signature

![image](https://user-images.githubusercontent.com/77157131/170880027-3b78f7ed-84ec-4634-ac87-b1352932b90b.png)

Entité User

![image](https://user-images.githubusercontent.com/77157131/170880043-85b63ff2-6060-4f60-bb97-224901786d09.png)


# Problèmes rencontrés
Connexion Google : Il arrive que nous n'arrivions pas à détecter l'ID lors de la connexion Google, il faut alors recharger la page

Bouton Google : Parfois, lorsqu'on est déconnecté et qu'on souhaite se connecter, el bouton Google ne s'affiche pas, dans ce cas là, appuyer sur F5 devrait résoudre le problème

Affichage top 100 pétitions : Nous avons rencontrés des difficultés à afficher 100 pétitions, nous nous sommes donc restreint à 10 pétitions pour le top 10.

# Conclusion
Ce projet nous a permis de mettre en pratique des notions vues en cours (scalabilité, utilisation d'API, etc...).
L'organisation choisie et appliquée dans notre groupe pour ce projet a été de faire les grosses mises en commun / réunions lors des weekends, et d'avancer au maximum dans la documentation et le developpement lors des fin de journée, après nos stages.
