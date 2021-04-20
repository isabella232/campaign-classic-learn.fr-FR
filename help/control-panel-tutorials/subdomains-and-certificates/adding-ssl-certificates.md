---
title: Ajout de certificats SSL
description: Découvrez comment ajouter des certificats SSL pour sécuriser vos sous-domaines.
feature: Control Panel
topics: Control Panel
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Administrator
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/adding-ssl-certificates.html
exl-id: 9ba485fb-be26-4f3c-a9de-844fecaec20d
translation-type: ht
source-git-commit: 298d3745a32d4509a82295be851f6e390f33749a
workflow-type: ht
source-wordcount: '220'
ht-degree: 100%

---

# Ajout de certificats SSL

Le [!UICONTROL panneau de contrôle] d’Adobe Campaign permet d’ajouter des certificats SSL pour sécuriser vos sous-domaines.

## Accès à la gestion des sous-domaines dans le panneau de contrôle

Pour accéder à la gestion des sous-domaines dans le panneau de contrôle, rendez-vous sur :

* [Accueil Experience Cloud](https://experience.adobe.com/#/home) > Sélecteur de solution : **[!DNL Campaign]** > Vignette **[!UICONTROL Panneau de contrôle]** > Vignette **[!UICONTROL Sous-domaines et certificats]**

   ou
* Directement à partir de l’URL : [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Étapes pour ajouter des certificats SSL

Pour ajouter des certificats SSL, trois étapes sont nécessaires :

### 1. Générer les demandes de signature de certificat

La demande de signature de certificat (CSR) est nécessaire pour l’achat d’un certificat SSL. Elle doit être générée pour l’instance et les sous-domaines que vous prévoyez de sécuriser.

La vidéo ci-dessous montre comment générer une demande de signature de certificat dans le panneau de contrôle.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*Générer des demandes de signature de certificat (02:36 min)*

### 2. Acheter le certificat SSL

Après avoir obtenu la demande de signature de certificat, vous devez acheter le certificat SSL auprès d’une autorité de certification approuvée par votre organisation.

### 3. Installer le certificat SSL

Une fois que vous avez obtenu le certificat SSL, il doit être installé pour les sous-domaines que vous envisagez de sécuriser.

La vidéo ci-dessous montre comment installer des certificats SSL dans le [!UICONTROL panneau de contrôle].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*Installer des certificats SSL (01:25 min)*

## Ressources supplémentaires

* [Délégation complète de sous-domaines (vidéo)](./subdomain-delegation.md)
* [Sous-domaines et certificats (documentation)](https://docs.adobe.com/content/help/fr-FR/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)
