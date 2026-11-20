---
title: "Pellicule — Politique de confidentialité"
lang: fr
permalink: /confidentialite/
---

# Politique de confidentialité de Pellicule

*Dernière mise à jour : 20 novembre 2026*

Pellicule est un lecteur vidéo pour iPhone, iPad, Apple TV et Mac. Il lit les vidéos de **vos propres serveurs** : un serveur Jellyfin, des partages réseau (SMB) et les fichiers de votre appareil.

## En résumé

**Pellicule ne collecte aucune donnée.** L'éditeur de l'app ne reçoit rien : ni compte, ni statistiques d'usage, ni identifiant publicitaire, ni rapport de plantage. L'app ne contient aucun outil de mesure d'audience, aucune publicité et aucun service tiers de suivi.

Toutes les données restent entre l'app, votre appareil, les serveurs que vous choisissez d'y ajouter et, si vous activez la synchronisation de Pellicule+, votre propre compte iCloud.

## Ce que Pellicule échange avec vos serveurs

- **Serveur Jellyfin.** Pellicule s'y connecte avec l'adresse, le nom d'utilisateur et le mot de passe que vous saisissez. Il y lit vos bibliothèques et y enregistre ce que fait habituellement un lecteur Jellyfin : la progression de lecture, les vidéos vues et les favoris. Ces informations sont stockées sur votre serveur, sous votre contrôle.
- **Partages réseau (SMB).** Pellicule s'y connecte avec les identifiants que vous saisissez, uniquement pour lister et lire vos fichiers.
- **Sous-titres en ligne.** La recherche de sous-titres passe par votre serveur Jellyfin, qui interroge les fournisseurs que vous y avez configurés (OpenSubtitles, par exemple). Pellicule ne contacte pas ces fournisseurs directement.
- **Bandes-annonces en ligne.** Quand vous touchez « Bande-annonce » et que le film n'en a pas sur votre serveur, Pellicule ouvre le lien fourni par vos métadonnées (YouTube, en général) dans le navigateur ou l'app correspondante. C'est la politique de confidentialité de ce site qui s'applique alors.

## Ce que Pellicule garde sur votre appareil

- **Identifiants.** Les jetons de connexion Jellyfin et les mots de passe des partages SMB sont dans le trousseau d'Apple (Keychain), chiffré par le système.
- **Réglages et comptes enregistrés.** Ils sont dans les préférences de l'app.
- **Téléchargements.** Les vidéos téléchargées pour une lecture hors ligne restent dans le stockage de l'app. Elles sont supprimées avec l'app ou depuis l'onglet Téléchargements.
- **Intégration au système.**
  - La recherche Spotlight, les raccourcis Siri et le widget « Reprendre » utilisent les titres et les vignettes de vos vidéos récentes.
  - Sur Apple TV, l'étagère du haut fait de même.
  - Ces informations sont préparées et stockées sur l'appareil uniquement.

## Pellicule+ : achats et synchronisation iCloud

- **Achats.** L'abonnement et l'achat à vie Pellicule+ sont traités par Apple (App Store). L'éditeur ne reçoit ni votre nom, ni votre adresse e-mail, ni vos coordonnées de paiement. L'app vérifie seulement auprès de l'App Store, sur l'appareil, qu'un achat est valide.
- **Synchronisation iCloud (facultative).** Avec Pellicule+, et tant que l'option est activée dans les Réglages, Pellicule synchronise entre vos appareils :
  - vos comptes Jellyfin (adresse du serveur, nom d'utilisateur et jeton de connexion, **sans mot de passe** ; le jeton permet à un nouvel appareil de se connecter sans rien saisir) ;
  - vos partages réseau (nom, adresse, utilisateur et mot de passe) ;
  - vos réglages de lecture ;
  - la position de lecture et l'état « vu » des fichiers des partages réseau et de l'appareil.
- **Où vont ces données.** Dans le stockage clé-valeur iCloud de l'app, propre à votre compte iCloud et chiffré par Apple. Seuls vous et vos appareils y ont accès : l'éditeur ne peut ni les lire ni les recevoir. La politique de confidentialité d'Apple s'applique à iCloud.
- **Effacer.** Réglages › Pellicule+ › « Effacer les données iCloud » retire tout ce que Pellicule a rangé dans iCloud. Vous pouvez aussi le faire dans les réglages iCloud de votre appareil.
- **Réseau local.** Pour savoir si votre serveur Jellyfin est sur votre réseau local (l'accès à distance fait partie de Pellicule+), l'app regarde sur l'appareil l'adresse jointe et le type de connexion. Rien n'est envoyé.

## Réseau local

Pellicule demande l'accès au réseau local pour joindre votre serveur Jellyfin et vos partages SMB à la maison. Cet accès sert uniquement à ces connexions.

## Enfants

Pellicule ne s'adresse pas spécifiquement aux enfants et ne collecte aucune donnée, quel que soit l'âge de l'utilisateur.

## Vos droits

Comme l'éditeur ne détient aucune donnée vous concernant, il n'y a rien à consulter, à corriger ou à supprimer de son côté. Les données de lecture sont sur votre serveur Jellyfin, où vous pouvez les gérer, et celles de la synchronisation dans votre compte iCloud. Pour effacer tout ce que Pellicule garde sur un appareil, déconnectez vos comptes ou supprimez l'app.

## Contact

Pour toute question sur cette politique : [florian.simon@skolln.com](mailto:florian.simon@skolln.com).

Si cette politique change, la nouvelle version sera publiée à la même adresse, avec sa date de mise à jour.
