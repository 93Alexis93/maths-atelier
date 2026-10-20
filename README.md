# Maths Atelier

Assistant pédagogique pour professeurs de mathématiques — prototype local.

## Versions

- `index.html` : prototype v0.1 (démonstration).
- **`atelier.html` : prototype v0.2** (version de travail).

Ouvrir `atelier.html` dans un navigateur, via un serveur local ou en téléchargeant le fichier. La consultation du code sur GitHub n'exécute pas l'application. Aucun hébergement public n'est configuré.

## Fonctionnalités v0.2

- Banque de ressources par niveau, chapitre et type.
- Énoncé, corrigé et barème saisis par le professeur.
- Import de PDF ou d'images avec **conservation locale dans IndexedDB** (15 Mo par fichier).
- Recherche, filtres, sélection d'exercices.
- Impression de contrôles A ou A/B et corrigés ; avertissement si le barème diffère de 20.
- Export/import JSON des fiches **sans les pièces jointes**.

## Limites à connaître

- Les PDF/images sont stockés et consultables, **mais leur contenu n'est pas lu, converti ni inséré dans le contrôle**.
- A et B sont actuellement identiques ; pas encore de variantes distinctes.
- Les exercices sont imprimés à partir des énoncés saisis ; un document joint sans énoncé n'est pas imprimé.
- La mise en page A4 n'assure pas encore un recto-verso strict, ni le rendu mathématique avancé.
- Les données restent dans le navigateur de l'appareil : pas de compte, pas de synchronisation, risque de perte en cas d'effacement des données du navigateur. Faire des exports réguliers.
- Aucun traitement de données personnelles d'élèves.
- Prototype non testé de bout en bout sur iPhone ou en navigateur réel.

## Feuille de route

1. Import complet des documents avec sauvegarde/restauration des pièces jointes.
2. Extraction PDF/image, reconnaissance des formules et schémas, validation humaine.
3. Variantes A/B réellement différentes, équilibrage du barème et de la difficulté.
4. Génération PDF avec fractions horizontales, pagination A4 recto-verso et corrigé séparé.
5. Tests automatisés, déploiement sécurisé et éventuellement synchronisation.

## Cahier des charges pédagogique

Priorité aux fondamentaux, au raisonnement et à l'autonomie ; exercices issus des documents fournis par le professeur ; niveau de rigueur adapté. Évaluations avec espaces de réponse suffisants, note/commentaire, pointillés foncés et corrigés à la fin.
