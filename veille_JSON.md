# Veille JSON
## English Version
### JavaScript Object Notation
*created in 2002/2005* by **Douglas Crockford**   
His working path : from radio/television to Javascript's development to Paypal(present)
![XML/JSON public interest](https://cdn-images-1.medium.com/max/1600/1*cU8rwGI0WgtCWP91SIy3-w.png)
***
#### Advantages
* FAST
    - very small syntax **and** light weighted
    - easy to use
* SUPPORT   
&nbsp; &nbsp; huge amount of browsers with compatibility
* SERVER PARSING   
&nbsp; &nbsp; fast server-side parsing
* SHARING DATA   
&nbsp; &nbsp; excellent tool for sharing all kinks of data
    + audio
    + video
    + ... 
***
#### Disadvantages
* NO HERROR HANDLING   
&nbsp; &nbsp; you must use protocols(like *Ajax*) to know if errors have been made through the parsing
* SECURITY
    - browsers wrap the JSON response, they execute the call fonction
    - makes the web-app hosting vulnerable   

|**How to prevent it ?**|
|:-:|
|use methods to secure cookies|
|existing code testing tools|
|user's access log managed|
|use an API|
|even better, a token-based API, like [JWT](https://jwt.io/)|
|implement error handling|



---
## Version française
### JavaScript Object Notation
*créé en 2002/2005* par **Douglas Crockford**   
Son cheminement professionnel : a commencé par des études de radio/télévision, développé le langage Javascript et travaille aujourd'hui pour Paypal
![XML/JSON intérêt du public](https://cdn-images-1.medium.com/max/1600/1*cU8rwGI0WgtCWP91SIy3-w.png)
***
#### Avantages
* RAPIDE
    - syntaxe très simple **et** faible en poids/taille
    - facile à utiliser
* SUPPORT   
&nbsp; &nbsp; compatible avec un grand nombre de navigateurs
* SERVER PARSING   
&nbsp; &nbsp; analyse côté serveur très rapide
* SHARING DATA   
&nbsp; &nbsp; excellent outil pour partager tous types de data
    + audio
    + video
    + ...
*** 
#### Désavantages
* PAS DE GESTION D'ERREUR   
&nbsp; &nbsp; on est obligé d'utiliser des protocoles(comme *Ajax*) si des erreurs ont été faites durant l'analyse/compilation/recompilation/transfert
* SECURITE
    - les navigateurs assemblent la réponse eux-mêmes, en exécutant la fonction d'appel
    - cela rend l'hébergement de vos sites vulnérables à une grande variété d'attaques   

|**Pour combattre ces failles, que puis-je faire ?**|
|:-:|
|utiliser des méthodes pour sécuriser les cookies|
|utiliser des outils de test de codes déjà existants|
|gérer proprement les comptes utilisateurs et leurs identifiants|
|utiliser une API|
|encore mieux, une API protégée par une clé, like [JWT](https://jwt.io/)|
|coder soi-même la gestion d'erreurs|

