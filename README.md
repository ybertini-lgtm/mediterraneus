# Section Shopify « Collection tailles »

Section Dawn inspirée de rhythmlivin.com : au survol d'une image produit, un panneau
« Ajouter au panier » apparaît en bas de l'image avec les tailles.

- **Case blanche** = taille en stock, un clic l'ajoute directement au panier
- **Case grisée et barrée** = taille épuisée, impossible de cliquer dessus
- Onglets (ex. Femmes / Hommes) : chaque bloc correspond à une collection
- Flèches pour faire défiler les images, ou 2e image au survol
- Mobile : un bouton « + » ouvre le panneau des tailles
- Fonctionne avec le tiroir panier et la notification panier de Dawn

## Installation

1. Shopify Admin → Boutique en ligne → Thèmes → `…` → **Modifier le code**
2. Dossier **sections** → **Ajouter une section** → nommez-la `featured-collection-sizes`
3. Remplacez tout le contenu par celui de `sections/featured-collection-sizes.liquid` et enregistrez
4. Dans l'éditeur de thème : **Ajouter une section** → « Collection tailles »
5. Choisissez une collection dans chaque bloc « Onglet collection »

## À vérifier

Le réglage **Nom(s) de l'option taille** (par défaut `Taille,Size,Pointure`) doit
correspondre au nom de l'option de vos produits. Si un produit a aussi une option
couleur, les tailles affichées sont celles de sa première couleur disponible.
