# 📉 Prédiction du Churn Client

Prédiction des clients susceptibles de résilier leur abonnement pour cibler les actions de rétention.

## Stack technique
- **Python** — langage principal
- **Pandas** — manipulation des données
- **Scikit-learn** — modélisation (Régression Logistique, Random Forest)
- **Matplotlib / Seaborn** — visualisation (matrice de confusion, courbe ROC)

## Étapes
1. Analyse exploratoire (EDA) — distribution, corrélations
2. Identification des variables discriminantes
3. Préparation des données (encodage, normalisation)
4. Modélisation et comparaison
5. Évaluation (Accuracy, ROC-AUC, matrice de confusion)

## Résultats

| Modèle | Accuracy | ROC-AUC |
|--------|----------|---------|
| Régression Logistique | ~0.80 | ~0.84 |
| Random Forest | ~0.85 | ~0.89 |

## Enseignements clés
- Les clients avec contrat mensuel churned 3x plus que ceux avec contrat annuel
- L'ancienneté et les charges mensuelles sont les variables les plus discriminantes
- Recommandation : cibler les clients à moins de 12 mois avec des offres de fidélisation
