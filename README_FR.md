
# Boussole Safari — Guide iPhone pas à pas

## 1) Réglages (iOS)
- **Réglages → Boussole → Utiliser le nord vrai** : activez.
- **Réglages → Confidentialité et sécurité → Services de localisation** : activez.
  - Descendez jusqu’à **Safari Sites Web** et mettez **Pendant l’utilisation**.
- **Réglages → Safari → Accès aux mouvements et à l’orientation** : activez (si présent).

## 2) Optionnel : Remplacer l’icône par celle de Safari
- Placez un PNG transparent 1024×1024 nommé **safari.png** dans le dossier `icons/`.
- (Usage perso uniquement — ne pas redistribuer le logo Apple.)

## 3) Mettre la web app en ligne (obligatoire pour « Sur l’écran d’accueil »)
Choisissez l’une des options :
- **GitHub Pages** (gratuit) : uploadez tout le dossier puis activez Pages.
- **Netlify / Vercel / Cloudflare Pages** : déposez le dossier tel quel.
- **Hébergeur perso** : servez `index.html` en HTTPS.

*(iOS ne permet pas d’ajouter un fichier local à l’écran d’accueil.)*

## 4) Ajouter sur l’écran d’accueil
- Ouvrez votre URL dans **Safari**.
- Appuyez sur **Partager → Sur l’écran d’accueil**.
- Renommez si besoin, validez. L’icône provient de `icons/apple-touch-icon.png`.

## 5) Premier lancement
- Touchez **Activer la boussole** pour accorder la permission « mouvements et orientation ».
- Si un message apparaît, touchez **Autoriser**.

## Dépannage
- Aucune rotation ? Vérifiez « Accès aux mouvements et à l’orientation » (Réglages → Safari).
- Cap mal précis ? Faites un 8 avec le téléphone (recalibration) et vérifiez « nord vrai ».
- Carte qui ne tourne pas dans une page web ? Le site doit utiliser l’orientation — la web app, elle, tournera bien.

Bon usage !
