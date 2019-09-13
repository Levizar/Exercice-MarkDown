### [Description et histoire du MakDown](/Describe.md) ###

# Syntax MarkDown #
La syntaxe de MD et semblable à celle de Html:



## Paragraphe ##
Pour un paragraphe, il faut simplement sauter deux lignes et taper le texte du paragraphe. Un seul saut de ligne correspond à un retour et non un chanrement de paragraphe.


Voici un exemple:


paragraphe 1


paragraphe 2,
simple retour à la ligne du code, pas de retour à la ligne dans le visuel


Voici le code des lignes ci-dessus: 
```


paragraphe 1


paragraphe 2,
simple retour à la ligne du code, pas de retour à la ligne dans le visuel
```

## citation ##

Les citations doivent simplement être indentées par un chevron
exemple:

> Voici une citation

Voici le code pour effectuer cette citation:

```
> voici une citation
```

## Comment créer des titres et sous titres ##

# 1er titre #
## 2e titre ##
### 3e titre ###


```
# 1er titre #
## 2e titre ##
### 3e titre ###
```
-mettre son/ses titres entre "#"

   et rajouter un ou plusieurs "#" en fonction du niveau des titres.

## Création de ligne ##

L'on peut créer une ligne sur la longueur de la page en alignant au moins 3 astérisques comme présenté ci-dessous:

Voici une ligne ci-dessous
***
Très belle ligne ci-dessus

```
Voici une ligne ci-dessous
***
Très belle ligne ci-dessus
```

L'on peut aligner plus d'astérisque, à votre convenance pour la clarté du code.

## Echappement des caractères servant au marquage de markdown ##

Les marqueurs ne peuvent être utilisé "simplement" dans du texte.
Afin de les afficher, il faut les échapper avec un antislash.

Voici les caractères qui doivent être échappés:
\\ \* \` \- \_ \[\] \(\) \{\} \# \+ \. \!

Voici le code:
```
\\ \* \` \- \_ \[\] \(\) \{\} \# \+ \. \!
```

## Création de lien ##

[Lien cliquable vers google](www.google.com)

Voici comment procéder:
```
[Lien cliquable vers google](www.google.com)
```
L'on peut également créer des liens relatifs comme celui-ci:

[Description et histoire du MakDown](/Describe.md)

Pour cela, il suffit de remplacer le lien pour un chemin relatif, voyez plutot:

```
[Description et histoire du MakDown](/Describe.md)
```

## Lien vers des images ##

![Logo Markdown](/Markdown-mark.svg)

Voici le code permettant ce lien:

```
![Logo Markdown](/Markdown-mark.svg)
```
Le texte entre \[  \] s'affiche lorsque l'image ne peut pas se charger.


## Les listes ordonnées ##

1. Une liste ordonée commence par un numéro.

2. Suivi d'un point

Voici comment procéder:
```
1. 1er liste.

2. 2e liste.

```
## Les listes non ordonnées ##

Pour créer une liste non ordonées il suffit de placer un tirer avant son texte
- tiret
- valeur
```
-Listes non ordonées
-...
-...
```
## Les listes imbriqués ##
Pour créer le 1er niveau de la liste il faut placer une astérix avant le texte
Pour imbriqué des listes il faut laisser 2 espace avant l'asterix  pour chaque niveau

* first level
  * second level
      * third level
      * third level second line
* first level
  * second level
      * third level
      * third level second line
      * first level
  * second level
      * third level
      * third level second line

```
* first level
  * second level
      * third level
      * third level second line
* first level
  * second level
      * third level
      * third level second line
      * first level
  * second level
      * third level
      * third level second line
```

## Création de tableau ##

commande | nom de commande | visuel
- | :-: | -:
colonne 1 | colonne 2 | colonne 3

Voilà le code de ce tableau:
```
commande | nom de commande | visuel
- | :-: | -:
colonne 1 | colonne 2 | colonne 3
```

## Fenced Code Blocks ##

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Il suffit pour cela de baliser le code avec au début du code ´´´ et ´´´ à la fin

