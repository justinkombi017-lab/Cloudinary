# Galerie Photos - Cloudinary

**Auteur :** Justin Kombi - Butembo, Nord-Kivu
**Projet :** Site web de galerie d'images hébergées sur Cloudinary

## 1. Présentation du projet

Ce projet est un site web vitrine qui présente une galerie de 3 photos de chambres et de suites de luxe.
Le but est de montrer comment héberger des images sur le cloud avec Cloudinary et les afficher sur un site web simple, rapide et responsive.

Le site affiche :
- Chambre Rouge Luxe
- Dressing Moderne
- Suite de Luxe

## 2. Technologies utilisées

- **HTML5** : Structure de la page
- **CSS3** : Design, mise en page, responsive
- **Cloudinary** : Hébergement et optimisation des images
- **GitHub** : Hébergement du code source
- **GitHub Pages** : Publication du site en ligne
- **VS Code** : Éditeur de code

## 3. Comment Cloudinary est utilisé

1. Je me suis créé un compte gratuit sur Cloudinary.
2. J'ai téléversé mes 3 images dans le Media Library de Cloudinary.
3. Cloudinary a généré pour chaque image une URL publique (CDN) qui commence par `https://res.cloudinary.com/qlyft4zy/image/upload/...`
4. J'ai copié ces 3 URL et je les ai collées dans le fichier `index.html` dans les balises `<img src="...">`.
5. Avantage : Les images ne sont pas stockées dans le dossier du projet, elles sont chargées depuis les serveurs de Cloudinary, ce qui rend le site plus léger, plus rapide et accessible partout.

Exemple d'URL utilisée :
`https://res.cloudinary.com/qlyft4zy/image/upload/v.../chambre.jpg`

## 4. Instructions pour exécuter le projet localement

1. Cloner le dépôt :