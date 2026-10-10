# Le Temps des Mets — maquette indépendante

Site vitrine statique pour **Le Temps des Mets**, restaurant à Saint-Bonnet-en-Champsaur (05).

## Vérification et sources

- Activité : le guide pratique Champsaur & Valgaudemar répertorie le restaurant au cœur de Saint-Bonnet avec une cuisine à base de produits de saison ; une fiche locale d’horaires est encore active, crawlée en septembre 2026.
- Sources : [guide pratique Champsaur & Valgaudemar](https://www.champsaur-valgaudemar.com/app/uploads/champsaur-valgaudemar/2024/12/Guide-pratique-2025-BAT-compresse.pdf), [fiche horaires Le Figaro](https://horaires.lefigaro.fr/05500/Saint-Bonnet-en-Champsaur/Le-Temps-des-Mets-Saint-Bonnet-En-Champsaur-2-rue-de-chaillol%2C1472613.html).
- Logo : aucun logo officiel avec permission claire de réutilisation n’a été identifié ; typographie provisoire à remplacer par le fichier approuvé.
- Visuels : photos Unsplash sous licence, liées dans `index.html`, destinées uniquement à l’ambiance et non à représenter le restaurant.

## Liens

- GitHub : https://github.com/AMWEBDESIGNER/le-temps-des-mets
- Pages : https://le-temps-des-mets.pages.dev

## Parcours livré

L’accueil est complété par `experience.html` et `infos.html`, avec une présentation éditoriale de la cuisine de saison, les repères du village, l’itinéraire et les appels à confirmation. Faire confirmer toutes les coordonnées, horaires, menus, logo et photos par l’établissement avant exploitation commerciale. Maquette indépendante.

## Motion design et provenance du code

Animations réalisées en CSS vanilla, avec respect de `prefers-reduced-motion`, et une révélation progressive inspirée du pattern public [Scroll animation: IntersectionObserver and CSS](https://codepen.io/oscar-jite/pen/qBzwOVq). La logique reste locale, légère et adaptée à l’identité de chaque établissement ; aucune dépendance payante ni contenu généré n’est requis.

## Informations pratiques livrées

`site-enhance.js` ajoute sur l’accueil un bloc dédié à l’adresse, aux horaires, aux services, au téléphone et à l’itinéraire, ainsi qu’un footer local complet. Les informations signalées « à confirmer » doivent être validées par l’établissement avant mise en production commerciale.
