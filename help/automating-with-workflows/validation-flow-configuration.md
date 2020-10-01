---
title: Configuration des workflows de validation dans Adobe Campaign Classic
seo-title: Configuration des workflows de validation dans Adobe Campaign Classic
description: adobe campaign offre plusieurs options permettant aux spécialistes du marketing de consulter et de fournir le contenu des diffusions, la cible des campagnes, l’extraction des données et les approbations de budget. Ce didacticiel explique comment configurer différents workflows de validation d’approbation.
seo-description: Cette vidéo explique comment configurer et utiliser un modèle de diffusion dans ACCAdobe Campaign offre plusieurs options pour que les spécialistes du marketing puissent examiner et fournir le contenu des diffusions, la cible des campagnes, l’extraction des données et les approbations de budget. Ce didacticiel explique comment configurer différents workflows de validation d’approbation.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Configuration des workflows de validation dans Adobe Campaign Classic

adobe campaign offre plusieurs options permettant aux spécialistes du marketing de consulter et de fournir le contenu des diffusions, la cible des campagnes, l’extraction des données et les approbations de budget.

Ce didacticiel explique comment configurer différents workflows de validation d’approbation.

## Prérequis  {#prerequisite}

Avant d’activer les étapes d’approbation, l’équipe marketing doit définir des réviseurs individuels :

* Le rôle de réviseur Adobe Campaign dans une activité d’approbation peut être un réviseur unique (opérateur) ou un groupe de réviseurs (rôle d’opérateur).
* Les réviseurs et les groupes de réviseurs doivent être configurés précédemment dans Adobe Campaign par un rôle Administrateur. Cela permet aux développeurs de campagne de sélectionner les réviseurs en tant qu’approbateurs dans une campagne ou une diffusion.

## Configuration des approbations pour les campagnes  {#configuring-approvals-for-campaigns}

Si vous disposez du même jeu de réviseurs pour toutes les diffusions de votre processus de campagne, vous utiliserez les fonctionnalités d’ [!DNL Campaign] approbation. En configurant les approbations et les réviseurs au niveau de la campagne, les tâches d’approbation et les réviseurs seront repoussés à chaque activité de diffusion de votre processus une fois le processus exécuté.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configuration des approbations pour les diffusions  {#configuring-approvals-for-deliveries}

Vous pouvez également configurer des approbations au niveau de la diffusion. Si les étapes d’approbation des diffusions et les réviseurs diffèrent des étapes d’approbation des campagnes et des réviseurs, les paramètres de la diffusion remplaceront les paramètres de la campagne.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configuration d’une activité d’approbation  {#configuring-an-approval-activity}

Contrairement aux approbations de diffusion ou de campagne, l’activité d’approbation permet de créer un processus d’approbation au sein d’un processus. Ainsi, la logique de sélection du ciblage peut être approuvée avant le lancement de la diffusion. Il permet également l’approbation à plusieurs niveaux dans le processus, si nécessaire.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

For more information, refer to the [Approval Documentation](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)