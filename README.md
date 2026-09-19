# QSPhoto Paiement

Projet Android de départ pour l'application d'encaissement QSPhoto.

## Ce qui fonctionne déjà
- Interface simple pour le stand/studio
- Boutons 5 €, 10 €, 15 €, 20 €
- Montant personnalisé
- Mode démo local
- Dépendance Stripe Terminal Android préparée
- Workflow GitHub Actions pour produire un APK

## Important
Le paiement Stripe réel n'est volontairement pas activé dans cette première version.
La clé secrète Stripe ne doit jamais être mise dans l'APK.

Pour les paiements réels, il faudra ajouter un petit backend sécurisé (par exemple sur le serveur QSPhoto/IONOS) qui crée les Connection Tokens et PaymentIntents Stripe.
