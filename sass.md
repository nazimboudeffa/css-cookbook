# SASS

C'est un compilateur qui va transformer nos fichies.scss en .css et il a quelques trucs sympathiques

## variables

`$maCouleur: bleu;`

sert à éviter de répéter la couleur que l'on a défini et qu'on souhaite changer dans le code css

## inclure des selecteurs dans d'autres selecteurs

on peu ajouter des selecteur dans d'autres selecteur et ça nous fera comme si on appellait le mode parent enfant

## &

Permet de faire appel au selecteur à l'intéreur de ce dernier avec une pseudo classe

## import

@import 'maclasse.scss'

permet d'importer des fichiers dans d'autres fichiers pour faciliter la lecteur et l'organisation on fera attention à nommer ces fichier avec un _ au début du nom

## mixin

```
@mixin maFonction {

}
```

permet d'éviter d'écrire à chaque fois le même code CSS et donc il devient sous forme de fonction

## mixin parameters

on peut ajouet des paaramètres aux fonctions Sass

## extend

permet d'ajouter des propriété en etendant un selecteur déjà défini

## calculations

on peut effectuer des calculs
