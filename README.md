# scanalis
projet scanalis
# SCANALIS - Landing Page

## 📋 Description

Landing page élégante et professionnelle pour Scanalis, solution de sécurité spécialisée dans la protection des API et automatisations IA pour agences SaaS.

**Slogan :** "Sécurisez les automatisations IA de vos clients"

**Positionnement :** Protection experte pour agences qui intègrent des API et des systèmes IA pour leurs clients.

---

## 🎯 Cible

- Agences IA et SaaS
- Intégrateurs API
- Développeurs d'automatisations
- CTOs d'agences digitales

---

## ✨ Caractéristiques du design

### Style
- **Élégant et professionnel** : ton sobre et sérieux adapté à la cybersécurité
- **Dark mode moderne** : couleurs sombres avec accent indigo
- **Typographie claire** : -apple-system pour une lecture parfaite
- **Animations subtiles** : smooth scrolling et hover effects discrets
- **100% responsive** : adapté mobile, tablette, desktop

### Structure
1. **Header fixe** : navigation simple et épurée
2. **Hero** : message clair sur la sécurité des automatisations IA
3. **Protection complète** : 6 domaines d'expertise en cartes
4. **Menaces** : liste des risques neutralisés (prompt injection, API abuse, etc.)
5. **Approche** : processus en 3 étapes
6. **Contact** : coordonnées simples (email + LinkedIn)

---

## 🚀 Installation

### Méthode 1 : Fichier HTML simple

```bash
# Téléchargez le fichier index.html
# Ouvrez-le directement dans un navigateur
```

### Méthode 2 : Hébergement gratuit

**Netlify (recommandé)**
```bash
# 1. Créez un compte sur netlify.com
# 2. Glissez-déposez le fichier HTML
# 3. Votre site est en ligne !
```

**Vercel**
```bash
npm i -g vercel
vercel --prod
```

**GitHub Pages**
```bash
# 1. Créez un repo GitHub
# 2. Uploadez index.html
# 3. Activez Pages dans Settings
```

---

## 🎨 Personnalisation

### Couleurs

Modifiez les variables CSS dans le fichier :

```css
:root {
    --dark: #0A0E27;           /* Fond principal */
    --darker: #050816;         /* Sections alternées */
    --accent: #4F46E5;         /* Couleur principale */
    --accent-light: #6366F1;   /* Hover/liens */
    --text: #F1F5F9;           /* Texte blanc */
    --text-muted: #94A3B8;     /* Texte secondaire */
    --border: #1E293B;         /* Bordures */
}
```

### Contenu

**Email de contact** : ligne 348
```html
<a href="mailto:votre-email@scanalis.fr">votre-email@scanalis.fr</a>
```

**LinkedIn** : ligne 352
```html
<a href="https://linkedin.com/in/votre-profil">LinkedIn</a>
```

**Menaces** : section `.threats` ligne 220-240  
Ajoutez/modifiez les risques listés

**Services** : section `.security-grid` ligne 180-210  
Personnalisez les 6 cartes de services

---

## 📊 SEO

### Meta tags à ajouter

Ajoutez dans le `<head>` pour améliorer le référencement :

```html
<!-- Open Graph -->
<meta property="og:title" content="Scanalis - Sécurité API & IA">
<meta property="og:description" content="Protection des automatisations IA pour agences SaaS">
<meta property="og:image" content="https://votredomaine.com/og-image.jpg">
<meta property="og:url" content="https://scanalis.fr">

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Scanalis - Sécurité API & IA">
<meta name="twitter:description" content="Protection experte des intégrations IA">

<!-- Favicon -->
<link rel="icon" type="image/svg+xml" href="/favicon.svg">
```

### Sitemap et robots.txt

Créez `robots.txt` :
```
User-agent: *
Allow: /
Sitemap: https://scanalis.fr/sitemap.xml
```

---

## 📈 Analytics

### Google Analytics

Ajoutez avant `</body>` :

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

### Plausible Analytics (alternatif, RGPD friendly)

```html
<script defer data-domain="scanalis.fr" src="https://plausible.io/js/script.js"></script>
```

---

## 🔧 Optimisations techniques

### Performance
- ✅ Pas de dépendances externes
- ✅ CSS et JS inline (< 10KB)
- ✅ Pas d'images lourdes
- ✅ Lazy loading natif possible

### Accessibilité
- ✅ Contraste WCAG AAA
- ✅ Navigation clavier
- ✅ Balises sémantiques HTML5
- ✅ Alt texts sur icônes

### Compatibilité
- Chrome, Firefox, Safari, Edge (dernières versions)
- iOS Safari 12+
- Android Chrome 80+

---

## 💼 Stratégie marketing

### Pour attirer les agences

**LinkedIn** (prioritaire)
- Posts sur les vulnérabilités IA communes
- Cas d'usage concrets
- Partage d'articles techniques

**Content Marketing**
- "10 vulnérabilités dans les workflows IA"
- "Comment sécuriser vos intégrations GPT"
- "Checklist sécurité pour automatisations"

**Partenariats**
- Make.com, Zapier : intégrateurs no-code
- n8n : workflows open-source
- LangChain : framework IA

**Networking**
- Meetups DevOps locaux
- Conférences cybersécurité
- Communautés IA (Discord, Slack)

### Proposition de valeur claire

> "Vos clients vous font confiance pour leurs automatisations IA. Nous faisons en sorte que cette confiance soit méritée."

---

## 📞 Contact

Pour questions sur cette landing page :
- **Email** : contact@scanalis.fr
- **LinkedIn** : Mathilde de Roumilly

---

## 📝 Structure des fichiers

```
scanalis-landing/
├── index.html          # Page unique complète
└── README.md          # Cette documentation
```

Tout est dans un seul fichier HTML pour faciliter le déploiement.

---

## 🎯 Prochaines étapes

### Court terme
- [ ] Configurer le domaine scanalis.fr
- [ ] Ajouter analytics
- [ ] Créer page LinkedIn entreprise
- [ ] Premier post LinkedIn avec lien

### Moyen terme
- [ ] Ajouter section témoignages
- [ ] Créer 3-5 articles de blog SEO
- [ ] Développer des case studies
- [ ] Webinar "Sécuriser vos automatisations IA"

### Long terme
- [ ] Dashboard client (espace sécurisé)
- [ ] Documentation technique publique
- [ ] Outils gratuits (checklist, scanner)
- [ ] Programme de partenariat agences

---

## 📄 Licence

© 2026 Scanalis. Tous droits réservés.

Design minimaliste, élégant et professionnel adapté au secteur de la cybersécurité.
