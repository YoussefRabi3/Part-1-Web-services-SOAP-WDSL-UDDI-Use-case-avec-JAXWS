# Part1_WebService
## Voilà le resultat du web service ce forme d'un fichier XML 
![image](https://user-images.githubusercontent.com/86606579/199036267-c992f77b-7c7b-443f-8692-581b2609d911.png)
# tester les fonctions de la methode conversion sur l'outilis SoapUI Comme vous voyez sur le resultat suivant 
![soap](https://user-images.githubusercontent.com/86606579/199036831-1b8c0d51-e797-40c0-b2fe-2df58844ed6a.JPG)
# Içi on veux voir le resultats de proxy c'est le but de web services c'est connecter le code d'une machine different ou bien distance à l'aide de STub
## Voilà les démarche à suivre 
    - Le client demande au stub de faire appel à la méthode conversion(12)
    - Le Stub se connecte au Skeleton et lui envoie une requête SOAP
    - Le Skeleton fait appel à la méthode du web service
    - Le web service retourne le résultat au Skeleton
    - Le Skeleton envoie le résultat dans une la réponse SOAP au Stub
    - Le Stub fournie lé résultat au client

![resultat proxy](https://user-images.githubusercontent.com/86606579/199037708-59f3fc79-4875-4a97-88c8-ff8dca5d2ce9.JPG)
..




