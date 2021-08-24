---
title: Résolution des problèmes du panneau de contrôle
description: Le Panneau de Contrôle vous permet de surveiller et de gérer votre stockage SFTP par instance et par liste autorisée d’adresses IP.
feature: Panneau de contrôle
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '344'
ht-degree: 44%

---


# Résolution des problèmes du [!UICONTROL panneau de contrôle]

## Connexion et page d’accueil

### Symptôme : Impossible de se connecter à l’Experience Cloud

**Que faire :**
 l’utilisateur doit localiser son identifiant de l’organisation IMS (xxx). L’administrateur doit ajouter l’utilisateur au profil de produit &quot;Campaign-xxx-Admins&quot; pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit s’ajouter en tant qu’utilisateur.

### Symptôme : dans la page d’accueil Experience Cloud, les liens permettant d’accéder au [!UICONTROL panneau de contrôle] ne sont pas visibles pour un utilisateur.

**Cause :**
un utilisateur ne verra pas les liens tant qu’il n’aura pas été ajouté en tant qu’utilisateur au profil de produit _Campaign-xxx-Administrators/Admin_.

**Que faire :**
l’administrateur doit ajouter l’utilisateur au profil de produit  _Campaign-xxx-_  Admins pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit s’ajouter en tant qu’&quot;utilisateurs&quot;.

### Symptôme : une instance n’est pas répertoriée dans le [!UICONTROL panneau de contrôle]

**Cause :**
l’utilisateur doit probablement être ajouté en tant que profil de produit &quot;utilisateur&quot;  _Campaign-xxx-Administrators/_ Adminator pour l’instance manquante.

**Que faire :**
l’administrateur doit ajouter l’utilisateur au profil de produit  _Campaign-xxx-_  Admins pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit s’ajouter en tant qu’&quot;utilisateurs&quot;.

### Vidéos utiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Vérification de l’ID org. IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Comment ajouter un administrateur aux administrateurs de profil de produit pour pouvoir utiliser le [!UICONTROL panneau de configuration] (01:03 min)*

### Documentation utile

* [Découverte du panneau de contrôle](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)
* [[!UICONTROL Gestion des autorisations pour le panneau de contrôle]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Établissement de la connexion au serveur SFTP (client ou API)

La connexion aux serveurs SFTP requiert les actions suivantes :

* [!UICONTROL Ajout à la liste autorisée] de l’adresse IP à partir de laquelle vous vous connectez au serveur SFTP
* Paire de clés privée/publique qui doit être enregistrée auprès d’Adobe Campaign
* Si vous vous connectez directement au serveur SFTP, vous avez besoin du logiciel client SFTP.

### Documentation utile {#helpful-docs}

* [Connexion à votre serveur SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

