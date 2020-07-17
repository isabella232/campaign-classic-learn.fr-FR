---
title: Panneau de contrôle
seo-title: Panneau de contrôle
description: Le Panneau de Contrôle vous permet de surveiller et de gérer votre enregistrement SFTP par instance et par liste autorisée d’adresses IP.
seo-description: Le Panneau de Contrôle vous permet de surveiller et de gérer votre enregistrement SFTP par instance et par liste autorisée d’adresses IP.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '485'
ht-degree: 7%

---


# [!UICONTROL Panneau de contrôle]

>[!NOTE]
>
>Les termes &quot;[!UICONTROL liste blanche]&quot; et &quot;listenoire&quot; ont été remplacés par les termes &quot;[!UICONTROL liste autorisée]&quot; et &quot;[!UICONTROL liste bloquée&quot; dans la documentation Adobe Campaign.]
>Certaines occurrences de ces termes peuvent toujours exister dans l’interface utilisateur du produit, les noms d’option, le code interne, ainsi que dans les vidéos du didacticiel. Ils seront remplacés dans les prochaines versions du Panneau de Contrôle.

Le [!UICONTROL Panneau de Contrôle] permet aux administrateurs d’Adobe Campaign de surveiller les ressources clés et d’effectuer des tâches administratives, telles que la gestion de l’enregistrement SFTP par instance ou les adresses IP de [!UICONTROL liste autorisée] .

## Accessing [!UICONTROL Control Panel]

Pour accéder au Panneau de Contrôle, accédez à Accueil Experience Cloud : [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Accueil]** Experience Cloud > Accès **[!UICONTROL rapide]**

   ou
* **[!UICONTROL Accueil]** de l&#39;Experience Cloud > Sélecteur [!UICONTROL de]solution : **Campaign** > Carte **[!UICONTROL Panneau de Contrôle]**

   ou

* Directement à partir de l’URL : [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Prérequis

Avant de commencer, remplissez les conditions préalables suivantes :

### Confirmer [!DNL IMS Org ID]

Tu as besoin de connaître ton [!DNL IMS org ID]. La vidéo suivante décrit où vous pouvez rechercher votre instance [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Vérification[!DNL IMS Org ID](00:26 min)*

### Droits d’administrateur

Les droits d’administrateur sont requis pour accéder au [!UICONTROL Panneau de Contrôle].
La vidéo suivante explique comment ajouter un administrateur à une instance Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Comment ajouter un administrateur au profil produit &quot;[!UICONTROL Administrateurs]&quot; pour pouvoir utiliser le[!UICONTROL Panneau de Contrôle](01:03 min)*

## [!UICONTROL Didacticiels sur le Panneau de Contrôle]

* **Gestion des serveurs SFTP**

   *Découvrez comment surveiller la capacité du serveur, les adresses IP de[!UICONTROL liste autorisée]et ajouter des clés SSH*

   * [Surveillance de la capacité du serveur, autorisation de la liste des adresses IP et ajout de clés SSH](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Génération d’une clé SSH](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Connexion à un serveur SFTP](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Délégation de sous-domaines](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Découvrez comment déléguer complètement un sous-domaine à un[!UICONTROL Adobe Campaign ]*

* **[Ajouter des certificats SSL](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Découvrez comment ajouter des certificats SSL pour sécuriser vos sous-domaines à l’aide de Panneau de Contrôle.*

* **[Gestion des certificats SSL](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *Découvrez comment vous pouvez vue l’état des certificats SSL de vos sous-domaines, ainsi que demander des renouvellements.*

* **[Ajouter les autorisations d’URL](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *comment ajouter des URL externes à la liste des URL autorisées, de sorte que votre instance puisse s’y connecter.*

* **[Listes autorisées d’adresses IP pour l’accès aux instances](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Découvrez comment configurer de nouvelles connexions à vos instances en[!UICONTROL autorisant la liste des]plages d’adresses IP.*

* **[Gestion des enregistrements TXT Google](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Découvrez comment ajouter un enregistrement de vérification[!DNL Google TXT]du site à tous les sous-domaines utilisés pour envoyer des courriers électroniques aux[!DNL GMAIL]adresses par le biais du Panneau de ContrôleCampaign.*

* **Gestion des clés GPG**

   *Découvrez comment générer et installer une paire de clés publique/privée sur une instance Campaign spécifique pour le chiffrement des données sortantes, ainsi que importer et installer une clé publique sur une instance Campaign pour le déchiffrement des données entrantes :*

   * [Génération et installation de clés GPG pour le chiffrement des données](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Utilisation d’une clé GPG pour chiffrer des données](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Décrypter des données](./gpg-key-management/decrypting-data.md)

* **[Dépannage du panneau de contrôle](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Comprendre comment résoudre le[!UICONTROL Panneau de Contrôle ]*

## Autres ressources

* [Centre d&#39;aide Panneau de Contrôle](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html)
