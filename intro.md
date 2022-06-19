# Qu'est ce que le CSS ?

CSS est une abréviation de Cascading Style Sheet

C'est ce qui rend les pages HTML plus jolies et lisibles qu'un tas de texte et d'images sans formattage

Le CSS permet d'ajouter des couleurs, des effets, de positionner des éléments différement pour que la page finale soit plus jolie

Si le HTML est affiché de gauche à droite et de haut en bas (chapitre 4) le CSS est lu de haut en bas et applique le style au fur et à mesure au diffèrents éléments, prenons un selecteur par type (chapitre 2)

```
p {
  font-size: 12px;
  color: white;
}
```

Puis si on ajoute encore une règle sur l'élément p

```
p {
  colore: blue;
}
```

On a créé une **cascade**
