# Lab 3 – VPN Site-to-Site FortiGate

## Objectif
Mettre en place un VPN IPsec site-à-site sécurisé entre deux sites distants
afin de permettre une communication chiffrée entre les réseaux internes.

## Scénario
Deux sites distants disposent chacun d’un FortiGate.
Les réseaux internes des deux sites doivent communiquer de manière sécurisée
via un tunnel VPN IPsec site-à-site.

## Technologies utilisées
- FortiGate (VM / GNS3)
- VPN IPsec Site-to-Site
- Phase 1 / Phase 2
- Firewall Policies

## Étapes principales
1. Configuration Phase 1 IPsec
2. Configuration Phase 2 IPsec
3. Création des policies firewall
4. Configuration du routage
5. Tests de connectivité inter-sites

## Résultats attendus
- Tunnel VPN IPsec opérationnel
- Communication sécurisée entre les deux sites
- Isolation des réseaux non autorisés

## Fichiers inclus
- `architecture.png` – Schéma VPN Site-to-Site
- `config-FortiGate-SiteA.pdf` – Configuration Site A
- `config-FortiGate-SiteB.pdf` – Configuration Site B
- `Lab FortiGate – Déploiement d’un VPN Site-to-Site IPsec - Partie 3 .pdf` – Documentation complète du lab
