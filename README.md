# KizNet Service - Site Web

Site web officiel de KizNet Service, votre partenaire technologique à Pointe-Noire, Congo Brazzaville.

## 🌟 Fonctionnalités

- ✅ Design moderne et responsive
- ✅ Animation du titre principal
- ✅ Navigation mobile optimisée
- ✅ Sections : Services, Réalisations, Témoignages, Contact
- ✅ Optimisé pour tous les appareils (mobile, tablette, desktop)

## 🎬 Animation du titre

Le slogan principal s'anime automatiquement entre :
- "On connecte." (bleu)
- "On construit." (noir)
- "On sécurise." (violet)

### Personnalisation
Consultez `GUIDE_ANIMATION.md` pour personnaliser l'animation.

## 📱 Optimisations mobile

- Menu de navigation qui se ferme automatiquement
- Zones de clic augmentées (44px minimum)
- Typographie et espacements optimisés
- Images responsive

Voir `AMELIORATIONS_MOBILE.md` pour plus de détails.

## 📁 Structure du projet

```
kiznet-service/
├── index.html                          # Page principale
├── style.css                           # Styles CSS
├── assets/
│   ├── css/                           # Bibliothèques CSS
│   ├── js/
│   │   ├── main.js                    # JavaScript principal
│   │   └── text-animation-alternative.js  # Animation alternative
│   ├── images/                        # Images du site
│   └── fonts/                         # Polices
├── demo-animations.html               # Démo des animations
├── GUIDE_ANIMATION.md                 # Guide d'utilisation
├── AMELIORATIONS_MOBILE.md            # Documentation mobile
├── ANIMATION_OPTIONS.md               # Options d'animation
└── RESUME_MODIFICATIONS.md            # Résumé des modifications
```

## 🚀 Démarrage rapide

1. Ouvrez `index.html` dans votre navigateur
2. Pour tester les animations : ouvrez `demo-animations.html`

## 🎨 Personnalisation

### Changer la vitesse de l'animation
Dans `assets/js/main.js` :
```javascript
setInterval(rotateText, 3000); // 3000 = 3 secondes
```

### Changer les couleurs
Dans `style.css` :
```css
.animated-text:nth-child(1) {
  color: var(--primary); /* Bleu */
}
```

Voir `GUIDE_ANIMATION.md` pour plus d'options.

## 📖 Documentation

- **Guide d'animation** : `GUIDE_ANIMATION.md`
- **Options d'animation** : `ANIMATION_OPTIONS.md`
- **Améliorations mobile** : `AMELIORATIONS_MOBILE.md`
- **Résumé complet** : `RESUME_MODIFICATIONS.md`

## 🌐 Navigateurs supportés

- ✅ Chrome (dernière version)
- ✅ Firefox (dernière version)
- ✅ Safari (dernière version)
- ✅ Edge (dernière version)
- ✅ Opera (dernière version)

## 📱 Appareils supportés

- ✅ Smartphones (iOS, Android)
- ✅ Tablettes (iPad, Android)
- ✅ Desktop (Windows, Mac, Linux)

## ♿ Accessibilité

- Support de `prefers-reduced-motion`
- Zones de clic minimum 44px
- Navigation au clavier
- Contraste des couleurs respecté

## 🔧 Technologies utilisées

- HTML5
- CSS3 (Animations, Flexbox, Grid)
- JavaScript (Vanilla)
- Bootstrap 5
- LineIcons

## 📞 Contact

**KizNet Service**
- 📍 Pointe-Noire, Congo Brazzaville
- 📱 WhatsApp : +242 06 931 747
- 🌐 Site web : [En cours]

## 📄 Licence

© 2026 KizNet Service. Tous droits réservés.

---

**Version** : 2.0  
**Dernière mise à jour** : Avril 2026  
**Statut** : ✅ Production ready

---

## Credits

Template original : [Business Template by Ayro UI](https://ayroui.com/)  
Personnalisation et développement : KizNet Service
