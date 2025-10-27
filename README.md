# Jeunactio - Infrastructure Numérique

Site web officiel de l'association Jeunactio - Pour une jeunesse active et engagée.

**URL:** www.jeunactio.fr

## 🎯 À propos

Jeunactio est une association dédiée à dynamiser la jeunesse par l'action et l'engagement. Ce dépôt contient l'infrastructure numérique complète de l'association.

## 📋 Structure du Projet

```
Muhammed-DURAN/
├── index.html          # Page d'accueil
├── about.html          # Page À propos
├── contact.html        # Page Contact
├── css/
│   └── style.css       # Feuilles de style
├── js/
│   └── script.js       # Scripts JavaScript
└── README.md           # Documentation
```

## 🚀 Fonctionnalités

- ✅ Design moderne et responsive
- ✅ Navigation intuitive avec menu mobile
- ✅ Page d'accueil avec présentation de la mission
- ✅ Page À propos détaillée avec objectifs et activités
- ✅ Formulaire de contact interactif
- ✅ Section FAQ
- ✅ Animations au défilement
- ✅ Compatible tous navigateurs modernes
- ✅ Optimisé pour mobile, tablette et desktop

## 💻 Technologies Utilisées

- HTML5
- CSS3 (avec variables CSS et Flexbox/Grid)
- JavaScript (Vanilla JS)
- Design Responsive

## 🎨 Palette de Couleurs

- Primaire: #2563eb (Bleu)
- Secondaire: #7c3aed (Violet)
- Accent: #10b981 (Vert)
- Texte sombre: #1f2937
- Texte clair: #6b7280

## 📱 Pages

### Accueil (`index.html`)
- Section héro avec appel à l'action
- Présentation de la mission (Engagement, Solidarité, Innovation)
- Nos valeurs
- Section d'appel à l'action

### À propos (`about.html`)
- Histoire de l'association
- Vision et objectifs
- Liste des activités
- Appel à rejoindre l'association

### Contact (`contact.html`)
- Informations de contact
- Formulaire de contact interactif
- Section FAQ
- Horaires de disponibilité

## 🌐 Déploiement

### Option 1: Hébergement Statique
Le site peut être déployé sur n'importe quelle plateforme d'hébergement statique:
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

### Option 2: Serveur Web Traditionnel
1. Uploadez tous les fichiers sur votre serveur web
2. Assurez-vous que `index.html` est le fichier par défaut
3. Configurez votre domaine pour pointer vers le répertoire

### GitHub Pages
1. Allez dans Settings → Pages
2. Sélectionnez la branche à déployer
3. Le site sera accessible à l'URL générée

## 🔧 Développement Local

Pour tester le site localement:

1. Clonez le dépôt:
```bash
git clone https://github.com/contactjeunactio/Muhammed-DURAN.git
cd Muhammed-DURAN
```

2. Ouvrez simplement `index.html` dans votre navigateur, ou utilisez un serveur local:

Avec Python:
```bash
python -m http.server 8000
```

Avec Node.js (http-server):
```bash
npx http-server
```

3. Accédez à `http://localhost:8000` dans votre navigateur

## 📝 Personnalisation

### Modifier les couleurs
Éditez les variables CSS dans `css/style.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    /* ... autres variables ... */
}
```

### Ajouter du contenu
- Modifiez les fichiers HTML pour changer le texte
- Ajoutez de nouvelles sections en suivant la structure existante
- Les styles sont modulaires et réutilisables

### Ajouter des pages
1. Créez un nouveau fichier HTML
2. Copiez la structure de navigation depuis une page existante
3. Ajoutez le lien dans le menu de navigation

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer:

1. Forkez le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/NouvelleFonctionnalite`)
3. Committez vos changements (`git commit -m 'Ajout de NouvelleFonctionnalite'`)
4. Poussez vers la branche (`git push origin feature/NouvelleFonctionnalite`)
5. Ouvrez une Pull Request

## 📧 Contact

- **Email:** contact@jeunactio.fr
- **Site Web:** www.jeunactio.fr

## 📄 Licence

Ce projet est la propriété de l'Association Jeunactio.

## 🙏 Remerciements

Merci à tous les membres et bénévoles de Jeunactio qui rendent cette association possible !

---

**© 2025 Jeunactio. Tous droits réservés.**
