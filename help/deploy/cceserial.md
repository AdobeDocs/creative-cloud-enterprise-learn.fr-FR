---
title: Présentation du Creative Cloud pour les entreprises et de l’expiration des numéros de série Acrobat
description: Présentation de l’expérience d’expiration des numéros de série pour Creative Cloud pour entreprise et Acrobat
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# Présentation du Creative Cloud pour les entreprises et de l’expiration des numéros de série Acrobat

Historiquement, l’Adobe a émis des numéros de série avec nos applications (Creative Suite, Creative Cloud pour entreprise, Acrobat XI, Acrobat DC) aux clients sur des contrats de licence d’entreprise (ETLA). Ces numéros de série ont une date d’expiration. Une fois la date d’expiration passée, le produit ne fonctionnera plus. Il est donc important de planifier votre migration avant l’expiration de vos numéros de série. Cette page décrit les étapes nécessaires pour garantir à vos utilisateurs finaux un accès continu à leurs applications et services d’Adobe.

## Vérification de la date d’expiration de vos numéros de série

### Recherche de votre ou vos numéros de série

Les licences par numéro de série associées à votre contrat d’ETLA sont disponibles via le [site Web d’achat de licences d’Adobe](https://licensing.adobe.com/) (LWS). Suivez les instructions suivantes pour afficher et télécharger :

1. Connectez-vous au [site web d’achat de licences d’Adobe](https://licensing.adobe.com/) (LWS) avec votre Adobe ID et votre mot de passe.
1. Sélectionnez **Licences > Récupérer les numéros de série**.
1. Entrez votre **ID d&#39;utilisateur final** ou **ID de déploiement**.
1. (Facultatif) Sélectionnez un **nom de produit**, **version de produit** ou **plate-forme** pour filtrer les résultats.
1. Cliquez sur Rechercher.
1. Le nom de produit et les numéros de série s’affichent.
1. (Facultatif) Sélectionnez &quot;EXPORTER AU FORMAT CSV&quot; pour télécharger la liste des numéros de série.

![Recherche des numéros de série](assets/retrieveserialnumbers.png)

### Vérification de la date d’expiration

[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) est un utilitaire de ligne de commande permettant aux administrateurs informatiques de vérifier si les produits d’Adobe sur un ordinateur utilisent des numéros de série qui ont expiré ou qui arrivent à expiration. L’outil affiche des informations telles que l’identifiant de licence du produit (LEID), le numéro de série chiffré et la date d’expiration. Cette [page](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) contient des instructions sur le téléchargement et l&#39;utilisation de l&#39;outil sur les ordinateurs Mac ou Windows.

## Comprendre l’expérience de l’utilisateur final avant et après l’expiration du numéro de série

Les applications Acrobat et Creative Cloud pour les entreprises commenceront à afficher des messages (dans les applications) à partir de 60 jours avant l’expiration. Une fois le numéro de série expiré, les produits cessent de fonctionner et invitent l’utilisateur à agir.

### Creative Cloud pour l’expérience d’entreprise

Les informations suivantes décrivent l’expérience de l’utilisateur final. Voici une courte vidéo, suivie d’une révision de l’expérience utilisateur finale.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Avant expiration**

À compter de 60 jours avant l’expiration du numéro de série, tous les Creative Cloud pour entreprise affichent une boîte de dialogue dans le produit à l’utilisateur final. Ce message apparaîtra toutes les semaines, jusqu’à 30 jours avant l’expiration, puis tous les jours jusqu’à la date d’expiration à laquelle *Votre licence expire. Ce produit Adobe utilise une licence qui doit expirer le 29 novembre 2020. Veuillez contacter votre administrateur pour assurer un accès continu*.

![CCE avant le message d&#39;expiration](assets/cceexpiring.png)

**Après expiration**

Une fois le numéro de série expiré, les utilisateurs n’auront plus accès au Creative Cloud pour les applications d’entreprise. Lors du premier lancement après expiration, l’utilisateur est invité à ouvrir une boîte de dialogue indiquant *que le numéro de série que vous avez entré a expiré. Ce produit ne peut pas être sous licence. Veuillez contacter le service clientèle*.

![CCE après message d&#39;expiration](assets/cceafterexpire.png)

Pour toutes les tentatives ultérieures de lancement des applications, l’utilisateur final sera invité à **Se connecter maintenant**, suivi de l’option permettant de créer son propre Adobe ID et de passer en mode d’évaluation. Toutefois, toute nouvelle Adobe ID créée par l’utilisateur final ne sera pas associée aux licences de votre entreprise et causera une confusion supplémentaire à vos utilisateurs. Afin d’éviter toute interruption d’activité et/ou toute confusion inutile, faites migrer vos utilisateurs vers des licences nominatives avant l’expiration de votre ou vos numéros de série.

![CCE de la boîte de dialogue de connexion 1](assets/ccesignin1.png)

![Boîte de dialogue de connexion CCE 2](assets/ccesignin2.png)

### Expérience Acrobat

Les informations suivantes décrivent l’expérience de l’utilisateur final. Voici une courte vidéo, suivie d’une révision de l’expérience utilisateur finale.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Avant expiration**

À compter de 60 jours avant l’expiration du numéro de série, Acrobat affiche un message contextuel d’entrée de produit à l’intention de l’utilisateur final. Cela apparaîtra une fois par semaine jusqu&#39;à 7 jours avant l&#39;expiration. Il commencera alors à apparaître tous les jours en indiquant *que votre licence Adobe Acrobat expire le 30/11/2020. Veuillez contacter votre administrateur pour continuer à utiliser Acrobat sans interruption.*

![Message d&#39;expiration Acrobat](assets/acrobatexpiring.png)

**Après expiration**

Une fois le numéro de série expiré, les utilisateurs n’auront plus accès à Acrobat. Lors du premier lancement après expiration, l’utilisateur est invité à ouvrir une boîte de dialogue indiquant *que le numéro de série que vous avez entré a expiré. Ce produit ne peut pas être sous licence. Veuillez contacter le service clientèle.*

![Acrobat après le message d&#39;expiration](assets/acrobatafterexpire.png)

Pour toutes les tentatives ultérieures de lancement d’Acrobat, l’utilisateur final sera invité à **Se connecter maintenant**, suivi de l’option permettant de créer son propre Adobe ID et de passer en mode d’évaluation. Toutefois, toute nouvelle Adobe ID créée par l’utilisateur final ne sera pas associée aux licences de votre entreprise et causera une confusion supplémentaire à vos utilisateurs.

![Boîte de dialogue Connexion Acrobat 1](assets/acrobatsignin1.png)

![Boîte de dialogue Connexion Acrobat 2](assets/acrobatsignin2.png)

## Contactez-nous si vous avez besoin d’aide

Si vous avez des questions sur l’utilisation de l’outil [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) ou si vous avez besoin d’aide pour migrer du déploiement par numéro de série vers un utilisateur nommé, vous disposez de quelques options :
* Envoyer un courrier électronique à l’équipe d’intégration d’entreprise d’Adobe - **entonb@adobe.com**
* Ouvrir un ticket de support dans [Admin Console](https://adminconsole.adobe.com/support)
* Contactez votre responsable de compte d’Adobe ou votre responsable du succès client.
