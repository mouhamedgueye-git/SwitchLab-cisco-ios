# Lesson 7 : Make and Undo

## Objectif
Créer des VLANs, vérifier leur enregistrement et les supprimer à l'aide du préfixe d'annulation `no`.

## Commandes apprises
* `vlan 10` / `vlan 20` : Crée les VLANs 10 et 20 (validés lors de la sortie du sous-mode avec `exit` ou `end`).
* `no vlan 10` / `no vlan 20` : Supprime les VLANs 10 et 20 de la base de données VLAN.
* `do show vlan brief` : Vérifie la suppression immédiate depuis le mode de configuration globale.

## Captures d'écran
![Création des VLANs](./screenshots7/lesson07-make-vlans.png)
![Suppression avec no](./screenshots7/lesson07-undo-vlans.png)