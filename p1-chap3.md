# Box Model

Le box model en CSS décrit comment les propriétés de taille et d'espacement d'un élément sont calculées. Il se compose de quatre parties: la boîte de contenu, les marges, les bordures et les paddings. La boîte de contenu est l'espace réservé pour le contenu de l'élément, tandis que les marges, les bordures et les paddings sont des espaces supplémentaires autour de cette boîte. Les marges définissent l'espacement entre l'élément et les autres éléments environnants, les bordures définissent une bordure autour de l'élément et les paddings définissent l'espacement entre le contenu de l'élément et sa bordure. Par défaut, la largeur et la hauteur d'un élément sont calculées en incluant ces quatre parties. Cependant, il est possible de changer ce comportement en utilisant la propriété "box-sizing" pour inclure ou exclure certaines parties du calcul. Il est important de comprendre comment ces différentes parties interagissent pour créer des mises en page précises et fiables.

Pour faire en sorte que les box soient à la bonne taille voici le petit truc

```
* {
  box-sizing : borderbox
}
```

## Padding et Margin

Pour ajouter de l'espacement autour d'un élément, on peut utiliser les propriétés "padding" pour ajouter de l'espacement à l'intérieur de l'élément, ou les propriétés "margin" pour ajouter de l'espacement à l'extérieur de l'élément. Par exemple, si on veut ajouter un espace de 20 pixels autour d'un bouton, on peut utiliser cette déclaration:

```
button {
  padding: 20px;
}
```

## Border

Pour ajouter une bordure autour d'un élément, on peut utiliser la propriété "border". Par exemple, si on veut ajouter une bordure rouge de 2 pixels autour d'un paragraphe, on peut utiliser cette déclaration:

```
p {
  border: 2px solid red;
}
```
