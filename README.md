# Carte d'Invitation de Mariage

Une carte d'invitation de mariage moderne et élégante inspirée du style de [mariage-sarahmaxime.com](https://mariage-sarahmaxime.com/love).

## 🎨 Caractéristiques

- **Design moderne et élégant** avec des dégradés et des animations
- **Compteur de temps** jusqu'à la date du mariage
- **Navigation fluide** entre les sections
- **Formulaire de réponse** interactif
- **Design responsive** pour tous les appareils
- **Animations au scroll** pour une expérience immersive
- **Boutons d'itinéraire** intégrés avec Google Maps

## 📁 Structure du projet

```
├── index.html          # Page principale
├── styles.css          # Styles CSS
├── script.js           # JavaScript pour les interactions
└── README.md           # Documentation
```

## 🚀 Installation et utilisation

1. **Téléchargez** tous les fichiers dans un dossier
2. **Ouvrez** `index.html` dans votre navigateur
3. **Personnalisez** le contenu selon vos besoins

## ⚙️ Personnalisation

### Modifier la date du mariage

Dans `script.js`, ligne 2 :
```javascript
const targetDate = new Date('2025-06-17T13:45:00').getTime();
```

### Changer les informations du mariage

Modifiez le contenu dans `index.html` :

- **Noms des familles** : Section "Houppa"
- **Dates et heures** : Toutes les sections
- **Adresses** : Toutes les sections
- **Informations de contact** : Section "Shabbat Hatan"

### Personnaliser les couleurs

Dans `styles.css`, vous pouvez modifier :
- **Couleur principale** : `#d4af37` (or)
- **Couleur secondaire** : `#f4d03f` (jaune doré)
- **Dégradés** : Modifiez les `linear-gradient`

### Ajouter des images

Pour ajouter des photos :
1. Créez un dossier `images/`
2. Ajoutez vos images
3. Modifiez le HTML pour inclure les images

## 📱 Fonctionnalités

### Compteur de temps
- Affiche les jours, heures, minutes et secondes jusqu'au mariage
- Se met à jour automatiquement
- S'arrête à zéro quand la date est atteinte

### Navigation
- Menu fixe en haut de page
- Défilement fluide entre les sections
- Navigation responsive

### Formulaire de réponse
- Champs pour nom et prénom
- Boutons radio pour chaque événement
- Zone de texte pour message personnel
- Validation des champs

### Boutons d'itinéraire
- Ouvrent Google Maps avec l'adresse
- Fonctionnent sur tous les appareils

## 🎯 Sections incluses

1. **Hero** - Compteur principal
2. **Mairie** - Cérémonie civile
3. **After Mairie** - Cocktail après la mairie
4. **Houppa** - Cérémonie religieuse
5. **Soirée** - Réception du soir
6. **Shabbat Hatan** - Weekend de célébration
7. **Coupon Réponse** - Formulaire de réponse

## 🔧 Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Styles modernes avec Flexbox et Grid
- **JavaScript ES6+** - Interactions et animations
- **Google Fonts** - Typographies élégantes
- **Font Awesome** - Icônes

## 📧 Envoi des réponses

Le formulaire collecte les données mais ne les envoie pas automatiquement. Pour envoyer les réponses :

### Option 1 : Email
Ajoutez un service comme EmailJS ou Formspree

### Option 2 : Base de données
Intégrez une API backend (Node.js, PHP, etc.)

### Option 3 : Google Sheets
Utilisez Google Apps Script pour envoyer vers Google Sheets

## 🌐 Déploiement

### Hébergement gratuit
- **GitHub Pages** : Parfait pour les sites statiques
- **Netlify** : Déploiement automatique depuis Git
- **Vercel** : Performance optimisée

### Hébergement payant
- **OVH** : Hébergement français
- **Hostinger** : Bon rapport qualité/prix
- **SiteGround** : Support excellent

## 📞 Support

Pour toute question ou personnalisation :
- Modifiez les fichiers selon vos besoins
- Testez sur différents navigateurs
- Vérifiez la responsivité sur mobile

## 📄 Licence

Ce projet est libre d'utilisation pour des mariages personnels.

---

**Créé avec ❤️ pour célébrer l'amour** 