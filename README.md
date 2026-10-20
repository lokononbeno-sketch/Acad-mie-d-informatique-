# Académie Numérique

Une première version de plateforme d'apprentissage responsive et installable sur Android.

## Contenu
- Informatique générale
- Graphisme et sérigraphie
- Photoshop, InDesign et Illustrator
- Word, Excel et PowerPoint
- Internet et sécurité
- Maintenance informatique
- Développement web
- Recherche, filtres par catégorie, leçons, exercices et mini-quiz

## Tester sur ordinateur
Ouvre `index.html` dans un navigateur. Certaines fonctions d'installation hors ligne nécessitent un serveur HTTPS.

## Publier sur GitHub Pages
1. Crée un dépôt GitHub nommé `academie-numerique`.
2. Envoie tous les fichiers de ce dossier à la racine du dépôt.
3. Dans le dépôt, ouvre **Settings → Pages**.
4. Choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
5. Attends la publication et ouvre l'adresse indiquée par GitHub Pages.

## Installer sur Android
Après publication sur HTTPS, ouvre le site avec Chrome sur Android. Dans le menu, choisis **Installer l'application** ou **Ajouter à l'écran d'accueil** (le libellé varie selon l'appareil).

**Important :** cela installe une application web progressive (PWA), pas un fichier APK natif. Pour produire un vrai `.apk`, il faudra ensuite emballer le site avec Capacitor/Android ou utiliser un service de conversion PWA en application Android. GitHub héberge le code mais ne transforme pas, à lui seul, le site en APK.

## Ajouter du contenu
Les cours de démonstration sont dans le tableau `courses` du fichier `app.js`. Pour ajouter une formation, copie un objet existant et modifie `id`, `title`, `category`, `icon`, `desc`, `lesson`, `body`, `steps`, `question`, `answers`, `correct` et `explain`.

## Limites de cette version
C'est une base de départ avec des leçons introductives, pas encore un programme complet certifiant. Les logiciels Adobe et Microsoft sont des produits distincts : l'application enseigne leurs concepts, elle ne les remplace pas.
