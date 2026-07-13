---
title: ​3. Créer votre premier graphique
description: Procédure pas à pas pour créer votre premier workflow Firefly Graph
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: 4dd919a2b06f0852dc0010b0f79d5a0b2eae4c1a
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 1%

---

# &#x200B;3. Création de votre premier graphique

Une fois que vous savez ce que sont un nœud, une connexion et un modèle, vous êtes prêt à créer votre premier workflow.

1. Ouvrez le Firefly et sélectionnez **Graphique** dans le menu de gauche.
1. Sélectionnez **Créer un graphique**.
1. Cliquez avec le bouton droit sur la zone de travail vide et sélectionnez **+ nouveau nœud**.
1. Sélectionnez **Entrée** dans le menu de gauche, puis **Image d&#39;entrée**.
   ![&#x200B; nœud](../assets/node.png)
Il s’agit d’un nœud qui vous permet d’importer un graphique.
1. Faites glisser et déposez une image sur le nœud.
   ![Nœud avec image](../assets/node-image.png)
1. Faites un clic droit sur la zone de travail vide et sélectionnez **+ nouveau nœud** et sélectionnez **Masque de dégradé** dans la boîte de dialogue.
1. Cliquez avec le bouton droit de la souris sur la zone de travail vide et sélectionnez **+ nouveau nœud** et sélectionnez **Appliquer le masque** dans la boîte de dialogue.
1. Connectez la sortie du nœud **Image d&#39;entrée** à l&#39;entrée du nœud d&#39;image **Appliquer le masque**.
1. Connectez la sortie **Masque de dégradé** à l&#39;entrée **Appliquer le masque** Masque/canal.
   ![Connecter les nœuds](../assets/plug-in.png)

## Étape suivante

Vous démarrez à partir d’un modèle ? Rendez-vous sur [4. Personnalisez un modèle](https://experienceleague.adobe.com/fr/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template) pour qu&#39;il reflète votre propre résumé.
