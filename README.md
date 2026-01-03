# Détecteur de présence infrarouge – Conception électronique (KiCad)

## 📌 Description
Ce projet consiste en la conception d’un **détecteur de présence infrarouge actif** basé sur une
chaîne de traitement **entièrement analogique**.  
Le système émet un signal infrarouge modulé, détecte la réflexion sur un obstacle (présence humaine),
puis traite le signal afin de produire une **sortie logique exploitable**.

Le projet a été conçu et simulé sous **KiCad** dans un objectif **académique et pédagogique**, avec
une architecture modulaire inspirée des systèmes industriels.

---

## ⚙️ Principe de fonctionnement

1. Une **diode infrarouge émettrice** génère un signal IR modulé.
2. La **diode infrarouge réceptrice** capte le signal réfléchi.
3. Le courant reçu est converti en tension (TIA).
4. Un **filtre passe-bande** rejette le bruit ambiant.
5. Le signal est **amplifié**.
6. Un **détecteur de crête** extrait l’enveloppe.
7. Un **comparateur** compare le signal à un seuil réglable.
8. Une **sortie logique** indique la présence détectée.

---

## 🧩 Architecture du système

- Émetteur infrarouge (LED IR)
- Récepteur infrarouge (photodiode SFH203FA)
- Convertisseur courant/tension
- Filtre passe-bande (≈ 10 kHz)
- Amplificateur non-inverseur
- Détecteur de crête
- Comparateur avec seuil ajustable
- LED d’indication
- Sortie logique vers système externe

## 🧩 System Architecture

![System architecture of the presence detector](Architecture.png)

---

## 🛠️ Outils utilisés

- **KiCad** (schéma & PCB)
- Git & GitHub

---

## 📂 Structure du dépôt

