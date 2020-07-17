---
title: Panneau de Contrôle de tir problématique
description: Le Panneau de Contrôle vous permet de surveiller et de gérer votre enregistrement SFTP par instance et par liste autorisée d’adresses IP.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '351'
ht-degree: 3%

---


# [!UICONTROL Panneau de Contrôle de prise de vue problématique]

## Connexion et page d&#39;accueil

### Symptôme : Impossible de se connecter à l&#39;Experience Cloud

**Que faire :**
L’utilisateur doit localiser son ID d’organisation IMS (xxx). L’administrateur doit ajouter l’utilisateur au Profil de produits &quot;Campaign-xxx-Admins&quot; pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il peut encore être nécessaire de s’ajouter en tant qu’utilisateurs.

### Symptôme : Les liens de la page d’accueil de l’Experience Cloud vers le [!UICONTROL Panneau de Contrôle] d’accès n’apparaissent pas pour un utilisateur.

**Cause :**
Les utilisateurs ne verront pas les liens tant qu’ils ne seront pas ajoutés en tant qu’utilisateurs au Profil de produits Campaign-xxx-Administrators/Admin __.

**Que faire :**
L’administrateur doit ajouter l’utilisateur au Profil de produits _Campaign-xxx-Admins_ pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il peut encore être nécessaire de s’ajouter en tant qu’&quot;utilisateurs&quot;.

### Symptôme : Une instance n’est pas répertoriée dans le [!UICONTROL Panneau de Contrôle]

**Cause :**
L’utilisateur doit probablement être ajouté en tant qu’Profil de produit &quot;utilisateur&quot; _Campaign-xxx-Administrators/Admin_ pour l’instance manquante.

**Que faire :**
L’administrateur doit ajouter l’utilisateur au Profil de produits _Campaign-xxx-Admins_ pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il peut encore être nécessaire de s’ajouter en tant qu’&quot;utilisateurs&quot;.

### Vidéos utiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Vérifiez l&#39;ID d&#39;organisation IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Comment ajouter un administrateur aux administrateurs de profil de produits pour pouvoir utiliser le panneaude configuration (01:03 min)*

### Documentation utile

* [Découvrir le Panneau de Contrôle](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [[!UICONTROL Gestion des autorisations pour le panneau de contrôle]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## Établissement de la connexion au serveur SFTP (client ou API)

La connexion aux serveurs SFTP requiert :

* [!UICONTROL Autoriser la liste] de l’adresse IP à partir de laquelle vous vous connectez au serveur SFTP
* Paire de clés privée/publique qui doit être enregistrée avec l&#39;Adobe Campaign
* Si vous vous connectez directement au serveur SFTP, vous aurez également besoin du logiciel client SFTP.

### Documentation utile

* [Connexion à votre serveur SFTP](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

