#Exercice 5

**Durée :** :warning: 25 mins :warning:

En utilisant jQuery le plus possible (sinon vanilla, c'est ok aussi), mettez en place les comportements suivants : 

1. Une fois le document chargé, ajouter un attribut "data-count-css" au bouton "Open Google in new tab" ayant comme valeur le nombre de fichiers CSS inclus dans la page.
  
2. Une fois toute la page chargée, si le nombre total de balises contenues dans la balise body est supérieur ou égal à 1000 alors ajouter une balise script à la fin de la balise body. Sinon, ajouter la balise script au début de la balise body. Cette balise script devra contenir le code nécessaire à la mise en place du point 3 :

2. Chaque fois que la fenêtre est redimensionnée, logger dans la console la valeur en pixels de la distance séparant le bouton "Open Google in new tab" du haut de la page ainsi que celle le séparant de son parent direct.

---

1. Ajouter la librairie [Lodash](https://lodash.com/) au projet de la façon qui vous semble la meilleure.

2. Inclure la libraire dans le bundle JS de la homepage.

3. Créez le tableau suivant : 

```js
var stars = [
  {
    name: 'Morgan Freeman',
    chauve: false,
    cool: true,
  },
  {
    name: 'Bruce Willis',
    chauve: true,
    cool: true
  },
  {
    name: 'Cyril Hanouna',
    chauve: false,
    cool: false
  },
  {
    name: 'Pascal Obispo',
    chauve: true,
    cool: false
  }
];
```

4. En utilisant Lodash et en une seule ligne de code, afficher dans la console le(s) nom(s) de la/des star(s) chauve(s) et pas cool(s).

---

- [Introduction](../README.md)
- [Exercice 1](./exo1.md)
- [Exercice 2](./exo2.md)
- [Exercice 3](./exo3.md)
- [Exercice 4](./exo4.md)
- **Exercice 5**
- [Exercice 6](./exo6.md)
