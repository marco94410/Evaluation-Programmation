# Évaluation individuelle

## Programmation - Coaching

```
Nom : Akonde	
Prénom : Marc-Olivier
URL de votre compte Github : https://github.com/marco94410
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
A travers un réseau c'est lorsque le client envoi des requêtes et que le serveur y repond. Il s'agit d'échanges entre deux parties.
```



 ### 2. HTML est un langage côté... 	

```
client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
    <head>
        <meta charset="utf-8" />
        <title>Titre</title>
    </head>

    <body>
    
    </body>
</html>

```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
p { color: green;
}

```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est un framework qui sert a utiliser des tamplates en utilisant des codes HTML et CSS en organisant la page web simplement 
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html>
     <link href="bootstrap/css/bootstrap.min.css" rel="stylesheet">
    <head>
        <meta charset="utf-8" />
        <title>Titre</title>
    </head>

    <body>
    
    </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div>
    <img src="images/logo_google.jpg" alt="logo google" />
   
</div>

<div>
  <img src="images/logo_microsoft.png" alt= "logo microsoft" />
    
</div>

<div>
   <img src="images/logo_apple.jpg" alt="logo apple" />
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div>
<a href="https://www.google.fr/"> <img src="images/logo_google.jpg" /> </a>
    
</div>

<div>
<a href="https://www.microsoft.com/fr-fr"> <img src="images/logo_microsoft.jpg" /> </a>
</div>

<div>
  <a href="https://www.apple.com/fr/"> <img src="images/logo_apple.jpg" /> 
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
 # Ceci est un 
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
first_name="Marc-Olivier"
puts first name 

last_name="AKONDE"
puts last_name

my_account="https://github.com/marco94410"
puts my account

```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby

a = 674
b = 311 
c = a % b
puts c
# Le résultat attendu est 52.
```



### 14. Qu'est-ce qu'une gem ? 

Une gem est un module de code associé a Ruby qui permet des fonctios particulieres comme l'authentification automatique par exemple 



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Une Api est une sorte de clé unique qui permet à deux programmes de communiquer. Elle sert d'interface pour la programmation
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

