📌 Description du Projet
Ce projet est une application Spring Boot permettant la gestion d’inventaire.
Elle inclut la gestion des entités suivantes :

Customer
Supplier
Product
Order
Chaque Supplier possède au moins un Product.
Chaque Customer peut passer des Orders.

🧱 Entités Principales
Entité	Description
Customer	Client de la plateforme
Supplier	Fournisseur de produits
Product	Produit vendu / stocké
Order	Représente une commande contenant des produits
🔗 API Endpoints
Supplier
Method	Endpoint	Description
GET	/api/suppliers	Get all suppliers
POST	/api/suppliers	Add supplier
GET	/api/suppliers/{id}	Get supplier by ID
PUT	/api/suppliers/{id}	Update supplier
DELETE	/api/suppliers/{id}	Delete supplier
Product
Method	Endpoint	Description
GET	/api/products	Get all products
POST	/api/products	Add product
GET	/api/products/{id}	Get product by ID
PUT	/api/products/{id}	Update product
DELETE	/api/products/{id}	Delete product
Customer
Method	Endpoint	Description
GET	/api/customers	Get all customers
POST	/api/customers	Add customer
GET	/api/customers/{id}	Get customer by ID
PUT	/api/customers/{id}	Update customer
DELETE	/api/customers/{id}	Delete customer
Order
Method	Endpoint	Description
GET	/api/orders	Get all orders
POST	/api/orders	Add order
GET	/api/orders/{id}	Get order by ID
PUT	/api/orders/{id}	Update order
DELETE	/api/orders/{id}	Delete order

▶️ Instructions pour exécuter
Importer le projet dans IntelliJ / Eclipse
Vérifier le fichier application.properties et mettre votre DB (MySQL / PostgreSQL)
Démarrer le serveur Spring Boot
✅ Technologies Utilisées
Java 17
Spring Boot 3+
Spring Data JPA
Hibernate
MySQL
Postman (API Tests)
Tester les endpoints avec Postman sur :
