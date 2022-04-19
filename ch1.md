## Code HTML de base

Ce que vous lisez entre `<!-- ... -->` ce sont des commentaires sinon vous pouvez lire [l'introduction](https://github.com/nazimboudeffa/handbook-css/blob/main/intro.md)

```
<!DOCTYPE html>
<html>
  <head>
    <title>Ceci est une Page</title>
    <!-- external -->
    <link href='./style.css' rel='stylesheet'>
  </head>
    <!-- internal -->
    <style>
      p : {
        background-color : blue;
      }
    </style>
  <body>
    <!-- inline -->
    <p style="color : red">Ceci est un paragraphe</p>
  </body>
</html>
```

## Ajouter du CSS

Il y a trois manières d'ajouter du CSS à un élémenet

* inline
* internal
* external

**Inline**

`<p style="color : red;">Ceci est un paragraphe</p>`

**Internal**

Dans le head juste après la balise title

```
<style>
  p {
    colore : red;
  }
</style>
```

**External**

Dans le head juste après la balise title

```
<link href='./style.css' rel='stylesheet'>
```
