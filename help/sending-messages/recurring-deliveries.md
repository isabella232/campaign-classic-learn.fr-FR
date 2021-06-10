---
title: Configuration de campagnes email récurrentes et continues
description: Découvrez comment configurer une diffusion récurrente et continue et comprendre les différences entre les deux approches.
feature: Workflows
kt: 1560
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: 5fb898eca821c5078393003c41032801f8454fd5
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 67%

---

# Configuration de campagnes email récurrentes et continues

Ce tutoriel explique comment configurer une diffusion récurrente et continue et les différences entre les deux approches.

## Suivi des diffusions récurrentes et continues {#recurring-and-continuous-delivery-tracking}

Les diffusions récurrentes et continues diffèrent dans la façon dont les données de contact sont gérées :

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

## Ressources supplémentaires

[Créer une diffusion récurrente dans un workflow de ciblage](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/use-cases/deliveries/sending-a-birthday-email.html?lang=en#creating-a-recurring-delivery-in-a-targeting-workflow)
