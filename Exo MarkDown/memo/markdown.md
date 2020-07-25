### Mémo syntaxique pour MarkDown


## Les titres

`#` affiche un `<h1>`

`###` affiche un `<h3>`

`######` affiche un `<h6>`

```
TITRE PRINCIPAL
===============
```

⇒ Donne

TITRE PRINCIPAL
===============

```
Titre Secondaire
----------------
```

⇒ Donne

Titre Secondaire
----------------


## Mise en forme du texte

`*Mon texte italique*` ⇒ *Mon Texte italique*

`_Mon autre texte italique_` ⇒ _Mon autre Texte italique_

`**Mon texte gras**` ⇒ **Mon Texte gras**

`__Mon autre texte gras__` ⇒ __Mon autre Texte gras__

`___Mon Texte en gras et italique___` ⇒ ___Mon Texte en gras et italique___

`__Mon Texte en gras *bout italique*__` ⇒ __Mon Texte en gras *bout italique*__


## Les listes

```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
    * Item 2b1
```

⇒ Donne

* Item 1
* Item 2
  * Item 2a
  * Item 2b
    * Item 2b1
```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

⇒ Donne

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   2. Item 3b


## Les liens
```
http://github.com

[GitHub](http://github.com)
```

⇒ Donne

http://github.com

[GitHub](http://github.com)


## Les images

```
![Texte de l'image](https://cdn.futura-sciences.com/buildsv6/images/wide1920/6/6/d/66da29be61_99905_google-images-rechercher.jpg)
```

⇒ Donne

![Texte de l'image](https://cdn.futura-sciences.com/buildsv6/images/wide1920/6/6/d/66da29be61_99905_google-images-rechercher.jpg)

```
![Image de souris](mouse.jpg)
```

⇒ Donne

![Image de souris](mouse.jpg)


## Un lien sur une image

```
[![Texte de l'image](https://i1.pngguru.com/preview/442/817/105/circular-icon-set-linkedin-in-logo-png-clipart.jpg)](https://www.linkedin.com/in/gerardo-cella/)
```

⇒ Donne

[![Texte de l'image](https://i1.pngguru.com/preview/442/817/105/circular-icon-set-linkedin-in-logo-png-clipart.jpg)](https://www.linkedin.com/in/gerardo-cella/)


## Afficher du code

Indenter de 4 espaces devant le code 

&nbsp;&nbsp;&nbsp;&nbsp;if($test=="test"){

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$message = "Salut";

&nbsp;&nbsp;&nbsp;&nbsp;}

⇒ Donne

    if($test=="test"){
        $message = "Salut";
    }

**OU**

&grave;&grave;&grave;

if($test=="test"){

&nbsp;&nbsp;&nbsp;&nbsp;$message = "Salut";

}

&grave;&grave;&grave;

⇒ Donne

```

if($test=="test"){

    $message = "Salut";

}

```

**OU**

&grave;&grave;&grave;php

if($test=="test"){

&nbsp;&nbsp;&nbsp;&nbsp;$message = "Salut";

}

&grave;&grave;&grave;

⇒ Donne

```php
if($test=="test"){
    $message = "Salut";
}
```


#### Code sur une ligne

Mettre un &grave;&lt;code>&grave; dans une ligne.

⇒ Donne

Mettre un `<code>` dans une ligne.


## Liste de tâches

```
- [x] Tâches terminée
- [ ] Tâches en cours
```

⇒ Donne

- [x] Tâches terminée
- [ ] Tâches en cours


## Les tableaux

```
Titre 1 | Titre 2 | Titre 3
--|--|--
Contenu celulle 1 | |Contenu celulle 3
Contenu celulle 1 ligne 2 | Contenu celulle 2 ligne 2 | Contenu celulle 3 ligne 2
```

⇒ Donne

Titre 1 | Titre 2 | Titre 3
--|--|--
Contenu celulle 1 | |Contenu celulle 3
Contenu celulle 1 ligne 2 | Contenu celulle 2 ligne 2 | Contenu celulle 3 ligne 2


## Emoji

[Liste d'emoji](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

```
Je suis heureux. :satisfied:
```

Je suis heureux. :satisfied:


## Le blockquote

```
> #### Titre du blockquote
>
> - Un item de la liste
> - Un item de la liste
>
>  *Italique* texte et **Gras**.
>
>> Blockquote dans blockquote
```

⇒ Donne

> #### Titre du blockquote
>
> - Un item de la liste
> - Un item de la liste
>
>  *Italique* texte et **Gras**.
>
>> Blockquote dans blockquote


## Ligne de séparation

```
***

---

_________________
```

⇒ Donne


***

---

_________________


## Echapper des caracteres

```
Echappement du premier \*

Exemple : Ceci est un phrase avec du texte \***Gras\***
```

⇒ Donne


Echappement du premier \*

Exemple : Ceci est un phrase avec du texte \***Gras\***

Voici la liste des caractere que l'on peut échapper ⇒ ```\ ` * _ { } [ ] ( ) # + - . ! |```


## Les balises html

Toutes les balise html sont reconue.

```
<p>Paragraphes avec un <em>em</em>.</p>

<span style="color:blue">*Bleu italique.*</span>
```

⇒ Donne

<p>Paragraphes avec un <em>em</em>.</p>

<span style="color:blue">*Bleu italique.*</span>

> On peut remarquez que sa ne fonctionne pas on ne peus pas mettre d'attributs dans les balises html.


> # Fin du fichier
> 
> Des mise à jour seront possible si je vois de nouvelle fonctionalité de ***Markdown***