# poo3


1.

Créer une classe abstraite HighWay possédant les propriétés suivantes :

currentVehicles (array), 


nbLane (int) et 


maxSpeed (int), 


2.

Créer les getters et setters correspondants au propriétés ci-dessus, 

3.
Faire hériter les classes finales 

MotorWay (4 voies, 130km/h), 

PedestrianWay (1 voie, 10km/h)et 

ResidentialWay (2 voies, 50km/h).

4.
Ajouter à  la classe HighWay une méthode abstraite addVehicule() prenant en paramètre un objet de type Vehicle. 

5.
 implémenter la méthode pour qu’elle ajoute le véhicule au tableau $currentVehicules, uniquement si ce dernier est autorisé sur ce type de voie. Ainsi, pour MotorWay, addVehicule($car) ajoutera bien une voiture au tableau, tandis que addVehicule($bike) ne le fera pas, car il n’est pas possible de rouler en vélo sur une autoroute. Les règles attendues sont les suivantes: 

motorway : tout type de voiture

ResidentialWay : tout type de véhicule

PedestrianWay : Bike et Skateboard uniquement
Astuce : tu peux t’aider de la fonction PHP instanceof() pour t’aider à déterminer le type de véhicule qui est mis en paramètre de la méthode addVehicule().
