# Analyse du Risque du Portefeuille

Ce projet analyse le risque d'un portefeuille d'actions en utilisant plusieurs méthodes statistiques pour évaluer la Value at Risk (VaR) et le Conditional Value at Risk (CVaR). L'objectif est de comprendre et quantifier les risques potentiels associés à un portefeuille d'actions.

## Objectifs du Projet

1. **Évaluer les Risques du Portefeuille** : Calculer la Value at Risk (VaR) et le Conditional Value at Risk (CVaR) en utilisant différentes méthodes :
   - **VaR Historique** : Basée sur les rendements historiques.
   - **CVaR Historique** : Basée sur la VaR historique.
   - **VaR et CVaR Paramétriques** : Utilise des distributions statistiques (normale et t-distribution) pour évaluer les risques.
   - **VaR et CVaR via Simulations Monte Carlo** : Estime les risques à l'aide de simulations aléatoires.

2. **Visualiser les Résultats** : Fournir une vue graphique des simulations Monte Carlo pour mieux comprendre l'évolution du portefeuille.

## Méthodes de Calcul

### 1. Value at Risk (VaR)

La VaR mesure la perte maximale potentielle d'un portefeuille sur une période donnée, avec un certain niveau de confiance. Par exemple, une VaR à 95 % indique la perte maximale que le portefeuille pourrait subir dans 5 % des cas les plus défavorables.

### 2. Conditional Value at Risk (CVaR)

La CVaR, également connue sous le nom de Expected Shortfall, mesure la perte moyenne au-delà de la VaR. Elle fournit une évaluation plus complète des pertes potentielles en cas de scénarios extrêmes.

### 3. Méthodes Paramétriques

Les méthodes paramétriques estiment la VaR et la CVaR en supposant que les rendements suivent une distribution spécifique, soit normale, soit t-distribution. Ces méthodes utilisent des paramètres de distribution pour estimer les risques.

### 4. Simulations Monte Carlo

Les simulations Monte Carlo génèrent de multiples scénarios de rendements futurs pour estimer la VaR et la CVaR. Cette méthode permet d'obtenir une vue probabiliste des pertes potentielles en simulant de nombreux chemins possibles pour les rendements du portefeuille.

## Portefeuille d'Actions

Le portefeuille d'exemple utilisé dans ce projet comprend les actions de grandes entreprises françaises, sélectionnées pour leur représentativité et leur disponibilité de données. Voici les actions incluses :
- **AIR.PA** : Airbus
- **OR.PA** : L'Oréal
- **SAN.PA** : Société Générale
- **MC.PA** : LVMH
- **GLE.PA** : Groupe Société Générale
- **BNP.PA** : BNP Paribas
- **ACA.PA** : Crédit Agricole
- **BN.PA** : Danone

Ce choix permet de démontrer l'analyse des risques en utilisant des données financières réelles et variées.

## Résultats

Le script fournit des résultats détaillés pour :
- Rendement attendu du portefeuille
- VaR et CVaR historique à 95 %
- VaR et CVaR paramétriques (distribution normale et t-distribution) à 95 %
- VaR et CVaR via simulations Monte Carlo à 95 %

Les résultats sont affichés sous forme de valeurs numériques et graphiques, facilitant l'interprétation des risques du portefeuille.

## Conclusion

Cette analyse fournit une évaluation complète des risques associés à un portefeuille d'actions, en utilisant différentes méthodes pour obtenir une vue globale des pertes potentielles. Vous pouvez adapter le portefeuille et les paramètres pour explorer d'autres scénarios et portefeuilles.


