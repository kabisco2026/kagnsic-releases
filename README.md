# Kagnsic Studio — téléchargements

Kagnsic Studio est un environnement de développement pour cartes à microcontrôleur STM32 : écrire un programme en
C++, le compiler, le flasher, lire le port série et le déboguer pas à pas. Tout est inclus dans l'installateur
(compilateur Arm, débogueur, OpenOCD, SDK) : **rien d'autre à installer**, et l'installation fonctionne hors ligne.

## Télécharger

Dernière version : **[page des versions](https://github.com/kabisco2026/kagnsic-releases/releases)**

| Système | Fichier |
|---|---|
| Windows 10 et 11 (64 bits) — sans droits administrateur | `Kagnsic_Studio-<version>-windows-x64-setup.exe` |
| Linux, Ubuntu 24.04 et plus récents (64 bits) | `Kagnsic_Studio-<version>-x86_64.AppImage` |

Cartes prises en charge : NUCLEO-L476RG, NUCLEO-G431KB, carte minimale STM32F103RC.

Installation et premiers pas : guide intégré à Kagnsic Studio (**Aide > Guide de l'utilisateur**, F1).

## Mises à jour du SDK

Kagnsic Studio (**Fichier > Gestionnaire de SDK**) lit l'index des paquets de ce dépôt :
`https://raw.githubusercontent.com/kabisco2026/kagnsic-releases/main/index.json`.
Pour une salle sans Internet, copiez sur une clé USB l'archive `kagnsic-sdk-AAAA.N.zip` d'une version, puis
installez-la avec « Installer depuis une archive... ».

## Licences

- **Kagnsic Studio** : logiciel propriétaire, gratuit pendant la phase alpha (`LICENCE-UTILISATEUR.md` dans chaque
  version).
- **Framework Kagnsic (SDK)** : Apache 2.0 ; modèles de projet : MIT-0. Vos programmes vous appartiennent.
- **Composants tiers** (Qt, toolchain Arm, OpenOCD, CMake, Ninja, clangd) : leurs propres licences (`THIRD-PARTY.md`).
  Le code source des composants sous GPL et LGPL est publié dans chaque version (fichiers `source-*`,
  liste et empreintes dans `SOURCES-GPL.txt`).

Ce dépôt ne contient que la distribution : index des paquets et versions publiées.
