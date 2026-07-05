# Templates de sites vitrine

5 templates HTML autonomes (CSS + JS inline, sans framework, sans build), prêts à personnaliser pour différents secteurs.

| Fichier | Vibe / cas d'usage |
|---|---|
| `template-luxe-dore.html` | **Luxe Doré** — sombre, premium, doré. Artisanat haut de gamme, joaillerie, conciergerie, gastronomie. |
| `template-minimal-epure.html` | **Minimal Épuré** — clair, aéré, éditorial. Studio de conseil, architecture, indépendant. |
| `template-corporate-bleu.html` | **Corporate Bleu** — professionnel B2B, cartes arrondies, mock dashboard. Conseil, finance, tech. |
| `template-creatif-audacieux.html` | **Créatif Audacieux** — bold, coloré, dégradés et blobs flous. Agence créative, branding, startup. |
| `template-nature-bienetre.html` | **Nature Bien-être** — chaleureux, organique, arrondis généreux. Spa, yoga, bien-être, marque éco-responsable. |

Chaque fichier est un site d'une page complet : nav avec menu burger mobile, hero, bandeau de chiffres clés, section services, méthode en 3 étapes (`#methode`), galerie de réalisations (`#galerie`), bandeau d'engagement, témoignages, contact avec formulaire mailto (`#contact`), footer et bouton flottant de contact rapide.

## Comment personnaliser

**a) Recolorer** — chaque fichier a un bloc `:root { ... }` en haut du `<style>` avec les variables CSS de palette (ex. `--gold`, `--navy`, `--sage`...). Changez ces valeurs pour retheme tout le site sans toucher au reste du CSS.

**b) Remplir le contenu** — cherchez/remplacez tous les textes entre crochets : `[Nom de votre marque]`, `[Votre ville]`, `[votre-email@domaine.com]`, `[+33 X XX XX XX XX]`, `[@votre-compte]`, `[Service 1/2/3]`, `[Projet 1 — nom du client]`, etc. Un commentaire HTML juste après `<body>` dans chaque fichier rappelle quoi éditer.

**c) Ancres stables** — les IDs `#methode`, `#galerie` et `#contact` sont identiques sur les 5 templates. Vous pouvez réordonner ou dupliquer des sections entre templates : les liens de nav et de footer continueront de fonctionner tant que ces IDs sont conservés.

**d) Formulaire de contact** — le formulaire ne s'envoie pas via un serveur : le clic sur "Envoyer" (fonction `submitForm()` dans le `<script>` de la section contact) construit un lien `mailto:` avec le contenu du formulaire en corps de message et ouvre le client mail de l'utilisateur. Pour router les demandes ailleurs, remplacez `[votre-email@domaine.com]` dans `window.location.href = 'mailto:...'` par votre adresse réelle (ou remplacez ce bloc par un appel à un service de formulaire tiers si besoin).
