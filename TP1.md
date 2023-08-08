# Calcul de la moyenne d'un tableau de nombres :
**<ins>Enoncé détaillé :</ins>**

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


// Exemple d'utilisation
tableau <- [10, 20, 30, 40, 50]
moyenneCalculee <- calculerMoyenne(tableau)
Afficher "La moyenne est : ", moyenneCalculee
```

**<ins>Focus</ins>**

Cet algorithme parcourt le tableau, additionne tous les éléments pour obtenir la somme totale, puis divise cette somme par le nombre total d'éléments pour calculer la moyenne. Ensuite, il affiche la moyenne calculée. Notez que vous devrez adapter le code selon le langage de programmation que vous utilisez, mais le concept général reste le même.


En javascript ça donne: 

```
function calculerMoyenne(tableau) {
    let somme = 0;
    
    for (let i = 0; i < tableau.length; i++) {
        somme += tableau[i];
    }
    
    const nombreTotal = tableau.length;
    const moyenne = somme / nombreTotal;
    
    return moyenne;
}

// Exemple d'utilisation
const tableau = [10, 20, 30, 40, 50];
const moyenneCalculee = calculerMoyenne(tableau);
console.log("La moyenne est :", moyenneCalculee);
```

En c# ça donne: 
```
using System;

class Program
{
    static void Main(string[] args)
    {
        int[] tableau = { 10, 20, 30, 40, 50 };
        double moyenneCalculee = CalculerMoyenne(tableau);
        Console.WriteLine("La moyenne est : " + moyenneCalculee);
    }

    static double CalculerMoyenne(int[] tableau)
    {
        double somme = 0;

        for (int i = 0; i < tableau.Length; i++)
        {
            somme += tableau[i];
        }

        double nombreTotal = tableau.Length;
        double moyenne = somme / nombreTotal;

        return moyenne;
    }
}

```
