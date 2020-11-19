---
title: Prise en main des notifications Push pour Android - Introduction
description: Ce tutoriel vous guide tout au long des étapes nécessaires à l’envoi de notifications push depuis Adobe Campaign et à la réception de ces notifications dans votre application Android.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 016f47e131df9c3a25b9131da372efaedf6cd5ad
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 8%

---


# Prise en main des notifications Push pour Android - Introduction

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. Ce didacticiel décrit les étapes à suivre pour envoyer des [!DNL push] notifications d&#39;Adobe Campaign à une [!DNL Android] application.

## Conditions préalables requises

Avant de commencer, vous devez disposer des éléments suivants :

1) **Application Android Mobile**

   Ce didacticiel ne décrit pas les étapes détaillées requises pour configurer l’application mobile. Vous devez disposer d&#39;une application **[!DNL Android]mobile avec l&#39; [!DNL Campaign SDK] intégration**.

   Vous trouverez une description détaillée des étapes requises dans la documentation du produit :

   [Intégrer le SDK Campaign dans l’application mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   Vous pouvez également utiliser le SDK mobile Experience Platform. Pour plus d’informations, visionnez la vidéo du didacticiel :

   [Configuration du Canal Push à l’aide du SDK mobile Experience Platform](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]package installé**

   Le [!DNL Mobile App channel] package doit être installé sur votre [!DNL Campaign] instance. La vidéo suivante explique comment vérifier si l’instance [!DNL Mobile App channel] est installée sur votre instance et, dans le cas contraire, comment l’installer.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Présentation du didacticiel

Nous souhaitons envoyer une [!DNL push] notification promotionnelle personnalisée aux abonnés de l&#39;application [!DNL Neotrip][!DNL Android] mobile. L&#39; [!DNL Neotrip] application est configurée avec le [!DNL Campaign SDK] et nous nous sommes assurés que le [!DNL Mobile App channel] est activé sur notre [!DNL Campaign] instance.

Les étapes de configuration suivantes sont requises :

### Étape 1 : Étendre le schéma d’abonnement de l’application pour personnaliser les [!DNL push] notifications

Comme nous souhaitons personnaliser la [!DNL push] notification, nous allons tout d’abord [étendre le schéma](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) d’abonnement de l’application afin de pouvoir stocker les valeurs de personnalisation que nous recevons de l’application lorsque l’utilisateur s’abonne au service.

### Étape 2 : Configuration du service Android et création de l’application mobile dans Campaign

Ensuite, nous devrons [configurer le service Android et créer l&#39;application mobile dans Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). Au cours de cette étape, nous définirons l’ [!DNL Neotrip] application comme la cible de la notification Push.

### Étape 3 : Configuration et envoi de la notification Push

Ensuite, nous sommes prêts à [configurer et envoyer la notification](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)Push.

## Début du didacticiel

Étape 1 : [Étendre le schéma d’abonnement de l’application](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
