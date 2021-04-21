---
title: Prise en main des notifications push pour Android - Introduction
description: Ce tutoriel vous guide tout au long des étapes nécessaires à l’envoi de notifications push depuis Adobe Campaign et à la réception de ces notifications dans votre application Android.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
translation-type: tm+mt
source-git-commit: 137d1e0c36d038f3fb8a4742bafef6fbac96f41d
workflow-type: tm+mt
source-wordcount: '366'
ht-degree: 100%

---

# Prise en main des notifications push pour Android - Introduction

Adobe Campaign vous permet d’envoyer des notifications personnalisées et segmentés [!DNL push] aux appareils mobiles [!DNL iOS] et [!DNL Android]. Ce tutoriel montre les étapes à suivre pour envoyer des notifications [!DNL push] d’Adobe Campaign à une application [!DNL Android].

## Conditions préalables requises

Avant de commencer, vous devez disposer des éléments suivants :

1) **Application mobile Android**

   Ce tutoriel ne décrit pas les étapes détaillées requises pour configurer l’application mobile. Vous devez disposer d’une application mobile **[!DNL Android]avec [!DNL Campaign SDK] intégré**.

   Vous trouverez une description détaillée des étapes requises dans la documentation du produit :

   [Intégrer le SDK Campaign dans l’application mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=fr)

   Vous pouvez également utiliser le SDK Mobile Experience Platform. Pour en savoir plus, visionnez le tutoriel vidéo suivant :

   [Configuration du canal Push à l’aide du SDK Mobile Experience Platform](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=fr)

2) Package **[!DNL Mobile App channel]installé**

   Le package [!DNL Mobile App channel] doit être installé sur votre instance [!DNL Campaign]. La vidéo suivante explique comment vérifier si [!DNL Mobile App channel] est installé sur votre instance et, dans le cas contraire, comment l’installer.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Présentation du tutoriel

Nous souhaitons envoyer une notification promotionnelle personnalisée [!DNL push] aux abonnés de l’application mobile [!DNL Neotrip] [!DNL Android]. L’application [!DNL Neotrip] est configurée avec [!DNL Campaign SDK] et nous nous sommes assurés que [!DNL Mobile App channel] est activé sur notre instance [!DNL Campaign].

Les étapes de configuration suivantes sont requises :

### Étape 1 : étendre le schéma d’abonnement de l’application pour personnaliser les notifications [!DNL push] notifications.

Comme nous souhaitons personnaliser la notification [!DNL push], nous allons tout d’abord [étendre le schéma d’abonnement de l’application](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) pour pouvoir stocker les valeurs de personnalisation que nous recevons de l’application lorsque l’utilisateur s’abonne au service.

### Étape 2 : configurer le service Android et créer l’application mobile dans Campaign

Ensuite, nous devrons [configurer le service Android et créer l’application mobile dans Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). Au cours de cette étape, nous définirons l’application [!DNL Neotrip] comme cible de la notification push.

### Étape 3 : configurer et envoyer la notification push

Ensuite, nous sommes prêts à [configurer et envoyer la notification push](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Commencer le tutoriel

Étape 1 : [étendre le schéma d’abonnement de l’application](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
