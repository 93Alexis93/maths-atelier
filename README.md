# Maths Atelier

Prototype **v0.1** d'un assistant pédagogique pour les professeurs de mathématiques.

## Essayer
Ouvrir `index.html` dans un navigateur moderne (ordinateur ou mobile). Aucune installation ni serveur requis. L'application n'est pas encore déployée sur une adresse publique.

## Fonctions disponibles
- Créer des fiches par niveau, chapitre et type (cours, exercice, évaluation, corrigé).
- Joindre un PDF ou une image et le consulter **pendant la session courante uniquement**.
- Rechercher et filtrer les fiches.
- Sauvegarder les métadonnées localement dans le navigateur ; exporter/importer les fiches au format JSON.
- Générer et imprimer un **modèle de contrôle 3e Thalès / calcul littéral** (50 minutes par défaut, sujets A/B, corrigés). Utiliser l'impression du navigateur pour enregistrer un PDF.

## Limites importantes
- **Aucune extraction automatique** du texte, des schémas ou des exercices des PDF/images.
- Les pièces jointes ne sont **pas sauvegardées** dans le stockage local et ne figurent pas dans l'export JSON ; il faut les resélectionner après rechargement.
- Le générateur utilise des exercices de démonstration prédéfinis et **ne réutilise pas encore** la bibliothèque.
- La mise en page imprimée est expérimentale : le format strict « 1 sujet = 1 recto-verso » et les fractions horizontales restent à implémenter.
- Aucune synchronisation entre appareils ; ne pas y déposer de données personnelles d'élèves.

## Suite du développement
1. Persistance fiable des fichiers, avec consentement et stockage adapté.
2. Extraction PDF/image avec prévisualisation et validation manuelle des exercices.
3. Banque d'exercices structurée et sélection pour les évaluations.
4. Générateur A/B avec barème, contraintes de pagination et corrigés.
5. Tests automatisés et déploiement d'une interface accessible sur mobile.

Projet privé — premières bases techniques.