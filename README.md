# Parent Leader : page de vente

- Site en ligne (Netlify) : https://regal-sawine-a2377c.netlify.app (page + PDF téléchargeables)
- `index.html` : page, aussi visible sur https://claude.ai/artifact/CgmHsCsH2c1bqVHgHKaMCr (sans téléchargement des PDF)
- `emails-parent-leader.md` : séquence d'emails et SMS (offre 297 €)
- PDF : guide « 5 erreurs » et livret offert

## Réglages en haut du script de `index.html`
- `PAIEMENT` : liens Systeme.io (97 € et 297 € renseignés ; Phénix 30 jours et Phénix Ado Console à compléter).
- `LEAD_ENDPOINT` : adresse qui reçoit prénom + email du guide gratuit. Vide = aucun email conservé.
- `WEBINAIRE_URL`, `RDV_URL` : facultatifs.

## Avant mise en ligne définitive
Compléter les mentions légales et la politique de confidentialité (champs surlignés), le numéro d'aide affiché est le 3018 (numéro national unique depuis le 1er janvier 2024) : à revérifier de temps en temps.

## Mise à jour du site Netlify
Déposer le contenu du dossier (index.html + les 2 PDF) dans Netlify, onglet « Deploys ». Le fichier `index.html` du dépôt est un fragment : l'envelopper dans `<!doctype html><html lang="fr"><head><meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1"></head><body>…</body></html>` avant le dépôt.
