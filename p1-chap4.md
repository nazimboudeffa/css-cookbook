# Le positionnement

Les éléments HTML sont affiché de gauche à droite et de haut en bas, c'est ce qu'on appelle le flux HTML, pour mettre en page son code HTML il faut apprendre à positions ses éléments, pour celà on va voir trois propriétés

* float
* display
* position

## La propriété : position

Le positionnement en CSS permet de contrôler la façon dont les éléments sont disposés sur une page web. Il existe plusieurs valeurs possibles pour la propriété "position" : "static", "relative", "absolute" et "fixed". La valeur "static" est la valeur par défaut et signifie que l'élément est disposé dans le flux normal du document. La valeur "relative" permet de décaler un élément par rapport à sa position initiale dans le flux normal. La valeur "absolute" retire l'élément du flux normal et permet de le placer à une position précise en utilisant les propriétés "top", "bottom", "left" et "right". Enfin, la valeur "fixed" est similaire à "absolute", mais l'élément reste à la même position même lorsque la page est scrolée. Utiliser avec parcimonie, cela demande une bonne compréhension du fonctionnement du layout.

## La propriété : display

La propriété CSS "display" permet de contrôler la façon dont un élément est affiché sur une page web. Il existe plusieurs valeurs possibles pour cette propriété, chacune ayant un comportement différent. La valeur "block" permet de créer un élément qui occupe toute la largeur disponible, avec une nouvelle ligne avant et après. Les éléments HTML tels que les titres et les paragraphes ont généralement cette valeur par défaut. La valeur "inline" permet à un élément de s'insérer dans le flux de texte, sans créer de nouvelle ligne. Les éléments HTML tels que les liens et les images ont généralement cette valeur par défaut. La valeur "none" permet de masquer un élément, il n'occupera plus de place dans la page. La valeur "flex" et "grid" sont des valeurs avancées pour créer des layout flexibles et adaptatifs. Il est important de bien comprendre l'effet de chaque valeur pour utiliser efficacement cette propriété dans vos styles CSS.

## La propriété : float

La propriété CSS "float" permet de faire flotter un élément à gauche ou à droite de la page, en le faisant sortir du flux normal des éléments. Cela permet notamment de créer des dispositions de type "boîte à côté de boîte", où plusieurs éléments sont disposés côte à côte. Les valeurs possibles pour cette propriété sont "left", "right" et "none" (valeur par défaut). Lorsqu'un élément est flottant, les éléments suivants s'enrouleront autour de lui, sauf si on utilise la propriété clear. Il est important de noter que les éléments flottants ne prennent pas en compte la hauteur de leur contenu dans le calcul de la hauteur de leur parent, il peut causer des problèmes de layout si on ne fait pas attention. Il existe des alternatives comme flexbox et grid layout qui peuvent être utilisées pour créer des dispositions plus flexibles et modernes.
