# 🚀 Guide d'utilisation - Site TCONNECTÉ

## ✅ Site Web Premium Terminé !

Votre site web moderne pour services de domotique, alarmes et vidéosurveillance est prêt à l'emploi.

---

## 📦 Contenu du projet

### Pages créées (5)
1. ✅ **index.html** - Page d'accueil complète
2. ✅ **domotique.html** - Page Domotique
3. ✅ **alarmes.html** - Page Alarmes  
4. ✅ **videosurveillance.html** - Page Vidéosurveillance
5. ✅ **contact.html** - Page Contact avec formulaire

### Fichiers techniques
- ✅ **css/style.css** - Tous les styles (design system complet)
- ✅ **js/main.js** - Toutes les interactions JavaScript
- ✅ **images/** - Dossier pour vos images
- ✅ **README.md** - Documentation complète

---

## 🎯 Fonctionnalités implémentées

### Design & UX
- ✅ Design moderne et premium
- ✅ Palette de couleurs professionnelle (bleu/cyan)
- ✅ Typographie Poppins (Google Fonts)
- ✅ Icônes Font Awesome 6.5.1
- ✅ Animations subtiles au scroll
- ✅ Ombres et dégradés élégants

### Navigation
- ✅ Menu sticky avec effet au scroll
- ✅ Menu mobile hamburger responsive
- ✅ Smooth scroll vers les sections
- ✅ Indicateur de page active
- ✅ Bouton "Back to top"

### Sections de la page d'accueil
- ✅ Hero avec statistiques animées
- ✅ Section bénéfices (6 cards)
- ✅ Section services (3 services détaillés)
- ✅ Section "Comment ça marche" (4 étapes)
- ✅ Section confiance/partenaire Ajax
- ✅ Section CTA (Call-to-Action)
- ✅ Footer complet avec liens

### Pages secondaires
- ✅ Hero spécifique à chaque page
- ✅ Sections solutions détaillées
- ✅ Grilles de fonctionnalités
- ✅ Scénarios d'utilisation
- ✅ Témoignages clients (page Alarmes)

### Page Contact
- ✅ Formulaire de contact complet
- ✅ Validation en temps réel
- ✅ Cartes d'information de contact
- ✅ Carte Google Maps intégrée
- ✅ Liste des zones d'intervention
- ✅ FAQ avec accordion interactif

### JavaScript
- ✅ Menu mobile fonctionnel
- ✅ Animations au scroll (AOS)
- ✅ Validation de formulaire
- ✅ Système de notifications
- ✅ FAQ accordion
- ✅ Compteurs animés
- ✅ Lazy loading images
- ✅ Cookie consent banner
- ✅ Barre de progression du scroll
- ✅ Back to top button

### Responsive
- ✅ Mobile-first design
- ✅ Breakpoints : 768px, 1024px
- ✅ Grilles adaptatives
- ✅ Images responsive
- ✅ Menu mobile optimisé

---

## 🚀 Comment utiliser le site

### Option 1 : Ouvrir directement
1. Double-cliquez sur `index.html`
2. Le site s'ouvre dans votre navigateur par défaut
3. Naviguez entre les pages

### Option 2 : Avec un serveur local (recommandé)

**Avec Python (si installé) :**
```bash
cd "/Users/admin/DEV AGENCY/DEV/tconnect-main"
python3 -m http.server 8000
```
Puis ouvrir : http://localhost:8000

**Avec PHP (si installé) :**
```bash
cd "/Users/admin/DEV AGENCY/DEV/tconnect-main"
php -S localhost:8000
```

**Avec Node.js :**
```bash
npx http-server -p 8000
```

---

## 🎨 Personnalisation rapide

### 1. Changer les couleurs

Ouvrez `css/style.css` et modifiez les variables au début du fichier :

```css
:root {
    --primary-color: #2563eb;    /* Votre couleur principale */
    --accent-color: #06b6d4;     /* Votre couleur d'accent */
    /* ... */
}
```

### 2. Remplacer les images

1. Placez vos images dans le dossier `images/`
2. Nommez-les comme suit ou modifiez les chemins dans les HTML :
   - `domotique-hero.jpg`
   - `domotique-intro.jpg`
   - `alarme-hero.jpg`
   - `alarme-intro.jpg`
   - `camera-hero.jpg`
   - `camera-intro.jpg`
   - `ajax-partner.jpg`

### 3. Modifier les textes

Ouvrez les fichiers HTML et modifiez directement le contenu entre les balises.

### 4. Changer les coordonnées

Recherchez et remplacez dans tous les fichiers :
- Téléphone : `07 81 43 78 59`
- Email : `contact@tconnecte.fr`
- Adresse : `13 Rue des Aubépines, 35410 Domloup`

---

## 📱 Test du responsive

### Tester sur différents appareils

**Dans Chrome/Firefox :**
1. Ouvrir le site
2. Appuyer sur F12 (ouvrir les DevTools)
3. Cliquer sur l'icône mobile (ou Ctrl+Shift+M)
4. Sélectionner différentes tailles d'écran

**Tailles à tester :**
- iPhone SE (375px)
- iPhone 12 Pro (390px)
- iPad (768px)
- Desktop (1280px+)

---

## 🔧 Connecter le formulaire

Le formulaire est actuellement en mode démo. Pour le rendre fonctionnel :

### Option 1 : PHP (simple)
Créez un fichier `contact.php` :

```php
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $nom = htmlspecialchars($_POST['nom']);
    $email = htmlspecialchars($_POST['email']);
    $message = htmlspecialchars($_POST['message']);
    
    $to = "contact@tconnecte.fr";
    $subject = "Nouveau message depuis le site";
    $body = "Nom: $nom\nEmail: $email\n\nMessage:\n$message";
    
    mail($to, $subject, $body);
    
    header("Location: merci.html");
}
?>
```

Puis modifiez l'attribut `action` du formulaire dans `contact.html` :
```html
<form action="contact.php" method="POST">
```

### Option 2 : Services tiers
- **Formspree** : https://formspree.io
- **Netlify Forms** : Si hébergé sur Netlify
- **EmailJS** : https://www.emailjs.com

---

## 🌐 Mise en ligne

### Option 1 : Hébergement gratuit

**Netlify (recommandé) :**
1. Créer un compte sur netlify.com
2. Glisser-déposer le dossier du site
3. Site en ligne en quelques secondes !

**GitHub Pages :**
1. Créer un repo GitHub
2. Uploader les fichiers
3. Activer GitHub Pages dans les settings

**Vercel :**
1. Compte sur vercel.com
2. Importer le projet
3. Déploiement automatique

### Option 2 : Hébergement payant
- OVH
- O2Switch
- Hostinger
- Ionos

---

## ✅ Checklist avant mise en ligne

- [ ] Remplacer toutes les images placeholder
- [ ] Vérifier tous les textes et coordonnées
- [ ] Tester le formulaire de contact
- [ ] Vérifier les liens (réseaux sociaux, etc.)
- [ ] Tester sur mobile
- [ ] Optimiser les images (compression)
- [ ] Ajouter Google Analytics (optionnel)
- [ ] Configurer le domaine personnalisé
- [ ] Tester la vitesse (PageSpeed Insights)
- [ ] Vérifier le SEO

---

## 🎓 Ressources utiles

### Optimisation d'images
- **TinyPNG** : https://tinypng.com (compression)
- **Squoosh** : https://squoosh.app (compression avancée)
- **Remove.bg** : https://remove.bg (retirer les fonds)

### Icônes & Images
- **Font Awesome** : https://fontawesome.com/icons
- **Unsplash** : https://unsplash.com (photos gratuites)
- **Pexels** : https://pexels.com (photos gratuites)

### Outils de test
- **PageSpeed Insights** : https://pagespeed.web.dev
- **GTmetrix** : https://gtmetrix.com
- **Mobile-Friendly Test** : https://search.google.com/test/mobile-friendly

---

## 📞 Support

Si vous avez besoin d'aide pour personnaliser ou mettre en ligne le site, n'hésitez pas à demander !

### Modifications courantes
- ✅ Changer les couleurs
- ✅ Ajouter/supprimer des sections
- ✅ Modifier les textes
- ✅ Intégrer des outils tiers (chat, analytics)
- ✅ Optimiser les performances
- ✅ Ajouter des fonctionnalités

---

## 🎉 Félicitations !

Votre site web premium est prêt. Il ne vous reste plus qu'à :
1. Personnaliser le contenu
2. Ajouter vos vraies images
3. Le mettre en ligne
4. Commencer à recevoir des demandes de devis !

**Bon succès avec TCONNECTÉ ! 🚀**
