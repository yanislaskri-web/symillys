---
name: symillys-brand-guidelines
description: Applique l'identité visuelle de Symilly's (agence événementielle, traiteur, chef à domicile) à tout artefact généré — slides, documents, landing pages, visuels réseaux sociaux, composants web. Se déclenche quand la demande concerne Symilly's ou mentionne "charte graphique", "identité visuelle", "brand", pour ce projet.
---

# Symilly's — Brand Guidelines

## Positionnement
Agence événementielle à Paris/Île-de-France (événementiel, traiteur, chef à domicile).
Ton de marque : élégant, raffiné, discret. Jamais tape-à-l'œil, jamais "corporate froid".
Référence directe : le site actuel (index.html) — toute production doit rester cohérente avec cette base.

## Palette de couleurs

| Rôle | Nom | Hex |
|---|---|---|
| Or principal (accents, CTA) | `--gold` | `#B8874E` |
| Or foncé (hover, contraste) | `--gold-dark` | `#9E7239` |
| Or texte (labels, liens) | `--gold-text` | `#8A6134` |
| Encre (texte principal) | `--ink` | `#2B2620` |
| Fond principal | `--bg` | `#FFFFFF` |
| Fond secondaire (sections alternées) | `--bg2` | `#FAF7F2` |
| Fond carte | `--card` | `#FFFFFF` |
| Texte atténué | `--muted` | `rgba(43,38,32,0.65)` |
| Bleu marine (secondaire, usage restreint) | `--navy` | `#1B2A41` |

Règles d'usage :
- L'or (`--gold`) est réservé aux accents et CTA — jamais en fond de grande surface (dilue le côté premium).
- Le bleu marine (`--navy`) est une couleur **secondaire tolérée**, jamais dominante : uniquement pour de grandes surfaces "fond sombre" ponctuelles (ex. panneau "Entreprises", footer) où le texte reste blanc/or dessus. L'or garde le rôle principal partout ailleurs (CTA, titres, liens).
- En dehors de `--navy` sur ces surfaces précises : jamais de violet ni de dégradés multicolores.
- Les bordures utilisent l'or à faible opacité (`rgba(184,135,78,0.15)` à `0.25)`), jamais du gris neutre.

## Typographie

- **Titres, citations, accents** : `Cormorant Garamond` (serif), style léger et élégant. `font-weight: 400`, jamais bold sur les gros titres.
- **Corps de texte, UI, boutons, labels** : `Jost` (sans-serif).
- Les CTA et labels utilisent des majuscules avec `letter-spacing` généreux (0.05em à 0.3em) pour un rendu soigné, pas criard.
- Ne jamais utiliser Inter, Arial, ou toute police système par défaut — ça casse immédiatement l'identité.

## Composition et style

- Sections avec beaucoup d'air : padding généreux (`5rem 1.5rem` sur desktop), pas de densité.
- Cartes (`.service-card`, `.testi-card`) : fond blanc, bordure or fine, coins doux (`border-radius: 16px`), ombre douce uniquement au hover.
- Boutons et CTA : forme pilule (`border-radius: 9999px`) — toute l'interface est arrondie, aucun coin carré (cartes 16px, champs de formulaire 10px, boutons en pilule).
- Animations : subtiles, `reveal` au scroll (translateY + opacity), transitions `cubic-bezier(.22,1,.36,1)` — jamais de rebond agressif ou d'effet gadget.
- Photos/visuels : toujours en écho au ton chaleureux et discret, jamais de stock photo générique "corporate".

## Ce qu'il faut éviter absolument

- Dégradés violets ou multicolores type "AI slop"
- Emojis dans les titres ou CTA
- Icônes en grille 3 colonnes sans personnalisation
- Boutons avec ombre portée forte façon Material Design
- Tout ce qui rend l'interface "générique SaaS" plutôt que "maison événementielle haut de gamme"

## Contact / infos de marque (pour cohérence contenu)

- Zone : Paris & Île-de-France
- Instagram : @symillys
- Signature de ton : phrases courtes, évocatrices, jamais de jargon marketing ("boostez", "révolutionnez")
