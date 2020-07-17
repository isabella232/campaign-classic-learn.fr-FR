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
source-git-commit: d1799d978a9a29f69d637178439fe770ffd4b281
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 4%

---


# Comment configurer des campagnes par courriel récurrentes et continues

Ce didacticiel explique comment configurer une diffusion récurrente et continue et les différences entre les deux approches.

## Suivi des Diffusions récurrentes et continues {#recurring-and-continuous-delivery-tracking}

Les diffusions récurrentes et continues diffèrent dans la manière dont les données de contact sont gérées :

* The **continuous delivery** lets you add new recipients to an existing delivery and avoids you having to create a new delivery each time a new recipient is added. Vous pouvez mettre à jour la création directement dans le processus de campagne et le modèle sera mis à jour dans le dossier modèle de diffusion Resource.

   Une diffusion continue crée une diffusion et des logs de diffusion UNIQUES (largeLog) et des logs de tracking qui font référence à l&#39;ajout d&#39;une diffusion chaque fois qu&#39;elle s&#39;exécute.

![Diffusion continue](/help/acc/assets/delivery_continuous.jpg)

* Une diffusion **** récurrente crée une nouvelle instance de diffusion chaque fois qu’elle s’exécute. Par exemple, si le flux de travail est planifié pour s’exécuter une fois par semaine, cela créera 52 Diffusions après une année. Cela signifie également que le grand journal et les logs de tracking seront séparés par chaque instance de diffusion.

![Diffusion récurrente](/help/acc/assets/delivery_recurring.jpg)

## Configuration d’une diffusion récurrente {#how-to-set-up-a-recurring-delivery}

Cette vidéo explique comment configurer une diffusion récurrente et une activité Planificatrice.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Comment configurer une diffusion continue {#how-to-set-up-a-continuous-delivery}

Cette vidéo montre comment configurer une diffusion continue avec une requête incrémentielle.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Autres ressources

[Créer une diffusion récurrente dans un workflow de ciblage](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)