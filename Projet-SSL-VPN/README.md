# Projet 4 – SSL VPN sécurisé FortiGate (Accès distant)

## 🧠 Contexte & Objectif

Ce projet simule un **accès distant sécurisé** pour des utilisateurs nomades
(travailleurs à distance, administrateurs, employés),via un **VPN SSL FortiGate**.

L’objectif est de démontrer la mise en place d’un **SSL VPN sécurisé**,
avec authentification des utilisateurs, attribution d’adresses IP et contrôle strict des accès réseau.

## 🧪 Scénario

Des utilisateurs distants se connectent à l’infrastructure interne de l’entreprise à travers **FortiClient** en utilisant un tunnel **SSL VPN**.
Les accès sont limités selon des règles de sécurité précises,afin de garantir la confidentialité et l’intégrité des ressources internes.

## 🛠️ Technologies & concepts
- FortiGate (VM / GNS3)
- SSL VPN
- FortiClient
- Portail SSL VPN
- Authentification utilisateurs
- Firewall Policies
- Routage & contrôle des accès

## 🧩 Architecture

<img width="872" height="477" alt="Architecture" src="https://github.com/user-attachments/assets/d98a9830-1efa-4778-b65b-0c1ecc0dc167" />

## ⚙️ Étapes clés 

1. Activation et configuration du SSL VPN
2. Création des utilisateurs / groupes
3. Configuration du portail SSL VPN
4. Création des firewall policies
5. Configuration du client FortiClient
6. Tests de connexion et d’accès aux ressources

## ✅ Résultats & validation

- Connexion SSL VPN fonctionnelle via FortiClient
- Attribution d’adresses IP aux utilisateurs distants
- Accès sécurisé aux ressources internes
- Contrôle des flux réseau appliqué avec succès
- Journalisation et visibilité des connexions VPN

## 🎯 Compétences démontrées

- Déploiement d’un accès distant sécurisé avec SSL VPN
- Configuration avancée du SSL VPN FortiGate
- Gestion des utilisateurs et des accès
- Mise en place de policies firewall pour VPN
- Sécurisation des accès distants en environnement entreprise

## 📂 Contenu du dossier

- `config-FortiGate-SSL-VPN.pdf` – Configuration du FortiGate
- `Lab FortiGate – Déploiement d’un VPN SSL - Partie 4.pdf` – Documentation complète du Projet
  
<img width="878" height="702" alt="30" src="https://github.com/user-attachments/assets/82f1a31c-e7e9-403f-8fcf-b78b499eaa6b" />

<img width="871" height="659" alt="31" src="https://github.com/user-attachments/assets/a966363a-44cb-406a-8e18-d83a7623ce20" />

<img width="880" height="702" alt="32" src="https://github.com/user-attachments/assets/cd1be221-4abe-477e-8b70-5ec7dfd3f521" />

📄 *Si le PDF ne s’affiche pas directement sur GitHub, veuillez le télécharger pour le consulter.*
