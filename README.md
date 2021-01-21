# Devoir

Questions de cours ( /5 ):

● qu’est-ce que l’interopérabilité ?
Capacité de communiquer entre deux ou plusieurs systèmes, appareils ou éléments informatiques 

● En quoi le web est un bon exemple d’interopérabilité ?

Différents navigateurs et versions de navigateurs peuvent être utilisés pour consulter le web.
Sur le Web, pour que le navigateur puisse afficher la page web désirée, il doit demander à un serveur web un ou plusieurs fichiers.
Le serveur web doit donc être interopérable avec différents logiciels clients(navigateurs). 
C'est la raison pour laquelle, il utilise du HTML associé à d'autres protocoles standard pour communiquer.


● Quelles sont les trois technologies fondatrices du Web et en quoi elles font un socle
pratique pour l’open data ?

•	Le HTTP : qui est le protocole de transfert réseaux au dessus d'IP. Il permet l'envoie de données.
Données liées à d’autres données pour les contextualiser et les enrichir

•	Le HTML : est un système de balisage ( lagage de description ) normé par le W3C pour permettre de décrire la structure d'une page web.
Données permettant d'être lisibles par un navigateur web

•	Les URI : système de nommage des Ressources. 
Données accessibles via des URL afin de pouvoir pointer dessus.


● Définir ce qu’est un client, ce qu’est un serveur dans le contexte du web.
client : envoie des requêtesau serveur
serveur : envoie des réponses au client

Exercice:
requête fetch pour récupérer le json

fetch('https://otakuotake.herokuapp.com/get2randomcharacters&format=json', { method: 'GET',
               headers: {},
               mode: 'cors',
               cache: 'default'}).then(
    function(response){
        response.json().then(function(data){result = data})
            }
)

Affiche le résultat

Console.log(result)
