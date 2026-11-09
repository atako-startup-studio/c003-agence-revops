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

- Audit RevOps
- Structuration des opérations commerciales
- Intégration CRM
- Migration CRM
- Reporting et tableaux de bord
- Formation RevOps
- Accompagnement continu
- Agents IA RevOps

## Utilisation

1. Déployer via GitHub Pages (activé sur le dépôt)
2. Configurer le domaine `naxtep.com` (CNAME vers `atako-startup-studio.github.io`)
3. Créer les pages de détail dans `offres/` (liées depuis l'index)

## Ce qui peut casser

- Les liens vers `offres/*.html` pointent vers des pages non encore créées (404)
- Le lien mail `contact@naxtep.com` nécessite la configuration du domaine et MX
- Les pages d'offres individuelles ne sont pas encore créées

## Hébergement

GitHub Pages. Aucune dépendance serveur.