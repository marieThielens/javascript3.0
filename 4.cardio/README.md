# Les méthodes des tableaux

## Exercices :
1. Filtrer les inventeurs qui sont né entre 1500 et 1600.
2. Renvoie un nouveau tableau avec le nom et prenoms des inventeurs.
3. Trier les inventeur par année de naissance du plus vieux au plus jeune.
4. Le nombre d'années de vie des inventeurs, faire le total.
5. Sort  : trier les inventeurs par le nombres d'années qu'ils ont vécu.
6. trier par ordre alphabétique en fonction du nom de famille

## Methodes :

      const tableau = [
          { nom : 'element1',
            nom : 'element2', 
            nom : 'element3'
          }
          ];

- tableau.push() : ajoute un element à la fin du tableau
- tableau.length() : la longueur du tableau, le nombre d'éléments présent dans le tableau
- tableau.join() : concatène les éléments du tableau en une chaîne de caractère
- tableau.splice() : ajoute ou retire des éléments d'un tableau
- tableau.indexOf(): La place de l'élément dans le tableau
- tableau.prototype() : ajoute des propriétés à tous les éléments du tableau
- tableau.shift() : supprime le 1er élément du tableau et retourne cet élémént
- tableau.slice() :  extrait une portion du tableau
- tableau.filtre() : crée et retourne un nouveau tableau contenant tous les éléments du tableau d'origine qui remplissent une condition déterminée par la fonction callback.

        const result = tableau.filter(word => word.length > 6);
        // filtre dans le tableau les mots plus grand que 6

- tableau.map() : crée un nouveau tableau avec les résultats de l'appel d'une fonction fournie sur chaque élément du tableau appelant

        var array1 = [1, 4, 9, 16];

        // pass a function to map
        const map1 = array1.map(x => x * 2);
        console.log(map1);
        // expected output: Array [2, 8, 18, 32]

- tableau.reduce() : prend chaque valeur du tableau(de gauche à droite) afin de la réduire en une seule valeur. Permet de faire un total d'années de vies de plusieurs personnes par exemple.
- tableau.sort() : trie les éléments d'un tableau et renvoie le tableau


