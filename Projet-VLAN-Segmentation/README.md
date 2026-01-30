# Lab 1 – VLAN & segmentation réseau

## Objectif
Comprendre et configurer les VLANs sur FortiGate pour segmenter le réseau et sécuriser le trafic interne.

## Matériel / Prérequis
- FortiGate (VM ou GNS3)
- Switch Cisco
- PCs virtuels pour tester la connectivité
- Connexion Internet pour télécharger les images si nécessaire
- Schéma de l'architecture réseau (`architecture.png`)

## Étapes
1. Créer les VLANs sur l’interface FortiGate
2. Configurer les VLANs sur le Switch Cisco
3. Configurer le routage statique
4. Tester l'attribution des adresses IP sur les PCs par le FortiGate

## Résultats attendus
- Les VLANs sont accessibles et isolés selon les règles définies
- Les PCs reçoivent correctement une adresse IP selon leur VLAN d’appartenance

## Fichiers inclus
- `architecture.png` – Schéma réseau
- `config-FortiGate.txt` – Captures d’écran / configuration FortiGate
- `config-Switches.txt` – Captures d’écran / configuration Switch Cisco
- `Lab-VLAN.pdf` – PDF complet du projet avec captures d’écran et explications détaillées
