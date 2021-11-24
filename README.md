# TEST-OF-IWACO
# Test iwaco

# Partie I

# Informations générales

# Nom et prénom: Rachid MESKY

# Actuallement En recherche active

## Vous voulez travailler en tant que:    developpeur backend
 
## combien d'année d'expérience avez-vous?    2


## partie 2

### Questions générales 

### 1- Git est un système de gestion de code distribué et de contrôle de version gratuit et open source.
### 2- Sass est un préprocesseur CSS et réduit la répétition des CSS et donc fait gagner du temps.
### 3- Composer vous aide à déclarer, gérer et installer les dépendances des projets PHP.
### 4- Les Design Patterns, ou modèles de conception,
 sont des solutions éprouvées à des problèmes récurrents de design ou de code.
 Utile au designer et au développeur, le design pattern améliore aussi l’utilisabilité du site ou de l’application.
 Ces « patrons de conception », réutilisables, rendent l’interface plus intuitive pour l’utilisateur.
### 5- La commande Diff est utilisée dans git pour suivre la différence entre les modifications apportées sur un fichier.

## =>Javascript

### 6- (CORS) est un mécanisme de navigateur qui permet un accès contrôlé aux ressources situées en
 dehors d'un domaine donné.
### 7- == convertit les valeurs des variables dans le même type avant d'effectuer la comparaison.
 C'est ce qu'on appelle la coercition de type .

===ne pas faire une conversion de type (contrainte) et retourne vrai que si les deux valeurs et types
 sont identiques pour être comparés les deux variables. 

### 8- this: permet d'obtenir l'adresse de l'objet courant c'est-à-dire la référence sur l'instance courante.

## =>CSS

### 9- inline: respectez les marges gauche et droite et le remplissage, mais pas en haut et en bas.
ne peut pas avoir une largeur et une hauteur définies.
permettre aux autres éléments de s'asseoir à leur gauche et à leur droite.

block: respecte tous ceux.
forcer un saut de ligne après l'élément de bloc.
acquiert toute la largeur si la largeur n'est pas définie.

### 10- Est-il possible de créer un site web responsive sans media queries ?
oui, Avec Grid & Flexbox, 
vous pouvez certainement créer des sites Web réactifs sans spécifier de points d'arrêt de requête multimédia. 

### 11- Expliquez les avantages/inconvénients de l'utilisation d'éléments inline-block, flex ou float?

-avantages de 'inline-block': permettre aux autres éléments de s'asseoir à leur gauche et à leur droite.
respectez les marges et le remplissage de gauche, de droite, du haut et du bas.
vous permet de régler la hauteur et la largeur.
-Inconvinients de 'inline-block': en dessous d'un élément ne peut être affichée inline-block si elle était déjà 
inline par défaut.
Ce que cela signifie, c'est qu'au lieu d'utiliser un <div> élément, vous devez utiliser un <span> élément.

-avantages de 'flex':  la possibilité de remplir un espace supplémentaire sans avoir besoin d'utiliser Javascript,
et flexbox est pris en charge par la plupart des principaux navigateurs.
-Inconvinients de 'flex': Flexbox se complique avec des mises en page plus complexes et
se limite à une seule direction (horizontale ou verticale).



-avantages de 'float': permet à un développeur d'incorporer des colonnes de type tableau dans
 une mise en page HTML sans utiliser de tableaux.
-Inconvinients de 'float': Tout flotter peut créer beaucoup d'incohérences,
 selon la largeur d'un écran et la hauteur de certains éléments rendus,
 vous pouvez vous retrouver avec un méli-mélo de jag d'écran.


 ## =>php:

## 1- 
#### <?php
 
#### for( $i=1; $i<=100; $i++ )
####{
    #### if($i%3==0 && $i%5==0){
    #### echo "DevOps\n";
    #### }

    #### elseif($i%3==0){
        #### echo "Dev\n";
    #### }
    
    #### elseif ($i%5==0) {
        #### echo "Ops\n";
    #### }
    
    #### else{
    #### echo $i."\n";
    #### }
#### }


#### ?>


## 2-
	
#### <?php
#### // fonction qui vérifie si paramètre est en fait un nombre premier
#### function IsPrime($n)
#### {
 #### for($x=2; $x<$n; $x++)
   #### {
      #### if($n %$x ==0)
	   ####   {
		####   return 0;
		  #### }
    #### }
  #### return 1;
   #### }
#### echo isPrime(73) ? 'Prime' : 'Composite';
#### ?>

### 3-
	
#### une loop pour afficher les valeurs de l'array, à condition de: si item est sup ou égale à 0 on va l'afficher,
#### sinon on va afficher le power de l'item. output est comme suit: [0] => 3
    #### [1] => 8
    #### [2] => 16
    #### [3] => 0
    #### [4] => 2
    #### [5] => 81

## =>database:

### 1-
select id, count(*) from employee group by create_at

### 2-
select id from employee where create_at like '%2021-10-03 %'

### 3-
select id from employee
where email LIKE '[b,c,d,f,g,h,j,k,l,m,n,p,q,r,s,t,v,w,x,z]%[0-9]@%'

### 4-
select lower(first_name), lower(last_name) from employee

### 5-
alter table employee
rename COLUMN create_at TO date_creation;

### 6-
L'instruction DELETE est utilisée lorsque nous voulons supprimer tout ou partie des enregistrements de la table,
tandis que l'instruction TRUNCATE supprimera des lignes entières d'une table.

### 7-
select first_name, last_name, MIN(salary) from employee;
select first_name, last_name, MIN(salary) from employee
where salary > 10000 ;
  
  ## Partie 3: pardon le fichier xd ne veut pas afficher, car j'ai pas le lecteur de fichier xd sur mon pc











