---
title: Expiration du Creative Cloud pour les entreprises et du numéro de série Acrobat
description: Présentation de l’expérience d’expiration du numéro de série pour Creative Cloud abonnement Entreprise et Acrobat
role: Admin
level: Beginner, Intermediate
feature: Deploy
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: c57212d39b2e613964bc15d2967a1958dc0c8c8e
workflow-type: tm+mt
source-wordcount: '844'
ht-degree: 3%

---

# Expiration du Creative Cloud pour les entreprises et du numéro de série Acrobat

Historiquement, l’Adobe émettait des numéros de série avec nos applications (c’est-à-dire Creative Suite, Creative Cloud pour entreprise, Acrobat XI, Acrobat DC) aux clients sous contrat de licence d’entreprise (ETLA). Ces numéros de série ont une date d’expiration. Une fois la date d’expiration passée, le produit ne fonctionnera plus. Il est donc important de planifier votre migration avant l’expiration de vos numéros de série. Cette page décrit les étapes nécessaires pour garantir à vos utilisateurs finaux un accès continu à leurs applications et services Adobe.

## Vérification de la date d’expiration de vos numéros de série

### Recherche de vos numéros de série

Les licences avec numéro de série associées à votre contrat d’ETLA sont disponibles via le [Site Web d’achat de licences d’Adobe](https://licensing.adobe.com/) (LWS). Suivez ces instructions pour afficher et télécharger :

1. Se connecter à [Site Web d’achat de licences d’Adobe](https://licensing.adobe.com/) (LWS) avec votre Adobe ID et votre mot de passe.
1. Choisir **Licences > Récupérer les numéros de série**.
1. Entrez votre **ID de l’utilisateur final** ou **ID de déploiement**.
1. (Facultatif) Sélectionnez un **Nom du produit**, **Version du produit** ou **Plateforme** pour filtrer les résultats.
1. Cliquez sur Rechercher.
1. Le nom de produit et les numéros de série s’affichent.
1. (Facultatif) Sélectionnez « EXPORTER AU FORMAT CSV » pour télécharger la liste des numéros de série.

![Recherche de vos numéros de série](assets/retrieveserialnumbers.png)

### Vérifier la date d’expiration

Le [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) est un utilitaire de ligne de commande permettant aux administrateurs informatiques de vérifier si les produits Adobes d’un ordinateur utilisent des numéros de série qui ont expiré ou qui expirent. L’outil affiche des informations telles que l’identifiant de licence de produit (LEID), le numéro de série chiffré et la date d’expiration. Ceci [page](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) contient des instructions sur le téléchargement et l’utilisation de l’outil sur les ordinateurs Mac ou Windows.

## Présentation de l’expérience de l’utilisateur final avant et après l’expiration du numéro de série

Les applications Acrobat et Creative Cloud abonnement Entreprise commenceront à afficher des messages (dans les applications) 60 jours avant l’expiration. Une fois le numéro de série expiré, les produits cessent de fonctionner et l’utilisateur est invité à prendre des mesures.

### Creative Cloud abonnement Entreprise

Les informations suivantes décrivent l’expérience de l’utilisateur final. Vous trouverez ci-dessous une courte vidéo, suivie d’une présentation de l’expérience utilisateur.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Avant l’expiration**

À partir de 60 jours avant l’expiration du numéro de série, toutes les applications Creative Cloud abonnement Entreprise affichent une boîte de dialogue dans le produit à l’attention de l’utilisateur final. Ce message s’affichera toutes les semaines jusqu’à 30 jours avant l’expiration, puis tous les jours jusqu’à la date d’expiration indiquant *Votre licence arrive à expiration. Ce produit Adobe utilise une licence qui doit expirer le 29 novembre 2020. Veuillez contacter votre administrateur pour garantir un accès continu*.

![Message CCE before expiration](assets/cceexpiring.png)

**Après expiration**

Une fois le numéro de série expiré, les utilisateurs n’auront plus accès aux applications Creative Cloud abonnement Entreprise. Lors du premier lancement après l’expiration, l’utilisateur est invité à ouvrir une boîte de dialogue indiquant *Le numéro de série saisi a expiré. Ce produit ne peut pas être concédé sous licence. Veuillez contacter le service clientèle*.

![CCE après le message d’expiration](assets/cceafterexpire.png)

Pour toutes les tentatives ultérieures de lancement des applications, l’utilisateur final sera invité à : **Se Connecter Maintenant** suivi de l’option permettant de créer son propre Adobe ID et de passer en mode d’évaluation. Cependant, tout nouvel Adobe ID créé par l’utilisateur final ne sera pas associé aux licences de votre organisation et entraînera une confusion supplémentaire pour vos utilisateurs. Pour éviter toute interruption d’activité et/ou confusion inutile, migrez vos utilisateurs vers des licences nominatives avant l’expiration de votre ou vos numéros de série.

![Boîte de dialogue de connexion à CCE 1](assets/ccesignin1.png)

![Boîte de dialogue de connexion à CCE 2](assets/ccesignin2.png)

### expérience Acrobat

Les informations suivantes décrivent l’expérience de l’utilisateur final. Vous trouverez ci-dessous une courte vidéo, suivie d’une présentation de l’expérience utilisateur.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Avant l’expiration**

60 jours avant l’expiration du numéro de série, Acrobat affiche un message contextuel dans le produit à l’utilisateur final. Elle apparaîtra une fois par semaine jusqu’à 7 jours avant l’expiration. Il apparaîtra alors quotidiennement en indiquant *Votre licence Adobe Acrobat expire le 30/11/2020. Contactez votre administrateur pour continuer à utiliser Acrobat sans interruption.*

![Message d’expiration d’Acrobat](assets/acrobatexpiring.png)

**Après expiration**

Une fois le numéro de série expiré, les utilisateurs n’auront plus accès à Acrobat. Lors du premier lancement après l’expiration, l’utilisateur est invité à ouvrir une boîte de dialogue indiquant *Le numéro de série saisi a expiré. Ce produit ne peut pas être concédé sous licence. Veuillez contacter le service clientèle.*

![Acrobat après le message d’expiration](assets/acrobatafterexpire.png)

Pour toutes les tentatives suivantes de lancement d’Acrobat, l’utilisateur final est invité à : **Se Connecter Maintenant** suivi de l’option permettant de créer son propre Adobe ID et de passer en mode d’évaluation. Cependant, tout nouvel Adobe ID créé par l’utilisateur final ne sera pas associé aux licences de votre organisation et entraînera une confusion supplémentaire pour vos utilisateurs.

![Acrobat Sign dans la boîte de dialogue 1](assets/acrobatsignin1.png)

![Acrobat Sign dans la boîte de dialogue 2](assets/acrobatsignin2.png)

## Contactez-nous si vous avez besoin d’aide

Si vous avez des questions sur l’utilisation de [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) outil ou besoin d’aide pour migrer du déploiement de numéro de série vers un utilisateur nommé, vous disposez de quelques options :
* Envoyer un e-mail à l’équipe d’intégration d’Adobe Enterprise - **entonb@adobe.com**
* Ouvrir un ticket de support dans [Admin Console](https://adminconsole.adobe.com/support)
* Contactez l’équipe chargée de votre compte Adobe
