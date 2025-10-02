# INF4127 TPE-1 – Exercice sur les Fonctions de Perte et le Calcul Symbolique

## Description du projet
Ce projet consiste à étudier plusieurs fonctions de perte couramment utilisées en apprentissage automatique en utilisant des outils de calcul symbolique (SymPy). L'objectif est de :

1. Calculer les gradients des fonctions de perte.
2. Étudier les propriétés de convexité.
3. Illustrer leur comportement sur des jeux de données pour la régression et la classification.
4. Représenter graphiquement les courbes des fonctions et déterminer l'équation des tangentes en des points spécifiques.

Les fonctions de perte étudiées sont :  
- Erreur Quadratique Moyenne (MSE)  
- Entropie Croisée Binaire  
- Entropie Croisée Catégorielle  
- Perte de Huber  

## Objectifs détaillés
Pour chaque fonction de perte :
1. **Gradient** : Fournir l'expression symbolique des dérivées par rapport aux variables.  
2. **Convexité** : Étudier la convexité de la fonction via le calcul symbolique et l'analyse mathématique.  
3. **Illustration sur données** :
   - Sélectionner un jeu de données pour la régression (2 attributs explicatifs, < 100 observations).  
   - Sélectionner un jeu de données pour la classification (2 attributs explicatifs, < 100 observations).  
   - Tracer les courbes de la fonction de perte en fonction des paramètres.  
   - Déterminer l'équation de la tangente à l'ellipse au point donné.

## Jeux de données utilisés
- **Régression** : `regression_dataset.csv` (2 attributs explicatifs, <100 observations)  
- **Classification** : `classification_dataset.csv` (2 attributs explicatifs, <100 observations)

## Technologies et outils
- **Python 3.x**  
- **SymPy** : Calcul symbolique  
- **NumPy / Pandas** : Manipulation des données  
- **Matplotlib / Seaborn** : Visualisation graphique  

# Auteurs

- Nangmo Feulfack Annick Duplesse (21S2530)
- Njiagupmun Njankouo Awa Rahma (22U2114)
- Nguefack Tangomo Chris Arthur (0000000)

Superviseur : Pr. Paulin Melatagia
# Licence
Usage académique et pédagogique uniquement.
