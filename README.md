# Let's Go Biking

## Comment lancer le serveur

Pour lancer le serveur, exécutez les fichiers exécutables dans l'ordre suivant (ActiveMQ doit être lancé avant) :

1. Lancez `ProxyCacheService` :
    - [./Let'GoBiking/ProxyCacheService/bin/Debug/ProxyCacheService.exe](./Let'GoBiking/ProxyCacheService/bin/Debug/ProxyCacheService.exe)
2. Ensuite, lancez `RoutingService` :
    - [./Let'sGoBiking/RouteService/bin/Debug/RoutingService.exe](./Let'sGoBiking/RouteService/bin/Debug/RoutingService.exe)

## Client Java

Le point d'entrée principal pour le client Java se trouve dans le dossier suivant :
- [./JavaClient/src/main/java/com/soap/client](./JavaClient/src/main/java/com/soap/client)

## Format des adresses

Les adresses doivent être saisies au format texte. Par exemple :
`2 rue Soutrane, Valbonne`


## Utilisation du service

Vous pouvez obtenir l'itinéraire complet en utilisant l'opération SOAP `GetItinerary`, ou obtenir l'itinéraire étape par étape en utilisant une Queue.

Les instructions sont affichées sur le côté droit de l'interface.
