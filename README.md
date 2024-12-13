## Description du Projet
Ce projet constitue la partie backend d'une application e-commerce distribuée. Il comprend plusieurs microservices pour la gestion des clients,
produits, facturations, et une passerelle API. Ce backend expose des APIs RESTful et implémente une architecture basée sur les microservices pour une meilleure scalabilité et maintenance.
## Structure du Projet
Microservices:
Discovery Service : Gestionnaire de découverte des services basé sur Eureka.
Gateway : Passerelle API pour centraliser les appels.
Customer Service : Gestion des clients avec des endpoints pour CRUD.
Inventory Service : Gestion des produits en stock.
Billing Service : Gestion des factures et des articles associés.
Config Service : Serveur de configuration centralisée.
## Technologies Utilisées
Langage : Java
Framework : Spring Boot
Base de données : H2
Communication : REST API
Découverte de service : Spring Cloud Eureka
Passerelle API : Spring Cloud Gateway
Configuration centralisée : Spring Cloud Config Server
Outils de build : Maven
## Installation et Configuration
1-Cloner le dépôt :
git clone https://github.com/elyahya1999/last_version-ecom-app.git)
cd application-ecommerce
2-Lancer les microservices 
3-Configurer le Discovery Service 

Application E-commerce - Backend
Description du Projet
Ce projet constitue la partie backend d'une application e-commerce distribuée. Il comprend plusieurs microservices pour la gestion des clients, produits, facturations, et une passerelle API. Ce backend expose des APIs RESTful et implémente une architecture basée sur les microservices pour une meilleure scalabilité et maintenance.

Structure du Projet
Microservices :
Discovery Service : Gestionnaire de découverte des services basé sur Eureka.
Gateway : Passerelle API pour centraliser les appels.
Customer Service : Gestion des clients avec des endpoints pour CRUD.
Inventory Service : Gestion des produits en stock.
Billing Service : Gestion des factures et des articles associés.
Config Service : Serveur de configuration centralisée.
Technologies Utilisées
Langage : Java
Framework : Spring Boot
Base de données : H2, MySQL (selon les services)
Communication : REST API
Découverte de service : Spring Cloud Eureka
Passerelle API : Spring Cloud Gateway
Configuration centralisée : Spring Cloud Config Server
Outils de build : Maven
## Exécution
Ordre de démarrage :

config-service -> discovery-service -> autres services.
Démarrez la passerelle API (gateway) en dernier.
Points d'entrée :

Passerelle API : http://localhost:9999
Discovery Service (Eureka) : http://localhost:8761
Endpoints REST principaux :

Customer Service : /customers
Inventory Service : /products
Billing Service : /bills
/fullbill/1
![WhatsApp Image 2024-12-13 à 14 43 23_59fa21f3](https://github.com/user-attachments/assets/5aabd105-5365-4ef1-a8fb-01912b0a338f)
![WhatsApp Image 2024-12-13 à 14 43 56_ca757ac3](https://github.com/user-attachments/assets/4b15e260-c006-4498-9c10-b889329b1c90)
![WhatsApp Image 2024-12-13 à 14 44 28_38642a80](https://github.com/user-attachments/assets/97fb8302-8caa-4dc7-b08a-eabebeb9757f)
![WhatsApp Image 2024-12-13 à 14 44 58_294f403d](https://github.com/user-attachments/assets/0a19c0b3-1504-4f12-afbb-d5b8ef38a1af)
![WhatsApp Image 2024-12-13 à 14 45 24_0521152d](https://github.com/user-attachments/assets/929d933f-a99f-4b91-9199-030049651f3b)







