# Évaluation individuelle

## Programmation - Coaching

```
Nom : Derval
Prénom : Manon
URL de votre compte Github : https://github.com/ManonDerval 
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
L'interaction client-serveur correspond à la relation entre l'utilisateur du terminal et la réponse de ce dernier. C'est une sorte de conversation entre l'homme et la machine. 
```



 ### 2. HTML est un langage côté... 

```
Utilisateur
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html lang="fr">
    <meta charset="utf-8" />
         <link rel="stylesheet" href="nomdelapagecss">
    <title>nom de la page html</title>
    <head>
      <body>
          #Entrer ligne de code ici#
        </body>
    </head>
</html>
      
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
    
   <h1><p>J'adore la programmation</p></h1>
  
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
.h1 
{
   color: pink;    
}

```



### 5. Qu'est-ce que Bootstrap ?

```
Boostrap est un site référençant de nombreuses lignes de code et explications permettant d'apprendre différents langages de programmation.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html lang="fr">
    <meta charset="utf-8" />
         <link rel="stylesheet" href="nomdelapagecss">
    <title>nom de la page html</title>
    <head>
        #Entrer les lignes de code ici
       <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    </head>
</html>

```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="container">
  <div class="row">
    <div class="col-md-4">
    Google
    </div>
    <div class="col-md-4"> 
    Microsoft
    </div>
   <div class="col-md-4">
    Apple
   </div>
    </div>
    </div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container">
  <div class="row">
    <div class="col-md-4">
    <img src="href="https://s-i.huffpost.com/gen/1363750/thumbs/o-LOGO-GOOGLE-570.jpg?6"">
    </div>
    <div class="col-md-4"> 
<img src= "href="https://www.cnetfrance.fr/i/edit/2018/10/microsoft-1-big.jpg"">
    </div>
   <div class="col-md-4">
  <img src="href="http://www.axellescom.com/blog/wp-content/uploads/2018/06/Logo-Apple-2-e1529658710778.jpg"">
   </div>
    </div>
    </div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html

<div class="container">
  <div class="row">
    <div class="col-md-4">
    <img src="href="https://s-i.huffpost.com/gen/1363750/thumbs/o-LOGO-GOOGLE-570.jpg?6""><href=https://www.google.com/>
    </div>
    <div class="col-md-4"> 
<img src= "href="https://www.cnetfrance.fr/i/edit/2018/10/microsoft-1-big.jpg"">
        <href= https://www.microsoft.com/fr-fr/>
    </div>
   <div class="col-md-4">
  <img src="href="http://www.axellescom.com/blog/wp-content/uploads/2018/06/Logo-Apple-2-e1529658710778.jpg""><href= https://www.apple.com/fr/>
   </div>
    </div>
    </div>

```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Serveur
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
String : chaine de caractère ; Array : permet de faire des tableau ; boolean : permet de faire des "si c'est vrai alors..." ; float : integrer des décimales ; integer : chiffres ; absence : permet de vérifier si quelque chose n'existe pas : absence de données.  
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
First_Name="Manon"
LAST_NAME="Derval"
Account="https://github.com/ManonDerval"
puts "#{First_name}"
puts "#{Last_Name}"
puts "#{Account}"

```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a="674"
b="311"
c="52"
puts "#{a} % #{b} 
end
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Gem : lignes de codes qui permettent d'apporter des fonctions supplémentaire à notre page Ruby. 
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

Il s'agit d'une clé d'identification permettant au terminal et au site voulut de communiquer entre eux pour faire fonctionné les codes souhaités. 



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
First_Name="Manon"
hour = 15

if hour < 12
    puts= "bonjour #{First_Name}"
if hour > 12 
    puts="Bonsoir #{First_Name}"
end

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]

array.each do |follow|
    client.follow("handles")
end 


```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

