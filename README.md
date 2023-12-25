# Système de Réservation de Bus (E-Bus)

Ce programme en langage C implémente un système de réservation de bus, appelé E-Bus. Les utilisateurs peuvent se connecter, réserver des billets, annuler des réservations, vérifier l'état du bus et afficher/modifier les détails des réservations.

## Structures de données

Trois structures sont utilisées pour stocker les informations :

1. **Bus** : Contient les détails sur chaque bus, tels que le numéro de bus, la source, la destination, le nombre total de sièges, le nombre de sièges disponibles, le tarif, l'heure de départ et l'heure d'arrivée.
2. **Passager** : Stocke les informations sur les passagers, y compris le nom, l'âge, le numéro de siège et le numéro de bus.
3. **Utilisateur** : Stocke les informations de connexion de l'utilisateur, notamment le nom d'utilisateur et le mot de passe.

## Fonctions principales

1. **afficherMenuPrincipal()** : Affiche le menu principal du programme.
2. **afficherMenuUtilisateur()** : Affiche le menu utilisateur avec des options telles que réserver un billet, annuler un billet, etc.
3. **connecterUtilisateur()** : Connecte un utilisateur en vérifiant le nom d'utilisateur et le mot de passe.
4. **reserverBillet()** : Permet à un utilisateur de réserver un billet pour un bus spécifique.
5. **annulerBillet()** : Permet à un utilisateur d'annuler un billet réservé.
6. **verifierEtatBus()** : Affiche l'état d'un bus spécifique, y compris les détails tels que la source, la destination, le nombre total de sièges, etc.
7. **affichermodifierDetailsReservation()** : Affiche les détails des réservations pour un bus donné et offre la possibilité de modifier les détails d'une réservation existante.

## Utilisation

1. Le programme commence par afficher le menu principal où l'utilisateur peut choisir de se connecter ou de quitter.
2. Une fois connecté, l'utilisateur a accès au menu utilisateur où différentes actions peuvent être effectuées.
3. L'utilisateur peut réserver un billet, annuler un billet, vérifier l'état du bus, afficher et modifier les détails des réservations, et se déconnecter.

## Compilation

Pour compiler le programme, utilisez un compilateur C tel que gcc :

```bash
gcc E-Bus.c -o E-Bus
