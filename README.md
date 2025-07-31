# Portfolio - Najiba Nazari

## 🚀 À propos

Portfolio professionnel de Najiba Nazari, développeuse web créatif spécialisée en HTML, CSS, JavaScript, PHP et WordPress. Ce site présente mes compétences, projets et offre un formulaire de contact fonctionnel.

## ✨ Fonctionnalités

- **Design moderne et responsive** avec des animations fluides
- **Navigation fluide** avec défilement automatique
- **Section compétences** organisée par catégories
- **Galerie de projets** avec liens vers les démos
- **Formulaire de contact** fonctionnel avec Formspree
- **Optimisation SEO** avec métadonnées complètes
- **Animations d'apparition** au scroll
- **Effets de parallaxe** légers
- **Icônes Font Awesome** pour une meilleure UX

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Design moderne avec Grid et Flexbox
- **JavaScript ES6+** - Animations et interactions
- **Font Awesome** - Icônes
- **Formspree** - Gestion des formulaires

## 📁 Structure du projet

```
portfolio/
├── index.html          # Page principale
├── style.css           # Styles CSS
├── script.js           # JavaScript
├── cv.html            # Page CV
├── imageprofil.webp   # Photo de profil
├── *.png              # Images des projets
└── README.md          # Documentation
```

## 🚀 Installation

1. **Clonez le repository** (si applicable)
2. **Ouvrez le fichier `index.html`** dans votre navigateur
3. **Ou servez les fichiers** avec un serveur local :
   ```bash
   # Avec Python
   python -m http.server 8000
   
   # Avec Node.js
   npx serve .
   ```

## 📧 Configuration du formulaire de contact

Le formulaire utilise Formspree pour la gestion des emails. Pour le configurer :

1. Créez un compte sur [Formspree](https://formspree.io)
2. Créez un nouveau formulaire
3. Remplacez l'URL dans le formulaire HTML :
   ```html
   <form action="https://formspree.io/f/VOTRE_ID" method="POST">
   ```

## 🎨 Personnalisation

### Couleurs
Les couleurs sont définies dans les variables CSS :
```css
:root {
    --bleu-nuit: #0a1929;
    --bleu-fonce: #102a43;
    --violet: #6b46c1;
    --violet-clair: #9f7aea;
    --blanc: #f8fafc;
}
```

### Ajout de projets
Pour ajouter un nouveau projet, dupliquez la structure :
```html
<div class="project-card">
    <div class="project-img">
        <img src="votre-image.png" alt="Description">
    </div>
    <div class="project-content">
        <h3>Titre du projet</h3>
        <p>Description du projet</p>
        <div class="project-links">
            <a href="lien-demo">Démo</a>
            <a href="lien-code">Code</a>
        </div>
    </div>
</div>
```

## 📱 Responsive Design

Le site est entièrement responsive avec :
- **Mobile First** approach
- **Breakpoints** : 768px, 1024px, 1600px
- **Unités relatives** (clamp, vw, vh)
- **Flexbox et Grid** pour la mise en page

## 🔧 Optimisations

- **Performance** : Images optimisées, CSS minifié
- **SEO** : Métadonnées complètes, structure sémantique
- **Accessibilité** : Contrastes appropriés, navigation clavier
- **Sécurité** : Liens externes avec `rel="noopener noreferrer"`

## 📞 Contact

- **GitHub** : [najiba93](https://github.com/najiba93)
- **LinkedIn** : [Najiba Nazari](https://linkedin.com/in/najiba-nazari-a52b43366)

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier selon vos besoins.

---

**Développé avec ❤️ par Najiba Nazari** 