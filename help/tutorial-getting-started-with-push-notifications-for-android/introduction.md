---
title: Didacticiel Prise en main des notifications Push pour Android - Introduction
description: Ce tutoriel vous guide tout au long des étapes nécessaires à l’envoi de notifications push depuis Adobe Campaign et à la réception de ces notifications dans votre application Android.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 412fe93f45be1e98343b4e63cbd7dd9285444e46
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# Didacticiel Prise en main des notifications Push pour Android - Introduction

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

Ce didacticiel décrit les étapes à suivre pour envoyer des [!DNL push] notifications d&#39;Adobe Campaign à une [!DNL Android] application.

## Conditions préalables requises

Avant de commencer, vous devez respecter les conditions préalables suivantes :

1) Application mobileCe didacticiel ne décrit pas les étapes détaillées requises pour configurer l&#39;application mobile. Vous devez disposer d&#39;une application **[!DNL Android]mobile avec l&#39;[!DNL Campaign SDK]** intégration.

   * Vous trouverez une description détaillée des étapes requises dans l’ [intégration du SDK Campaign dans l’application](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)mobile.

   * Vous pouvez également utiliser le SDK mobile Experience Platform. Pour plus d’informations, visionnez la vidéo du didacticiel [Configurer le Canal Push à l’aide du kit SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) mobile Experience Platform.

2) Package de Canal d’applications mobiles installé

   Vous devez avoir installé le module de canal d&#39;application mobile sur votre instance. La vidéo suivante explique comment vérifier si le canal d’applications mobiles est installé sur votre instance et, dans le cas contraire, comment l’installer.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Tutoriel

Nous souhaitons envoyer une notification Push personnalisée aux abonnés de l&#39;application mobile Neotrip [!DNL Android] . L’application Neotrip est configurée avec le Campaign SDK et nous nous sommes assurés que le canal d’applications mobiles est activé sur notre instance Campaign.

Les étapes de configuration suivantes sont requises :

### Étape 1 : Étendre le schéma d’abonnement de l’application pour personnaliser les notifications Push

Comme nous souhaitons personnaliser la notification Push, nous allons d’abord [étendre le schéma](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) d’abonnement de l’application afin de pouvoir stocker les valeurs de personnalisation que nous recevons de l’application lorsque l’utilisateur s’abonne au service.

### Étape 2 : Configuration du service Android et création de l’application d’application mobile dans Campaign

Ensuite, nous devrons [configurer le service Android et créer l&#39;application d&#39;application mobile dans Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). Au cours de cette étape, nous définirons l’application Neotrip comme la cible de la notification Push.

### Étape 3 : Configuration et envoi de la notification Push

Ensuite, nous sommes prêts à [configurer et envoyer la notification](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)Push.

## Début du didacticiel

**[Étape 1 : Étendre le schéma d’abonnement de l’application](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
