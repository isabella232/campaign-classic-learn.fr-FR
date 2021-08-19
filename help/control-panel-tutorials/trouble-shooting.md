---
title: Résolution des problèmes du panneau de contrôle
description: Découvrez comment résoudre les problèmes liés à Panneau de Contrôle.
feature: Panneau de contrôle
kt: 2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
exl-id: 016e8b77-20df-4ca5-b5e7-fe2f3e7ba7a3
source-git-commit: 2f8ae3d47e4debf71311f341d3c02ff3a7f5297a
workflow-type: tm+mt
source-wordcount: '334'
ht-degree: 40%

---

# Résolution des problèmes du [!UICONTROL panneau de contrôle]

## Connexion et page d’accueil

### Symptôme : Impossible de se connecter à l’Experience Cloud

**Que faire :**
 l’utilisateur doit localiser son identifiant de l’organisation IMS (xxx). L’administrateur doit ajouter l’utilisateur au profil de produit &quot;Campaign-xxx-Admins&quot; pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit s’ajouter en tant qu’utilisateur.

### Symptôme : dans la page d’accueil Experience Cloud, les liens permettant d’accéder au [!UICONTROL panneau de contrôle] ne sont pas visibles pour un utilisateur.

**Cause :**
les utilisateurs ne voient pas les liens tant qu’ils ne sont pas ajoutés en tant qu’utilisateurs au profil de produit  _Campaign-xxx-Administrators/Admin_.

**Que faire :**
l’administrateur doit ajouter l’utilisateur au profil de produit  _Campaign-xxx-_  Admins pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit s’ajouter en tant qu’utilisateur.

### Symptôme : une instance n’est pas répertoriée dans le [!UICONTROL panneau de contrôle]

**Cause :**
l’utilisateur le plus probable doit être ajouté en tant qu’ ** utilisateurProduct Profile  _Campaign-xxx-Administrators/_ administrateur pour l’instance manquante.

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
* Pour vous connecter directement au serveur SFTP, vous avez également besoin du logiciel client SFTP.

### Documentation utile {#helpful-docs}

* [Connexion à votre serveur SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
