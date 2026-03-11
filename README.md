# stats

Petit repo de notebooks **Python** pour réviser / illustrer des notions de **statistiques & probabilités** (distributions + simulations).

## Contenu
Ce dépôt contient des notebooks Jupyter centrés sur des distributions usuelles :

- `discrete_distrib.ipynb` : loi **binomiale** (tirages, PMF/CDF/SF)
- `poisson_distrib.ipynb` : loi de **Poisson** (PMF/CDF/SF + simulations)
- `unif_distrib.ipynb` : loi **uniforme** continue (CDF, intervalles, quantiles `ppf`, tirages)
- `norm_distrib.ipynb` : loi **normale** (probabilités, quantiles, visualisation PDF)
- `tcl_distrib.ipynb` : **théorème central limite** (simulation de moyennes d’échantillons + comparaison à une normale)

## Dépendances
Les dépendances sont listées dans `requirements.txt` :
- numpy, pandas
- matplotlib, seaborn
- scipy

## Utilisation
1. Installer les dépendances :
   ```bash
   pip install -r requirements.txt
