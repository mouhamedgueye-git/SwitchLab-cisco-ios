# Lesson 10 : Test 1 - Investigate (Évaluation)

## Objectif
Auditer un commutateur mal configuré, identifier les anomalies (nom d'hôte incorrect, VLANs manquants, port désactivé) et appliquer les correctifs avant de sauvegarder.

## Commandes utilisées lors de l'audit et de la réparation
1. **Diagnostic :**
   * `show running-config`
   * `show vlan brief`
   * `show interface status`
2. **Corrections en mode configuration (`conf t`) :**
   * `hostname Branch-SW1`
   * `vlan 10`, `vlan 20`, `vlan 30`
   * `interface g0/3` puis `no shutdown`
3. **Vérification et sauvegarde :**
   * `show running-config`
   * `copy running-config startup-config`

## Démonstration vidéo
> Si le lecteur vidéo ne s'affiche pas directement sur GitHub, [clique ici pour télécharger/voir la vidéo](./screenshots10/lesson10-test1-investigate.mp4).

https://github.com/mouhamedgueye-git/SwitchLab-cisco-ios/screenshots10/lesson10-test1-investigate.mp4