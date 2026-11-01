# Rive

Un petit refuge au bord du lac pour les personnes hypersensibles : respirer, nommer ce qu'on ressent, démêler les histoires que le cerveau invente, et se parler avec douceur.

Pas de compte, pas de serveur, pas de pub. Tout reste dans le téléphone (stockage local du navigateur), et l'app fonctionne hors connexion une fois ouverte.

## Mettre en ligne sur GitHub Pages

1. Crée un dépôt (par exemple `rive`) et dépose-y tout le contenu de ce dossier, à la racine : `index.html`, `manifest.webmanifest`, `sw.js`, `icons/`.
2. Dans le dépôt : **Settings → Pages → Build and deployment → Source : Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
3. Au bout d'une minute, l'app est en ligne sur `https://<ton-pseudo>.github.io/rive/`.

## L'installer sur l'iPhone

1. Ouvrir le lien dans **Safari** (pas dans Chrome ni dans l'aperçu d'une autre app).
2. Bouton **Partager** → **Sur l'écran d'accueil** → **Ajouter**.
3. Toujours l'ouvrir depuis cette icône : sur iPhone, l'app installée a son propre stockage, séparé de Safari, et il est mieux protégé contre l'effacement automatique.

## Mettre à jour

Après avoir modifié un fichier, change la version dans `sw.js` (`rive-v1` → `rive-v2`) pour que les téléphones récupèrent la nouvelle version.

## Personnaliser

- Le prénom par défaut est dans `index.html`, fonction `defaults()` (`name: "Mélina"`). Il se change aussi dans les réglages de l'app.
- Les cartes douceur (`CARDS`), les invitations à écrire (`PROMPTS`), le kit doux par défaut (`KIT_DEFAULT`) sont des listes faciles à modifier en haut du script.

## Sauvegarde

Réglages → **Sauvegarder** crée un fichier `.json` ; **Restaurer** le recharge. Utile avant de changer de téléphone.

## Sources des exercices

- Aron & Aron (1997), *Sensory-processing sensitivity*, Journal of Personality and Social Psychology.
- Lionetti et al. (2018), orchidées, tulipes et pissenlits, Translational Psychiatry.
- Balban et al. (2023), soupir cyclique, Cell Reports Medicine.
- Lieberman et al. (2007), mettre des mots sur ses émotions, Psychological Science.
- Pennebaker, écriture expressive ; synthèse Baikie & Wilhelm (2005).
- Neff & Germer (2013), pause d'autocompassion.
- LaFreniere & Newman (2020), 91 % des soucis ne se produisent pas, Behavior Therapy.
- Restructuration cognitive (Beck) et défusion (thérapie d'acceptation et d'engagement).

Rive ne remplace pas un accompagnement par un·e professionnel·le. En cas d'idées noires : **3114** (gratuit, 24 h/24). Urgence : 15 ou 112.
