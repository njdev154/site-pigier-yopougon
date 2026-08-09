# Guide simple - Site Pigier Yopougon

## 1) Fichiers du projet
- `index.html` : structure et textes du site.
- `styles.css` : design (couleurs, polices, disposition Flexbox).
- `favicon.svg` : petit logo dans l'onglet du navigateur.

## 2) Comment ouvrir le site
1. Ouvre le dossier `c:\Users\DELL\PROJET PIGI`.
2. Double-clique sur `index.html`.
3. Le site s'affiche dans ton navigateur.

## 3) Ce que tu dois personnaliser en priorite
- Les numeros de telephone/WhatsApp.
- L'adresse exacte.
- Les vrais chiffres de resultats (taux de reussite, insertion, etc.).
- Les noms des meilleurs eleves (si autorisation).
- La vraie video de presentation.

## 4) Modifier les textes rapidement
Dans `index.html`, cherche les sections avec ces id:
- `formations`
- `eleves`
- `evenements`
- `resultats`
- `contact`

Tu peux changer les titres `<h2>`, sous-titres `<p>`, et cartes `<article class="card">`.

## 5) Modifier les couleurs/polices
Dans `styles.css`, section `:root`:
- `--primary` = couleur principale
- `--accent` = couleur des chiffres importants
- `--text` = couleur des textes

Polices actuelles:
- Titres: `Poppins`
- Textes: `Lato`

## 6) Comprendre Flexbox (utilise dans ce projet)
Exemple:
```css
.cards-4 {
  display: flex;
  flex-wrap: wrap;
  gap: 18px;
}
```
- `display: flex` : aligne les cartes sur une ligne.
- `flex-wrap: wrap` : passe a la ligne si l'ecran est petit.
- `gap` : espace entre cartes.

## 7) Plan de travail sur 2 semaines
### Semaine 1
- Jour 1: finaliser les textes de toutes les sections.
- Jour 2: remplacer les fausses donnees par les vraies donnees.
- Jour 3: inserer vraies photos et vraie video.
- Jour 4: corriger orthographe + valider les informations.
- Jour 5: tester sur telephone et ordinateur.

### Semaine 2
- Jour 1: ameliorer la section resultats (chiffres + source interne).
- Jour 2: enrichir section evenements (dates + mini descriptions).
- Jour 3: enrichir section meilleurs eleves (profils reels).
- Jour 4: finaliser formulaire (si possible connecter un service).
- Jour 5: repetition de presentation + capture d'ecran pour rendu.

## 8) Si tu veux aller plus loin
- Ajouter une page `formations.html`.
- Ajouter une page `admission.html`.
- Connecter le formulaire a Formspree ou Google Forms.
