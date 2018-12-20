# Évaluation individuelle

## Programmation - Coaching

```
Nom : Lauriano	
Prénom : Ismath
URL de votre compte Github : https://github.com/ismathlau
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
c'est un mode d'echange a travers internet entre un serveur (unité centrale) et un client (ordinateur, internaute)
```



 ### 2. HTML est un langage côté... 

```
Frontend
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
div
{color: pink;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est une framework css qui contient une bibliotheque de code pour rendre une page responsive, accessible sur mobile et pour ajouter plusieurs fonctionnalité a une page web. Il facilite la création d'un site internet.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
	<title></title>
</head>
<body>

</body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
  <!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
	<title></title>
</head>
<body>
<div class="row">
    <div class="col">
    google
    </div>
    <div class="col">
     microsoft
    </div>
    <div class="col">
     apple
    </div>
  </div>
</div>
</body>
</html>



```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html

  <!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
	<title></title>
</head>
<body>
<div class="row">
    <div class="col">
        <a href="https://i0.wp.com/www.grapheine.com/wp-content/uploads/2015/09/nouveau-logo-google.png?zoom=2&resize=750%2C371&quality=90&strip=all&ssl=1" target="blank"> Google 
        </a> 
    </div>
    <div class="col">
        <a href="https://www.one-system.fr/wp-content/uploads/2016/05/logo-microsoft.png" target="blank"> Microsoft 
        </a> 
    </div>
    <div class="col">
        <a href="https://vignette.wikia.nocookie.net/trubetskoyfisher/images/3/3b/Apple_logo.png/revision/latest?cb=20130516231510" target="blank"> Apple 
        </a> 
    </div>
  </div>
</div>
</body>
</html>

```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html

  <!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
	<title></title>
</head>
<body>
<div class="row">
    <div class="col">
         <a href="https://www.google.fr/" target="blank"> Google 
         </a>  
    </div>
    <div class="col">
        <a href="https://www.microsoft.com/fr-fr" target="blank"> Microsoft 
        </a> 
    </div>
    <div class="col">
        <a href="https://www.apple.com/fr/"> Apple 
        </a> 
    </div>
  </div>
</div>
</body>
</html>



```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Backend
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
array, chaine de caractères, booléens , variables , constants
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
My_name = "Ismath"
My_familyname= "Lauriano"
My_github= "https://github.com/ismathlau"
puts My_name
puts My_familyname
puts My_github
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
puts a = 674
puts b = 311
puts c = a % b
puts c
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
cest un module de code utilisé en programmation
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
une api est une interface de programmation applicative un ensemble de service offert par un logiciel qui
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
print "What's your first name? "
first_name = gets.chomp

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

