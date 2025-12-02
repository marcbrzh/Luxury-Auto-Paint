# Atelier Renaissance — Site vitrine d'un atelier de peinture automobile haut de gamme

Ce dépôt contient le site vitrine statique d’**Atelier Renaissance**, un garage spécialisé dans la peinture, la restauration et les retouches de carrosserie pour véhicules de luxe, sport et collection à Lorient. Le site est prêt à être ouvert dans un navigateur ou déployé sur tout hébergement statique et met en avant l’expertise, les réalisations et les services de l’atelier.

## Aperçu du contenu
- **Accueil (`index.html`)** : présentation de l’atelier, domaines d’intervention, sélection de réalisations, FAQ et bloc de contact avec intégration WhatsApp.
- **Services (`nos-services.html`)** : détails complets des prestations (réparation après choc, reprises intégrales, detailing, restauration de collection) et FAQ dédiée.
- **Réalisations (`realisations.html`)** : galerie avant/après mettant en valeur des projets de restauration et de peinture haut de gamme.
- **Atelier (`atelier.html`)** : présentation des équipements (cabine, zone de masquage, diagnostic colorimétrique) et de la méthode de travail.
- **Ressources communes** :
  - `style.css` pour la charte graphique premium (typographies serif/sans, palette profonde, grilles responsives).
  - `js/script.js` pour la navigation mobile (hamburger, verrouillage du scroll) et les interactions de base.
  - `images/` pour les visuels (héros, réalisations, icônes, favicon).

## Fonctionnalités clés
- Navigation responsive avec menu hamburger et CTA WhatsApp mis en avant.
- Sections « Services », « Réalisations » et « Atelier » orientées conversion : textes courts, bénéfices clairs, appels à l’action.
- Galerie avant/après et grilles de services optimisées pour les véhicules d’exception.
- Formulaire de contact prêt à connecter à votre solution (Formspree, mailto, API) et lien Maps personnalisable.
- Performance statique : aucun build requis, compatible GitHub Pages, Netlify, Vercel ou tout hébergement S3.

## Arborescence
```
/
├─ index.html           # Page d'accueil
├─ nos-services.html    # Détails des prestations
├─ realisations.html    # Galerie avant/après
├─ atelier.html         # Présentation des équipements
├─ style.css            # Styles globaux et composants
├─ js/
│  └─ script.js         # Navigation mobile et interactions
└─ images/              # Visuels (héros, services, réalisations, favicon)
```

## Personnalisation rapide
1. **Coordonnées & CTA**
   - Remplacez `[NUMERO]` dans les liens WhatsApp des pages HTML par le numéro du garage (format international, sans espaces).
   - Mettez à jour l’adresse et le lien Google Maps dans la section contact.
2. **Textes et métadonnées**
   - Ajustez les titres, descriptions et balises `<meta name="description">` pour refléter votre positionnement (ville, spécialités, marques suivies).
   - Adaptez les FAQ et argumentaires aux spécificités du garage (délais, garanties, marques de peinture utilisées, gestion assurance).
3. **Visuels**
   - Remplacez les images de `images/` par vos photos (format WebP/AVIF ou JPEG haute qualité). Gardez des dimensions cohérentes pour préserver les ratios.
4. **Identité visuelle**
   - Modifiez la palette et les typographies dans `style.css` si nécessaire. Les classes sont documentées par sections (hero, services, réalisations, atelier, FAQ, footer).

## Déploiement
Aucun serveur n’est requis : servez simplement les fichiers statiques.
- **Prévisualisation locale** : ouvrez `index.html` dans votre navigateur ou utilisez une extension type Live Server.
- **GitHub Pages** : poussez la branche principale puis activez Pages sur le dossier racine.
- **Netlify / Vercel / S3** : déployez le dossier tel quel sans étape de build.

## Bonnes pratiques SEO & performance
- Renseignez les balises `alt` des images lors de vos remplacements et gardez des noms de fichiers explicites.
- Compressez les images pour limiter le poids des pages (objectif : < 200 Ko par visuel clé).
- Vérifiez la cohérence des balises titres (H1/H2/H3) et des metas sur chaque page pour renforcer le référencement local.
- Testez l’affichage mobile (≤ 768 px) et desktop ; ajustez si vous changez la longueur des titres ou CTA.

## Support
Pour toute question ou extension (prise de rendez-vous en ligne, blog d’actualités, suivi de projet client), dupliquez ce dépôt et adaptez les sections concernées.
