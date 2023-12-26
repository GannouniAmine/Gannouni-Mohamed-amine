# Système de Réservation de Bus - README

## Description

Ce programme implémente un système de réservation de bus avec des fonctionnalités telles que la connexion utilisateur, la réservation et l'annulation de billets, la vérification de l'état d'un bus, et la modification des détails d'une réservation.

## Fonctionnalités

1. **Menu Principal**
   - Connexion
   - Quitter

2. **Menu Utilisateur**
   - Réserver un billet
   - Modifier les détails d'une réservation
   - Annuler un billet
   - Vérifier l'état du bus
   - Déconnexion

3. **Fonctions Principales**

   - **Connexion Utilisateur**
     - Fonction `connecterUtilisateur` pour vérifier les informations de connexion.

   - **Réservation de Billet**
     - Fonction `reserverBillet` pour réserver un billet en saisissant les détails du passager.

   - **Annulation de Billet**
     - Fonction `annulerBillet` pour annuler un billet en fournissant le nom du passager.

   - **Vérification de l'État du Bus**
     - Fonction `verifierEtatBus` pour afficher les détails d'un bus spécifique.

   - **Affichage et Modification des Détails de Réservation**
     - Fonction `affichermodifierDetailsReservation` pour afficher et modifier les détails d'une réservation.
## Utilisateurs initiaux

   Le programme est pré-configuré avec les utilisateurs suivants :

   1. Utilisateur : admin, Mot de passe : admin
   2. Utilisateur : admin1, Mot de passe : admin1

## Bus initiaux

   Le programme est également pré-configuré avec les données initiales de trois bus :

   1. Bus 101 - Source: Tunis, Destination: Gafsa, Sièges: 50, Tarif: 25.0, Départ: 6:00, Arrivée: 15:00
   2. Bus 202 - Source: Monastir, Destination: Sousse, Sièges: 40, Tarif: 20.0, Départ: 5:00, Arrivée: 9:00
   3. Bus 303 - Source: Tozeur, Destination: Tunis, Sièges: 30, Tarif: 15.0, Départ: 6:00, Arrivée: 17:00

## Utilisation

1. **Connexion**
   - Entrez le nom d'utilisateur et le mot de passe.

2. **Menu Utilisateur**
   - Sélectionnez une option pour effectuer une action spécifique.

3. **Réservation de Billet**
   - Entrez le numéro du bus et les détails du passager.

4. **Annulation de Billet**
   - Entrez le nom du passager dont vous souhaitez annuler le billet.

5. **Vérification de l'État du Bus**
   - Entrez le numéro du bus pour afficher ses détails.

6. **Modification des Détails de Réservation**
   - Sélectionnez l'option pour afficher les détails, puis suivez les instructions pour effectuer les modifications.

## Données Initiales

Le programme est préconfiguré avec des utilisateurs, des informations sur les bus, et peut être étendu avec des données supplémentaires au besoin.

## Mohamed amine Gannouni

Ce programme a été créé par [Mohamed amine Gannouni].



## Remarque : Veillez à entrer des données valides. Des données incorrectes peuvent entraîner des erreurs dans le programme.
