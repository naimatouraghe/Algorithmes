1. Calcul de la moyenne d'un tableau de nombres :

**Enoncé détaillé :**
Écrivez un algorithme qui prend en entrée un tableau de nombres et calcule la moyenne de ces nombres. Pour ce faire, vous devez parcourir le tableau, additionner tous les nombres et ensuite diviser la somme par le nombre total d'éléments dans le tableau. Enfin, affichez la moyenne calculée.

```
Algorithme calculerMoyenne(tableau: Tableau de nombres) : Réel
somme <- 0
pour chaque élément dans tableau faire
somme <- somme + élément
fin pour

    nombreTotal <- longueur(tableau)
    moyenne <- somme / nombreTotal

    Retourner moyenne

Fin Algorithme

```
