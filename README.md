📋 Projet de Base de Données : Système de Gestion des Commandes
📌 Description
Ce projet implémente une base de données relationnelle pour la gestion des clients, produits et commandes d'un système e-commerce. La structure comprend trois tables principales avec leurs relations.

🗃️ Schéma de la Base de Données
🔷 Tables Principales
Customer (Clients)
Customer_id (PK): Identifiant unique client

customer_Name: Nom du client

customer_Tel: Numéro de téléphone

Product (Produits)
Product_id (PK): Identifiant unique produit

product_name: Nom du produit

category: Catégorie du produit

Price: Prix unitaire

Orders (Commandes)
Customer_id (FK): Référence au client

Product_id (FK): Référence au produit

OrderDate: Date de commande

quantity: Quantité commandée

total_amount: Montant total
