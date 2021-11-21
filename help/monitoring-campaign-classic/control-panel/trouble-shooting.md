---
title: Résolution des problèmes du Panneau de contrôle
description: Le Panneau de contrôle permet de surveiller et de gérer votre espace de stockage SFTP par instance et d'ajouter des adresses IP aux listes autorisées.
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '342'
ht-degree: 100%

---


# Résolution des problèmes du [!UICONTROL Panneau de contrôle]

## Connexion et page d&#39;accueil

### Symptôme : impossible de se connecter à Experience Cloud

**Solution :**
L&#39;utilisateur doit rechercher l&#39;ID d&#39;organisation IMS (xxx). L&#39;administrateur doit ajouter l&#39;utilisateur au profil de produit « Campaign-xxx-Admins » pour chaque instance qu&#39;il souhaite gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;utilisateur.

### Symptôme : dans la page d&#39;accueil Experience Cloud, les liens permettant d&#39;accéder au [!UICONTROL Panneau de contrôle] ne sont pas visibles pour un utilisateur.

**Cause :**
un utilisateur ne verra pas les liens tant qu&#39;il n&#39;aura pas été ajouté en tant qu&#39;utilisateur au profil de produit _Campaign-xxx-Administrators/Admin_.

**Solution :**
l&#39;administrateur doit ajouter l&#39;utilisateur au profil de produit _Campaign-xxx-Admins_ pour chaque instance qu&#39;il souhaite gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;utilisateur.

### Symptôme : une instance n&#39;est pas répertoriée dans le [!UICONTROL Panneau de contrôle]

**Cause :**
l&#39;utilisateur doit probablement être ajouté en tant que profil de produit &quot;utilisateur&quot; _Campaign-xxx-Administrators/Admin_ pour l&#39;instance qui est absente.

**Solution :**
l&#39;administrateur doit ajouter l&#39;utilisateur au profil de produit _Campaign-xxx-Admins_ pour chaque instance qu&#39;il souhaite gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;&quot;utilisateur&quot;.

### Vidéos utiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Vérification de l&#39;ID org. IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Comment ajouter un administrateur aux administrateurs de profil de produit pour pouvoir utiliser le [!UICONTROL Panneau de contrôle] (01:03 min)*

### Documentation utile

* [Découverte du Panneau de contrôle](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)
* [[!UICONTROL Gestion des autorisations pour le Panneau de contrôle]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Établissement de la connexion au serveur SFTP (client ou API)

La connexion aux serveurs SFTP requiert les actions suivantes :

* [!UICONTROL Ajout à la liste autorisée] de l&#39;adresse IP à partir de laquelle vous vous connectez au serveur SFTP
* Paire de clés privée/publique devant être enregistrée auprès d&#39;Adobe Campaign
* Si vous vous connectez directement au serveur SFTP, vous aurez également besoin du logiciel client SFTP.

### Documentation utile {#helpful-docs}

* [Connexion à votre serveur SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

