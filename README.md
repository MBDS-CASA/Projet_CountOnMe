# Améliorer une calculette
Dans ce TP, vous allez reprendre une application existante et l'améliorer : 
1) En rendant l'interface adaptée à toutes les résolutions d'écrans d'iPhone
2) En ajoutant des fonctionnalités supplémentaires
3) En mettant à jour l'architecture du code

# Adapter l'interface de l'application
Dans sa version actuelle, l'interface de l'application ne s'affiche pas correctement. Dans un premier temps, il faut mettre à jour l'interface graphique
comme sur la capture d'écran ci-dessous. 


# Ajouter des fonctionnalités supplémentaires. 
Dans cette version de l'application, seule les opérations d'additions et de soustraction sont implémentées. Il vous est demandé d'ajouter les fonctionnalités suivantes : 
- Multiplication 
- Division entre (attention à la division par zéro)
- Gérer la priorité des opérations en combinant plusieurs opérateurs dans une même opération (la priorité des opérations doit être codé par le groupe, ne pas utiliser de méthodes existantes)
- Effacer un élément dans la chaîne d'opération (de la droite vers la gauche) 
- Réinitialiser toute la chaîne d'opération

# Mettre à jour l'architecture du code
Dans cette version, les opérations sont réalisées dans le View Controller. Par cette approche, le code ne respecte pas vraiment le principe de séparations des couches. 
Vous allez modifier l'architecture du projet pour y ajouter une classe Modele dans laquelle vous placerez toute la logique métier de l'application. 
Vous créez ensuite une instance de cette classe dans le view modele afin de gérer les opérations. 


