[Français](#français) | [English](#english)

---

# Français

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
```text
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
   Chaque page correspond à un fichier HTML séparé (`index.html`, `equipe.html`, etc.), lié à des fichiers CSS (communs entre les versions française et anglaise) pour le style.

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

Pour les futurs membres ou responsables qui reprendront le site :

1. **Accès au dépôt GitHub**
   - Assurez-vous d’avoir un compte GitHub.
   - Cloner ou télécharger le projet complet.  
   - Pour cloner le dépôt sur votre machine :  
     ```bash
     git clone [https://github.com/](https://github.com/)<username>/amu-website.git
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
   - En cas de transfert à un nouveau responsable, il faudra s’assurer que le domaine pointe toujours vers GitHub Pages et qu'il soit toujours à jour.

---

## Remarques importantes

- **Sauvegardes régulières** : gardez toujours une copie locale du site.
- **Respect du style** : essayez de conserver la cohérence visuelle lors des mises à jour.
- **Documentation** : toute modification importante doit être documentée pour les prochains responsables.

---

## Contact

Pour toute question, contactez [amu.udem@gmail.com](mailto:amu.udem@gmail.com).

---

# English

# Malagasy Association at UdeM (AMU) Website

## Description

This website is the official portal of the **Malagasy Association at the Université de Montréal (AMU)**.  
Its purpose is to inform, guide, and connect students and the Malagasy community.

**Main Objectives:**
- Introduce the association and its members.
- Provide useful resources for students.
- Share events and activities.
- Allow visitors to contact the association easily.

---

## Project Structure
```text
website/
│
├─ assets/ # Images and logos
├─ css/ # CSS files for styling
│ └─ index.css
│ └─ evenements.css
│ └─ contact.css
│ └─ equipe.css
│ └─ ressources.css
├─ fr/ # French HTML files
├─ └─ index.html # Home page
├─ └─ equipe.html # Team presentation
├─ └─ ressources.html # Resources page
├─ └─ evenements.html # Events page
├─ └─ contact.html # Contact page
├─ en/ # English HTML files
├─ └─ index.html # Home page
├─ └─ team.html # Team presentation
├─ └─ ressources.html # Resources page
├─ └─ events.html # Events page
├─ └─ contact.html # Contact page
└─ README.md # This file
```

---

## How the Site Works

1. **HTML Pages**  
   Each page corresponds to a separate HTML file (`index.html`, `equipe.html`, etc.), linked to CSS files (shared between the French and English versions) for styling.

2. **CSS**  
   The CSS files contain all the site's styling (colors, typography, layout, responsive design).

3. **Assets**  
   The `assets/` folder contains all images and logos used on the site.

4. **Navigation**  
   The navigation bar provides easy access to the different pages, along with a button to switch languages.

5. **Contact Form**  
   The contact page includes a simple form so visitors can send messages directly to the association.

---

## Hosting

- The site is **hosted via GitHub Pages**, allowing free and easy deployment.  
- It is connected to **AMU's official domain** for professional and memorable access.

---

## Handover and Maintenance

For future members or leads taking over the site:

1. **GitHub Repository Access**
   - Make sure you have a GitHub account.
   - Clone or download the full project.  
   - To clone the repository onto your machine:  
     ```bash
     git clone [https://github.com/](https://github.com/)<username>/amu-website.git
     ```

2. **Editing the Site**
   - HTML pages can be edited with any text editor or IDE.
   - Styling is centralized in `css/`.
   - Images and logos are in `assets/`.

3. **Publishing Updates**
   - After making changes, commit and push them:  
     ```bash
     git add .
     git commit -m "Update website"
     git push
     ```
   - GitHub Pages will automatically publish the new version of the site.

4. **Connecting the AMU Domain**
   - DNS settings for the domain are already configured.
   - When handing over to a new lead, make sure the domain still points to GitHub Pages and remains up to date.

---

## Important Notes

- **Regular Backups:** Always keep a local copy of the site.
- **Style Consistency:** Try to maintain visual consistency when making updates.
- **Documentation:** Document any major changes for future leads.

---

## Contact

If you have any questions, contact [amu.udem@gmail.com](mailto:amu.udem@gmail.com).
