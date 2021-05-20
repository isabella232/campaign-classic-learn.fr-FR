---
title: Résolution des problèmes du panneau de contrôle
description: Le panneau de contrôle permet de surveiller et de gérer votre capacité de stockage SFTP par instance et d’ajouter des adresses IP aux listes autorisées.
feature: Panneau de contrôle
kt: 2938
doc-type: article
activity: use
team: PM
role: Administrator
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
exl-id: 016e8b77-20df-4ca5-b5e7-fe2f3e7ba7a3
source-git-commit: 137d1e0c36d038f3fb8a4742bafef6fbac96f41d
workflow-type: ht
source-wordcount: '353'
ht-degree: 100%

---

# Résolution des problèmes du [!UICONTROL panneau de contrôle]

## Connexion et page d’accueil

### Symptôme : impossible de se connecter à Experience Cloud

**Solution :**
L’utilisateur doit rechercher l’ID org. IMS (xxx). L’administrateur doit ajouter l’utilisateur au profil de produit « Campaign-xxx-Admins » pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit peut-être encore s’ajouter en tant qu’utilisateur.

### Symptôme : dans la page d’accueil Experience Cloud, les liens permettant d’accéder au [!UICONTROL panneau de contrôle] ne sont pas visibles pour un utilisateur.

**Cause :**
un utilisateur ne verra pas les liens tant qu’il n’aura pas été ajouté en tant qu’utilisateur au profil de produit _Campaign-xxx-Administrators/Admin_.

**Solution :**
l’administrateur doit ajouter l’utilisateur au profil de produit _Campaign-xxx-Admins_ pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit peut-être encore s’ajouter en tant qu’utilisateur.

### Symptôme : une instance n’est pas répertoriée dans le [!UICONTROL panneau de contrôle]

**Cause :**
l’utilisateur doit probablement être ajouté en tant que profil de produit « utilisateur » _Campaign-xxx-Administrators/Admin_ pour l’instance qui est absente.

**Solution :**
l’administrateur doit ajouter l’utilisateur au profil de produit _Campaign-xxx-Admins_ pour chaque instance qu’il souhaite gérer. Si l’utilisateur est un administrateur de toutes les instances, il doit peut-être encore s’ajouter en tant qu’« utilisateur ».

### Vidéos utiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Vérification de l’ID org. IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Comment ajouter un administrateur aux administrateurs de profil de produit pour pouvoir utiliser le [!UICONTROL panneau de configuration] (01:03 min)*

### Documentation utile

* [Découverte du panneau de contrôle](https://helpx.adobe.com/fr/campaign/kb/control-panel-overview.html)
* [[!UICONTROL Gestion des autorisations pour le panneau de contrôle]](https://helpx.adobe.com/fr/campaign/kb/control-panel-access.html)

## Établissement de la connexion au serveur SFTP (client ou API)

La connexion aux serveurs SFTP requiert les actions suivantes :

* [!UICONTROL Ajout à la liste autorisée] de l’adresse IP à partir de laquelle vous vous connectez au serveur SFTP
* Enregistrement d’une paire de clés privée/publique auprès d’Adobe Campaign
* Si vous vous connectez directement au serveur SFTP, vous aurez également besoin d’un logiciel client SFTP.

### Documentation utile  {#helpful-docs}

* [Connexion à votre serveur SFTP](https://helpx.adobe.com/fr/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)
