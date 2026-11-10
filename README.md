# c003-agence-revops — Naxtep (naxtep.com)

Agence RevOps et optimisation des opérations commerciales (C003).
Site statique HTML/CSS vanilla, responsive, sans framework ni base de données.
Déployé via GitHub Pages.

## Structure

```
c003-agence-revops/
  index.html                 — Page d'accueil Naxtep
  mentions-legales.html      — Mentions légales Aiybiz
  confidentialite.html       — Politique de confidentialité RGPD
  cgu.html                   — Conditions générales d'utilisation
  css/style.css              — Feuille de styles responsive (thème violet)
  offres/                    — Pages de détail des offres (à créer)
  README.md
```

## Services

- Audit RevOps — Diagnostic complet de la stack et des processus commerciaux
- Pilotage du revenu — KPIs, tableaux de bord, prévisions et rituels
- Stack HubSpot — Déploiement et configuration CRM HubSpot
- Stack HubSpot + Salesforce — Architecture bi-CRM synchronisée
- Accélération — Scoring avancé, automatisations et agents IA RevOps

## Utilisation

1. Déployer via GitHub Pages (activé sur le dépôt)
2. Configurer le domaine `naxtep.com` (CNAME vers `atako-startup-studio.github.io`)
3. Les pages d'offres sont dans `offres/`, accessibles depuis le landing et entre elles

## Ce qui peut casser

- Le lien mail `contact@naxtep.com` nécessite la configuration du domaine et MX
- `js/stripe.js` est référencé mais pas encore créé

## Hébergement

GitHub Pages. Aucune dépendance serveur.