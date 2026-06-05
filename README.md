# Site portfolio photo — Quentin Tran

Site implémenté le 2026-06-05 à partir du design Claude (Direction A · Épuré).
Site mono-fichier en HTML/CSS/JS vanilla, sans framework ni dépendance à installer.

## Contenu du dossier

```
site/
├── index.html        # Tout le site (HTML + CSS + JS dans un seul fichier)
├── images/           # 20 images placeholder (.svg) à remplacer par tes photos
│   ├── hero.svg          # image d'accroche plein écran
│   ├── portrait.svg      # ton portrait (section À propos)
│   └── qt-*.svg          # les 18 photos de la galerie
└── README.md         # ce fichier
```

## Ouvrir le site

Double-clique sur `index.html` : il s'ouvre dans ton navigateur. C'est tout.

## Ce que fait le site

- **Hero** plein écran (nom + « Street & travel photography »), léger zoom à l'arrivée.
- **Galerie masonry** filtrable : Tout · Street · Indonésie · Turquie · Japon · Chine.
- **Lightbox** épurée : fond noir, image seule, navigation flèches ←/→ (souris et clavier), Esc pour fermer, compteur.
- **À propos** : portrait + texte (à personnaliser).
- **Contact** : email, formulaire de démo, liens Instagram `@qtn.ys` et TikTok `@qtcmoi`.

Style : Cormorant Garamond (titres) + Hanken Grotesk (texte), fond blanc cassé, accent terracotta `#9a3b2e`.

## Personnaliser (tout est commenté en français dans index.html)

Ouvre `index.html` et cherche (Cmd+F) ces étiquettes :

| À modifier | Étiquette à chercher |
|------------|----------------------|
| Tes photos de galerie | `LISTE DE VOS PHOTOS` |
| L'image du hero | `PHOTO DU HERO` |
| Ton portrait | `VOTRE PORTRAIT` |
| Le texte de présentation | `SECTION À PROPOS` |
| Ton email et tes réseaux | `SECTION CONTACT` |

Pour remplacer une image : dépose ton fichier (ex : `ma-photo.jpg`) dans `images/`,
puis remplace l'adresse `images/xxx.svg` correspondante par `images/ma-photo.jpg`.

### Textes placeholder à revoir en priorité
- « Basé à **Paris, FR** » dans la section À propos (le design a mis Paris par défaut).
- L'email **bonjour@quentintran.com** est fictif, mets le tien.
- Les lieux/titres des photos sont des exemples, adapte-les à tes vraies images.

## Mettre en ligne

Le site est juste un dossier de fichiers statiques. Options gratuites :
- **Netlify Drop** : glisse le dossier `site/` sur app.netlify.com/drop, en ligne en 30 secondes.
- **GitHub Pages** : pousse le dossier sur un dépôt et active Pages.

IAmi peut t'accompagner pour la mise en ligne quand tu seras prêt.

## Note technique
Les placeholders sont en SVG (légers, nets, autonomes, fonctionnent hors-ligne).
Tu peux les remplacer par des JPG/PNG sans souci, le code accepte n'importe quel format d'image.
