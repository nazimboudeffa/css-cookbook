# Box Model

Le box model en CSS décrit comment les propriétés de taille et d'espacement d'un élément sont calculées. Il se compose de quatre parties: la boîte de contenu, les marges, les bordures et les paddings. La boîte de contenu est l'espace réservé pour le contenu de l'élément, tandis que les marges, les bordures et les paddings sont des espaces supplémentaires autour de cette boîte. Les marges définissent l'espacement entre l'élément et les autres éléments environnants, les bordures définissent une bordure autour de l'élément et les paddings définissent l'espacement entre le contenu de l'élément et sa bordure. Par défaut, la largeur et la hauteur d'un élément sont calculées en incluant ces quatre parties. Cependant, il est possible de changer ce comportement en utilisant la propriété "box-sizing" pour inclure ou exclure certaines parties du calcul. Il est important de comprendre comment ces différentes parties interagissent pour créer des mises en page précises et fiables.

Pour faire en sorte que les box soient à la bonne taille voici le petit truc

```
* {
  box-sizing : borderbox
}
```
