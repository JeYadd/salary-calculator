# AGENTS.md

## Tools Commands

- **TypeCheck**: Pas de TypeScript dans ce projet
- **Lint**: Non configuré

## Project Overview

- **Type**: Site web statique (calculateur de salaire net)
- **Stack**: HTML + Alpine.js + Tailwind CSS
- **Lang**: Français
- **Fonctionnalité**: Calcul du salaire net à partir du salaire brut annuel selon le statut professionnel

## Conventions

- **CSS**: Tailwind CSS via CDN
- **JS**: Alpine.js via CDN (CDN: https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js)
- **Polices**: Inter (Google Fonts)
- **Couleurs**: Gradient violet (#667eea → #764ba2)
- **Structure**: Une seule page avec Alpine.js (x-data)

## Calcul Logic

Les taux de prélèvement approximatifs par statut:
- Cadre: ~22-23%
- Non-cadre: ~18-20%
- Fonctionnaire: ~15-17%
- Portagesalarial: ~25-28%
- Micro-BCE: ~25-27%