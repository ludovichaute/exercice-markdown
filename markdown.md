# Une liste a puces et une liste numerotee

## Une liste a puces

* Pour afficher une liste, commencez la ligne par une astérisque*, un moins - ou un plus +. Là encore, le choix n’a pas d’importance, mais il faut rester cohérent dans votre document.

* Example:
  * Git
  * Markdown
  * GitHub

## Une liste numerotee

* Pour afficher une liste ordonnée, commencez la ligne par un nombre suivit d’un point. Pour que votre markdown soit plus lisible, je vous conseille d’ordonner proprement votre liste.

* Example:
  1. Git
  2. Markdown
  3. GitHub


[Liens vers le Readme](https://github.com/ludovichaute/exercice-markdown)

![image du markDown](markdown.png)

### Insertion d’une image animée, une liste (à puce ou ordonnée) imbriquées (donc plusieurs niveaux hiérarchiques),un bout de code, avec coloration syntaxique

![When My co](https://media.giphy.com/media/349qKnoIBHK1i/giphy.gif)
##### Procedure pour insèrer un image gif
```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```

## Liste à Puces
#### Procedure
Voici un exemple de comment insèrer des listes dans votre MarkDown
##### Unordered List
Utilise les * pour une liste à puces (Unordered List)

```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```
#### Ordered List
Utilisez la numerations pour une liste ordonée (Ordered List)


```
1. Item 1
2. Item 2
  * Item 2a
  * Item 2b
```
#### Liens
Il suffit d'entrer votre TEXTE à afficher suivi du lien

```
[TEXTE](URL)
```
>### Résultat

Voici un example qui decris comme créer des une liste à pouce. Voici un example.

1. [Wiki Markdown](https://fr.wikipedia.org/wiki/Markdown)
     * [Formatage](https://fr.wikipedia.org/wiki/Markdown#Formatage)
     * [Listes](https://fr.wikipedia.org/wiki/Markdown#Listes)
     * [Titres](https://fr.wikipedia.org/wiki/Markdown#Titres)
     *  [Tableaux](https://fr.wikipedia.org/wiki/Markdown#Tableaux)
     *  [Liens](https://fr.wikipedia.org/wiki/Markdown#Liens)
2. [Mise en ouvre](https://fr.wikipedia.org/wiki/Markdown#Mises_en_%C5%93uvre)
3. [Évolution](https://fr.wikipedia.org/wiki/Markdown#%C3%89volutions)

### Code
Il suffit d'entrer les  au début et à la fin suivi d'un ENTER

```
```javascript
function Mark() {
console.log("look ma’, no spaces");
}```
```

### Resultat


```javascript
function Mark() {
console.log("look ma’, no spaces");
}
```
