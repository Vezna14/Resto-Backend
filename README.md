# Gestock_prj_G2
Projet Application Java Spring boot React pour le cours appl &amp; systèmes entreprise

# Présentation du projet
Nous allons réaliser une application qui permet de créer des commandes pour la vente de 
produit et gérer le stock de l’entreprise.
# Détails du projet
Utilisateurs : 
- Enregistrer un nouveau client.
- Encoder une commande pour un client
- Facturer une/des commandes client
- Gérer le stock (voir les quantités disponibles / modifier le stock / gérer les prix des produits)
- Abonner le client a une newsletter ou notification en cas de restock d’un article spécifique
(pattern observer +API email).
- Passer commandes auprès du fournisseur par mail (création et envoi du mail contenant la 
liste des articles et leur produit) (API email).
- Créer alerte si stock d’un produit atteint une certaine limite.
- Mettre en place une limite de stock pour un produit spécifique et commander 
automatiquement si le stock descend en dessous de cette limite.
Fonctionnalité supplémentaire :
Si une commande contient des articles dont le stock est nul ou insuffisant, ils seront 
automatiquement retirés de la commande lors de la facturation
