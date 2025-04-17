# Projet XVA – Processus Gaussiens pour l’estimation de la CVA

Ce projet implémente une méthode d’approximation numérique de la Credit Valuation Adjustment (CVA) à l’aide de la régression par Processus Gaussiens, inspirée de l’article de Crépey & Dixon.

Trois notebooks sont inclus :

- Notebook 1 : Approximation 1D du pricing (Call, Put, Straddle) avec GP standard.
- Notebook 2 : Processus Gaussiens multi-sortie (MGP) pour la modélisation conjointe de produits dérivés.
- Notebook 3 : Pipeline complet de calcul de la CVA avec MGP, simulation de scénarios de marché et comparaison à la méthode Monte Carlo de référence.

L’approche vise à réduire le coût de calcul tout en conservant une bonne précision et une interprétabilité du modèle.
