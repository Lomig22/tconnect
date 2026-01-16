# TCONNECTÉ - Site Web Premium

Site web moderne et responsive pour services de **domotique, alarmes et vidéosurveillance**, inspiré de tconnecte.fr avec un design amélioré et orienté conversion.

## 🎯 Caractéristiques

### Design & UX
- ✅ Design moderne et premium
- ✅ Interface propre et professionnelle
- ✅ Animations subtiles et fluides
- ✅ Responsive mobile-first
- ✅ Optimisé pour la conversion

### Pages
1. **Accueil** - Hero, services, bénéfices, processus, témoignages
2. **Domotique** - Solutions d'automatisation intelligente
3. **Alarmes** - Systèmes de sécurité Ajax Systems
4. **Vidéosurveillance** - Caméras connectées 24/7
5. **Contact** - Formulaire, coordonnées, FAQ, carte

### Technologies
- HTML5 sémantique
- CSS3 moderne (variables CSS, Grid, Flexbox)
- JavaScript vanilla (ES6+)
- Font Awesome 6.5.1 (icônes)
- Google Fonts (Poppins)

## 📁 Structure du projet

```
tconnect-main/
├── index.html              # Page d'accueil
├── domotique.html          # Page Domotique
├── alarmes.html            # Page Alarmes
├── videosurveillance.html  # Page Vidéosurveillance
├── contact.html            # Page Contact
├── css/
│   └── style.css           # Styles principaux
├── js/
│   └── main.js             # Scripts JavaScript
├── images/                 # Images et assets
│   └── placeholder.svg     # Image placeholder
└── README.md               # Documentation

```

## 🎨 Palette de couleurs

**Couleurs officielles TCONNECTÉ :**

```css
--primary-color: #1e3a8a    /* Bleu navy (principal) */
--primary-dark: #1e293b     /* Bleu très foncé */
--accent-color: #ff6b35     /* Orange corail (CTA) */
--gray-900: #0f172a         /* Texte principal */
--gray-600: #475569         /* Texte secondaire */
--white: #ffffff            /* Fond */
```

Ces couleurs correspondent exactement à l'identité visuelle de [tconnecte.fr](https://tconnecte.fr/).

## 🚀 Installation & Utilisation

### Installation simple
1. Téléchargez ou clonez le projet
2. Ouvrez `index.html` dans votre navigateur
3. C'est tout ! Le site est prêt à l'emploi

### Pour le développement
```bash
# Ouvrir avec un serveur local (recommandé)
# Option 1 : Python
python -m http.server 8000

# Option 2 : PHP
php -S localhost:8000

# Option 3 : Node.js (avec http-server)
npx http-server -p 8000
```

Puis ouvrir : `http://localhost:8000`

## ✨ Fonctionnalités JavaScript

### Navigation
- Menu sticky avec effet au scroll
- Menu mobile responsive
- Smooth scroll vers les sections
- Indicateur de page active

### Animations
- Animations au scroll (AOS)
- Fade in/out
- Parallax léger
- Transitions fluides

### Formulaires
- Validation en temps réel
- Messages d'erreur visuels
- Validation email et téléphone
- Système de notification

### Interactions
- FAQ accordion
- Compteurs animés
- Back to top button
- Cookie consent banner
- Barre de progression du scroll

### Performance
- Lazy loading des images
- Debounce/throttle sur les événements
- Monitoring des performances
- Optimisation mobile

## 📱 Responsive Design

Le site est entièrement responsive avec 3 breakpoints principaux :

- **Desktop** : > 1024px
- **Tablet** : 768px - 1024px
- **Mobile** : < 768px

## 🎯 SEO & Accessibilité

### SEO
- Balises meta optimisées
- Structure HTML sémantique
- Hiérarchie des titres (H1-H3)
- URLs descriptives
- Alt text sur les images

### Accessibilité
- Contraste WCAG AA compliant
- Navigation au clavier
- Labels ARIA
- Focus visible
- Textes alternatifs

## 🔧 Personnalisation

### Modifier les couleurs
Éditez les variables CSS dans `css/style.css` :

```css
:root {
    --primary-color: #votre-couleur;
    --accent-color: #votre-couleur;
    /* ... */
}
```

### Ajouter du contenu
1. Ouvrez le fichier HTML concerné
2. Dupliquez une section existante
3. Modifiez le contenu
4. Les styles s'appliquent automatiquement

### Remplacer les images
1. Placez vos images dans le dossier `images/`
2. Mettez à jour les attributs `src` dans les fichiers HTML
3. Formats recommandés : JPG (photos), PNG (logos), SVG (icônes)

## 📊 Performance

### Optimisations incluses
- CSS minifié (en production)
- Images optimisées
- Lazy loading
- Animations GPU-accelerated
- Debouncing des événements scroll

### Temps de chargement cible
- First Contentful Paint : < 1.5s
- Time to Interactive : < 3s
- Lighthouse Score : > 90

## 🌐 Navigateurs supportés

- Chrome/Edge (dernières versions)
- Firefox (dernières versions)
- Safari (dernières versions)
- Opera (dernières versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Copywriting

Le site utilise un ton :
- **Professionnel** mais accessible
- **Rassurant** pour la sécurité
- **Orienté bénéfices** client
- **Simple et direct**

### Exemples d'accroches
- "Votre maison plus sûre, plus intelligente, plus simple"
- "Sécurisez, automatisez et simplifiez votre quotidien"
- "Connectez, surveillez et automatisez en quelques clics"

## 🔄 Mises à jour futures

### Fonctionnalités à ajouter
- [ ] Système de blog
- [ ] Galerie photos interactive
- [ ] Configurateur de pack en ligne
- [ ] Chat en direct
- [ ] Espace client
- [ ] Multilingue (EN, ES)

### Optimisations
- [ ] PWA (Progressive Web App)
- [ ] Mode sombre
- [ ] Compression d'images automatique
- [ ] CDN pour les assets

## 📞 Support

Pour toute question ou assistance :
- **Email** : contact@tconnecte.fr
- **Téléphone** : 07 81 43 78 59
- **Adresse** : 13 Rue des Aubépines, 35410 Domloup

## 📄 Licence

© 2025 TCONNECTÉ - Tous droits réservés

---

## 🎨 Guide de style

### Typographie
- **Titres** : Poppins Bold (700-800)
- **Texte** : Poppins Regular (400)
- **Emphase** : Poppins SemiBold (600)

### Espacements
- **Section padding** : 6rem (desktop), 4rem (mobile)
- **Card padding** : 2rem
- **Gap standard** : 1.5rem

### Ombres
- **Légère** : `0 1px 2px rgba(0,0,0,0.05)`
- **Moyenne** : `0 4px 6px rgba(0,0,0,0.1)`
- **Forte** : `0 20px 25px rgba(0,0,0,0.1)`

### Animations
- **Rapide** : 150ms
- **Standard** : 300ms
- **Lente** : 500ms

## 🐛 Débogage

### Problèmes courants

**Le menu mobile ne s'ouvre pas**
- Vérifiez que `main.js` est bien chargé
- Ouvrez la console (F12) pour voir les erreurs

**Les animations ne fonctionnent pas**
- Vérifiez que JavaScript est activé
- Testez dans un autre navigateur

**Les images ne s'affichent pas**
- Vérifiez les chemins des images
- Assurez-vous que les fichiers existent dans `/images/`

**Le formulaire ne se soumet pas**
- C'est normal ! Le formulaire est en mode démo
- Connectez-le à votre backend pour l'activer

## 🎓 Ressources

### Documentation
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [Font Awesome Icons](https://fontawesome.com/icons)

### Outils recommandés
- [Figma](https://figma.com) - Design
- [TinyPNG](https://tinypng.com) - Compression d'images
- [Google PageSpeed](https://pagespeed.web.dev/) - Performance

---

**Développé avec ❤️ pour TCONNECTÉ**
