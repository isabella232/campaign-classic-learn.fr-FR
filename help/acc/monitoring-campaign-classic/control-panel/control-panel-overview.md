---
title: Panneau de contrôle
seo-title: Panneau de contrôle
description: Le panneau de contrôle permet de surveiller et de gérer votre espace de stockage SFTP par instance et d’ajouter des adresses IP aux listes autorisées.
seo-description: Le panneau de contrôle permet de surveiller et de gérer votre espace de stockage SFTP par instance et d’ajouter des adresses IP aux listes autorisées.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: ca3b7933927914b9965f6f059293041dd1db1da2
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 77%

---


# [!UICONTROL Panneau de contrôle]

>[!NOTE]
>
>Les termes « [!UICONTROL whiteliste] » et « [!UICONTROL blackliste] » ont été remplacés par les termes « [!UICONTROL liste autorisée] » et « [!UICONTROL liste bloquée » dans la documentation Adobe Campaign.]
>Certaines occurrences de ces termes peuvent toujours apparaître dans l’interface utilisateur du produit, les noms d’option, le code interne, ainsi que dans les tutoriels vidéos. Elles seront remplacées dans les prochaines versions du panneau de contrôle.

Le [!UICONTROL panneau de contrôle] permet aux administrateurs d’Adobe Campaign de surveiller les ressources essentielles et d’effectuer des tâches administratives, telles que la gestion de l’espace de stockage SFTP par instance ou l’[!UICONTROL ajout d’adresses IP aux listes autorisées].

## Accès au [!UICONTROL panneau de contrôle]

Pour accéder au panneau de contrôle, rendez-vous sur la page d’accueil d’Experience Cloud : [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com) :

* **[!UICONTROL Page d’accueil d’Experience Cloud]** > **[!UICONTROL Accès rapide]**

   ou
* **[!UICONTROL Page d’accueil d’Experience Cloud]** > [!UICONTROL Sélecteur de solution] : **Campaign** > carte **[!UICONTROL Panneau de contrôle]**

   ou

* Directement à partir de l’URL : [ https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Prérequis

Avant de commencer, effectuez les tâches prérequises suivantes :

### Confirmer [!DNL IMS Org ID]

Vous devez connaître votre [!DNL IMS org ID]. La vidéo ci-dessous décrit où vous pouvez trouver le [!DNL IMS org ID] de votre instance.

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Vérifier[!DNL IMS Org ID](00:26 min)*

### Droits d’administrateur

Les droits d’administrateur sont requis pour accéder au [!UICONTROL panneau de contrôle].
La vidéo ci-dessous explique comment ajouter un administrateur à une instance Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Comment ajouter un administrateur au profil de produit « [!UICONTROL Administrateurs] » pour pouvoir utiliser le[!UICONTROL panneau de contrôle](01:03 min)*

## [!UICONTROL Didacticiels sur le Panneau de Contrôle]

* **Gestion des serveurs SFTP**

   *Découvrez comment surveiller la capacité du serveur, les adresses IP de[!UICONTROL liste autorisée]et ajouter des clés SSH*

   * [Surveillance de la capacité du serveur, ajout d’adresses IP aux listes autorisées et ajout de clés SSH](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Génération d’une clé SSH](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Connexion à un serveur SFTP](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Délégation de sous-domaines](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *[!UICONTROL Découvrez comment déléguer entièrement un sous-domaine à Adobe Campaign ]*

* **[Ajout de certificats SSL](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Découvrez comment ajouter des certificats SSL pour sécuriser vos sous-domaines à l’aide de Panneau de Contrôle.*

* **[ajouter les autorisations d’URL](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *comment ajouter des URL externes à la liste des URL autorisées, de sorte que votre instance puisse s’y connecter.*

* **[Listes autorisées d’adresses IP pour l’accès aux instances](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Découvrez comment configurer de nouvelles connexions à vos instances en[!UICONTROL autorisant la liste des]plages d’adresses IP.*

* **[Gestion des enregistrements TXT Google](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Découvrez comment ajouter un enregistrement de vérification[!DNL Google TXT]du site à tous les sous-domaines utilisés pour envoyer des courriers électroniques aux[!DNL GMAIL]adresses par le biais du Panneau de ContrôleCampaign.*

* **Gestion des clés GPG**

   *Découvrez comment générer et installer une paire de clés publique/privée sur une instance Campaign spécifiée pour le cryptage des données sortantes. Apprenez aussi comment importer et installer une clé publique sur une instance Campaign pour le décryptage des données entrantes.*

   * [Génération et installation de clés GPG pour le cryptage des données](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Utilisation d’une clé GPG pour crypter des données](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Décrypter des données](./gpg-key-management/decrypting-data.md)

* **[Dépannage du panneau de contrôle](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *[!UICONTROL Comprendre comment résoudre les problèmes liés au panneau de contrôle ]*

## Ressources supplémentaires

* [Centre d’aide du panneau de contrôle](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html)
