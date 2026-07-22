---
title: Bibliothèque de modèles
description: Parcourez les modèles de graphiques de Firefly prêts à l’emploi que vous pouvez ouvrir et adapter à votre propre projet
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: facfbfbe45a25cbaf430446a326adb320d4e6968
workflow-type: tm+mt
source-wordcount: '874'
ht-degree: 0%

---

# &#x200B;5. Bibliothèque de modèles

Index de référence rapide de modèles de graphiques Firefly, organisé en fonction de ce que chacun produit ou fait. Chaque exemple est un point de départ : échangez votre propre marque, produit et invites avant d’utiliser un modèle en production.

## Génération et style d’image

* [**Prise en main - Générer une image**](/help/firefly/graph/templates/get-started-gen-image.md) — Ce modèle est un graphique de base : un nœud d&#39;invite en un nœud de génération en une sortie. Utilisez-le comme premier modèle à ouvrir avec un tout nouvel utilisateur.
* [**Génération de caractères cohérente**](/help/firefly/graph/templates/character-gen.md) : dans ce modèle de graphique, vous chargez une image de référence d&#39;un caractère, puis vous permutez la scène ou l&#39;invite de pose pour chaque nouvelle prise de vue. La référence de caractère reste verrouillée lorsque la scène environnante change.
* [**Extraction de style**](/help/firefly/graph/templates/style-extraction.md) : dans ce modèle de graphique, vous insérez une image de référence pour extraire son traitement de couleur, de lumière et de texture. Vous pouvez ensuite appliquer ce traitement à toute nouvelle image exécutée sur le même graphique.
* [**Sunset vibes**](/help/firefly/graph/templates/sunset-vibes.md) : ce modèle de graphique permet de créer une image typographique 3D à partir d’une invite de texte. Le modèle gère automatiquement le positionnement et la balance des couleurs.

## Segmentation et composition

* [**Prise en main - Segmenter une image**](/help/firefly/graph/templates/get-started-segment-image.md) : dans ce modèle de graphique, vous chargez n&#39;importe quelle image source et exécutez le nœud de segmentation pour isoler le sujet de son arrière-plan. Associez-le à un nœud de remplacement d’arrière-plan pour un découpage net.
* [**Composer et fusionner des calques**](/help/firefly/graph/templates/composite-blend-layers.md) : dans ce modèle de graphique, vous superposez un découpage de produit et une scène d’arrière-plan en tant qu’entrées de calque distinctes. Réglez le mode de fusion et les nœuds d’éclairage jusqu’à ce que la composition soit lue en une seule prise.
* [**Correction sélective des couleurs**](/help/firefly/graph/templates/selective-color-correction.md) : dans ce modèle de graphique, vous masquez une zone spécifique qui doit être corrigée et définissez la couleur cible sur ce nœud uniquement. Le reste de l’image traverse le graphique sans être touché.

## Vidéo et mouvement

* [**Prise en main - Génération vidéo**](/help/firefly/graph/templates/get-started-video-gen.md) : dans ce modèle de graphique, vous insérez une illustration clé fixe approuvée et une courte invite de mouvement. Le modèle génère une séquence vidéo construite à partir de cette même illustration plutôt qu’une nouvelle prise de vue.
* [**Bullet Time VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) : dans ce modèle de graphique, vous insérez un produit phare ou une image de sujet pour générer une séquence d&#39;angles rotative autour de celui-ci, puis coupez automatiquement le balayage des images figées.

## Création de storyboards

* [**Texte en storyboard**](/help/firefly/graph/templates/text-to-storyboard.md) : dans ce modèle de graphique, vous remplacez les nœuds d’entrée de texte par des éléments de votre article. Chaque ligne devient sa propre image de storyboard, générée dans l’ordre et présentée pour révision sous la forme d’un ensemble de panneaux unique.
* [**Créateur de storyboards**](/help/firefly/graph/templates/storyboard-builder.md) : dans ce modèle de graphique, vous créez une scène de storyboard par scène en ajoutant un nœud par battement du récit. Réorganisez les nœuds pour tester une séquence différente avant de verrouiller l’ordre final des panneaux.

## 3D et caractère

* [**Nuanciers en temps réel**](/help/firefly/graph/templates/real-time-shaders.md) : dans ce modèle de graphique, vous commencez par une image, appliquez trois nuanciers personnalisés différents et prévisualisez le résultat en temps réel. Ajustez les paramètres du shader directement sur le nœud plutôt que d’effectuer un nouveau rendu à partir de zéro.
* [**Génération du modèle de caractère**](/help/firefly/graph/templates/character-model-generation.md) : dans ce modèle de graphique, vous créez un style animé 3D d’illustration. Le modèle génère une passe de modèle 3D de base prête à être remise à un modélisateur pour nettoyage, plutôt que de partir d’une scène vierge.
* [**Conception de jouet en vinyle**](/help/firefly/graph/templates/vinyl-toy-design.md) : dans ce modèle de graphique, vous devez saisir une référence de personnage ou de mascotte et la restituer sous forme de jouet en vinyle stylisé. Il existe des angles de retournement pour un dossier de licence ou d’examen de produit.
* [**Retournement d&#39;esquisse en 3D**](/help/firefly/graph/templates/sketch-to-3d.md) : dans ce modèle de graphique, vous transformez une esquisse en un caractère 3D. Le graphique crée un retournement 3D rotatif à partir de celui-ci, prêt pour une révision de conception interne avant tout prototype physique.

## Maquettes de produits et de marques

* [**Visualisation de l&#39;image de marque**](/help/firefly/graph/templates/branding-visualization.md) : découvrez comment visualiser les scènes de produit dans ce modèle de graphique. Ajoutez des directives de marque pour un logo et une palette de couleurs et le graphique produit des illustrations statiques et une courte passe de mouvement en une seule fois, de sorte que les deux formats restent visuellement alignés.
* [**Maquette de produit de marque**](/help/firefly/graph/templates/brand-product-mockup.md) : dans ce modèle de graphique, découvrez comment visualiser votre produit dans différentes scènes. Vous déposez un rendu de produit ou une photo dans le nœud de maquette et le graphique le place dans une scène entièrement marquée, avec un éclairage et une ombre automatiquement adaptés à cette scène.
* [**Séance photo éditoriale**](/help/firefly/graph/templates/editorial-photoshoot.md) : dans ce modèle de graphique, vous chargez une référence de modèle et permutez l&#39;entrée du vêtement pour chaque nouveau look. Les nœuds de pose et d’éclairage restent verrouillés sur l’ensemble pour une sensation éditoriale cohérente.
* [**Studio de photographie**](/help/firefly/graph/templates/photography-studio.md) : dans ce modèle de graphique, vous placez un rendu de produit en studio et ajustez l&#39;éclairage jusqu&#39;à ce que le résultat ressemble à une véritable capture de studio.
* [**Appliquer la décalcomanie aux surfaces**](/help/firefly/graph/templates/decal-to-surfaces.md) : dans ce modèle de graphique, vous chargez la maquette du produit de base et la décalcomanie ou le logo comme entrées distinctes. Le gabarit adapte la décalcomanie à la géométrie de la surface afin qu&#39;elle suive correctement les contours.

## Opérations par lots et de cohérence

* [**Générateur de système de conception**](/help/firefly/graph/templates/design-system-generator.md) : dans ce modèle de graphique, vous générez un système de conception basé sur une capture d&#39;écran de site Web. Le graphique produit un ensemble d’icônes, de motifs et de composants de mise en page correspondants dans une seule exécution par lots.
* [**Génération d&#39;images principales**](/help/firefly/graph/templates/headshots-generation.md) : dans ce modèle de graphique, vous harmonisez un lot d&#39;images principales d&#39;entreprise. Chargez les photos source, une par personne, et le graphique normalise l’éclairage, l’arrière-plan et le recadrage sur l’ensemble en une seule fois.

Revenez à [Commencer avec Firefly Graph](https://experienceleague.adobe.com/fr/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph).