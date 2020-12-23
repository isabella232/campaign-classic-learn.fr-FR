---
title: Comment configurer des campagnes par courriel récurrentes et continues
description: Ce didacticiel explique comment configurer une diffusion récurrente et continue et les différences entre les deux approches dans Adobe Campaign Classic (ACC).
feature: workflows
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: 262807b2185cf98a154479e97540c561f273ca18
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 66%

---


# Comment configurer des campagnes par courriel récurrentes et continues

Ce didacticiel explique comment configurer une diffusion récurrente et continue et les différences entre les deux approches.

## Suivi des Diffusions récurrentes et continues {#recurring-and-continuous-delivery-tracking}

Les diffusions récurrentes et continues diffèrent dans la manière dont les données de contact sont gérées :

* Une **diffusion (au fil de l’eau)** permet d&#39;ajouter de nouveaux destinataires à une diffusion existante, ce qui évite d&#39;avoir à créer une diffusion chaque fois qu’un nouveau destinataire est ajouté. Vous pouvez mettre à jour le contenu créatif directement dans le workflow de campagne et le modèle sera mis à jour dans le dossier Ressource du modèle de diffusion.

   Une diffusion (au fil de l’eau) crée une diffusion et des logs de diffusion UNIQUES (broadLog) et des logs de tracking qui font référence à l&#39;ajout d&#39;une diffusion chaque fois qu&#39;elle s&#39;exécute.

![Diffusion (au fil de l’eau)](/help/assets/delivery_continuous.jpg)

* Une **diffusion récurrente** crée une nouvelle instance de diffusion chaque fois qu’elle s’exécute. Par exemple, si le workflow est planifié pour s’exécuter une fois par semaine, 52 diffusions seront créées en une année. Cela signifie également que le broadlog et les logs de tracking seront séparés par chaque instance de diffusion.

![Diffusion récurrente](/help/assets/delivery_recurring.jpg)

## Configuration d’une diffusion récurrente {#how-to-set-up-a-recurring-delivery}

Cette vidéo explique comment configurer une diffusion récurrente et une activité Planificateur.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Comment configurer une diffusion (au fil de l’eau){#how-to-set-up-a-continuous-delivery}

Cette vidéo montre comment configurer une diffusion (au fil de l’eau) avec une requête incrémentale.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Autres ressources

[Créer une diffusion récurrente dans un workflow de ciblage](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)