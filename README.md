# Site Web de l'Association des Malagasy de l'UdeM (AMU)

## Description

Ce site web est le portail officiel de l’**Association des Malagasy de l’Université de Montréal (AMU)**.  
Il a pour but d’informer, guider et connecter les étudiants et la communauté malgache.

**Objectifs principaux :**
- Présenter l’association et ses membres.
- Fournir des ressources utiles aux étudiants.
- Partager les événements et activités.
- Permettre aux visiteurs de contacter l’association facilement.

---

## Structure du projet
```
website/
│
├─ assets/ # Images et logos
├─ css/ # Fichiers CSS pour le style
│ └─ index.css
│ └─ evenements.css
│ └─ contact.css
│ └─ equipe.css
│ └─ ressources.css
├─ fr/ # Fichiers HTML en français
├─ └─ index.html # Page d’accueil
├─ └─ equipe.html # Présentation de l’équipe
├─ └─ ressources.html # Page de ressources
├─ └─ evenements.html # Page des événements
├─ └─ contact.html # Page contact
├─ en/ # Fichiers HTML en anglais
├─ └─ index.html # Page d’accueil
├─ └─ team.html # Présentation de l’équipe
├─ └─ ressources.html # Page de ressources
├─ └─ events.html # Page des événements
├─ └─ contact.html # Page contact
└─ README.md # Ce fichier
```


---

## Fonctionnement du site

1. **Pages HTML**  
   Chaque page correspond à un fichier HTML séparé (`index.html`, `equipe.html`, etc.), lié à des fichier CSS (commun entre les versions française et anglaise) pour le style.

2. **CSS**  
   Les fichiers CSS contiennent tout le style du site (couleurs, typographie, mise en page, responsive design).

3. **Assets**  
   Le dossier `assets/` contient toutes les images et logos utilisés sur le site.

4. **Navigation**  
   La barre de navigation permet d’accéder facilement aux différentes pages, avec un bouton pour changer la langue.

5. **Formulaire de contact**  
   La page contact contient un formulaire simple pour que les visiteurs puissent envoyer des messages directement à l’association.

---

## Hébergement

- Le site est **hébergé via GitHub Pages**, ce qui permet une mise en ligne gratuite et facile.  
- Il est connecté au **domaine officiel de l’AMU** pour un accès professionnel et facile à retenir.

---

## Transfert et maintenance

Pour les futurs membres ou responsables qui reprendront le site :

1. **Accès au dépôt GitHub**
   - Assurez-vous d’avoir un compte GitHub.
   - Cloner ou télécharger le projet complet.  
   - Pour clonez le dépôt sur votre machine :  
     ```bash
     git clone https://github.com/<username>/amu-website.git
     ```

2. **Modification du site**
   - Les pages HTML peuvent être éditées avec n’importe quel éditeur de texte ou IDE.
   - Le style est centralisé dans `css/`.
   - Les images et logos sont dans `assets/`.

3. **Mise à jour en ligne**
   - Après modifications, committez les changements :  
     ```bash
     git add .
     git commit -m "Mise à jour du site"
     git push
     ```
   - GitHub Pages publiera automatiquement la nouvelle version du site.

4. **Connexion au domaine AMU**
   - Les réglages DNS pour le domaine sont déjà configurés.
   - En cas de transfert à un nouveau responsable, il faudra s’assurer que le domaine pointe toujours vers GitHub Pages et qu'il soit toujours à jour. .

---

## Remarques importantes

- **Sauvegardes régulières** : gardez toujours une copie locale du site.
- **Respect du style** : essayez de conserver la cohérence visuelle lors des mises à jour.
- **Documentation** : toute modification importante doit être documentée pour les prochains responsables.

---

## Contact

Pour toute question sur la maintenance du site, contactez l’actuel responsable à : `amu.udem@gmail.com`.
