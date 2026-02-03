# Lab 2 – Sécurité avancée FortiGate : Policies, Profils, NAT & VIP

## Objectif
Mettre en place des politiques de sécurité avancées sur FortiGate
afin de contrôler, inspecter et publier des flux réseau de manière sécurisée.

## Scénario
Un réseau interne segmenté par VLAN doit :
- accéder à Internet de façon contrôlée
- être protégé par des profils de sécurité
- exposer un service interne via une IP publique (VIP)

## Technologies utilisées
- FortiGate (VM / GNS3)
- Switch Cisco
- VLANs
- Firewall Policies
- Security Profiles (AV, Web Filter, IPS)
- NAT & Virtual IP (VIP)

## Étapes principales
1. Création des politiques firewall inter-VLAN
2. Application des profils de sécurité
3. Configuration du NAT sortant
4. Mise en place d’un VIP pour publier un service interne
5. Tests de sécurité et de connectivité

## Résultats attendus
- Trafic autorisé uniquement selon les règles définies
- Inspection du trafic via profils de sécurité
- Accès Internet fonctionnel et sécurisé
- Service interne accessible depuis l’extérieur via VIP

## Fichiers inclus
- `architecture.png` – Schéma réseau
- `config-FortiGate.txt` – Captures de configuration FortiGate
- `config-Switches.txt` – Configuration Switch (si applicable)
- `Lab-Security.pdf` – Documentation complète du lab
