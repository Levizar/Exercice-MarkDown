</Describe.md>

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

Pour créer un lien hypertexte, il faut entourer le lien en question de chevron:

<www.google.com>

code:
```
<www.google.com>
```

## Lien vers des images ##

![Logo Markdown](/Markdown-mark.svg)

Voici le code permettant ce lien:

```
![Logo Markdown](/Markdown-mark.svg)
```
Le texte entre \[  \] s'affiche lorsque l'image ne peut pas se charger.

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

