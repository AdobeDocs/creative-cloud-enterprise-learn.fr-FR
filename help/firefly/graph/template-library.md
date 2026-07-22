---
title: Bibliothèque de modèles
description: Parcourez les modèles de graphiques de Firefly prêts à l’emploi que vous pouvez ouvrir et adapter à votre propre projet
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: aa0ae4747f081c69d8a01d3f9acdd7844cca6afe
workflow-type: tm+mt
source-wordcount: '996'
ht-degree: 2%

---

# &#x200B;5. Bibliothèque de modèles

Index de référence rapide de modèles de graphiques Firefly, organisé en fonction de ce que chacun produit ou fait. Chaque exemple est un point de départ : échangez votre propre marque, produit et invites avant d’utiliser un modèle en production.

## Génération et style d’image

| Modèle de graphique | Description | [!BADGE Cas d’utilisation]{type=Informative tooltip="Exemples d’utilisation"} |
|---|---|---|
| [**Prise en main - Génération d&#39;une image**](/help/firefly/graph/templates/get-started-gen-image.md) | Ce modèle est un graphique de base : un nœud d’invite en un nœud de génération en une sortie. Utilisez-le comme premier modèle à ouvrir avec un tout nouvel utilisateur. | Commerce de détail, Santé, Éducation |
| [**Génération de caractères cohérente**](/help/firefly/graph/templates/character-gen.md) | Dans ce modèle de graphique, vous chargez une image de référence d’un personnage, puis vous permutez l’invite de scène ou de pose pour chaque nouvelle prise de vue. La référence de caractère reste verrouillée lorsque la scène environnante change. | Voyage, Commerce de détail, Éducation |
| [**Extraction de style**](/help/firefly/graph/templates/style-extraction.md) | Dans ce modèle de graphique, vous insérez une image de référence pour extraire son traitement de couleur, de lumière et de texture. Vous pouvez ensuite appliquer ce traitement à toute nouvelle image exécutée sur le même graphique. | Voyage, Commerce de détail, Boissons |
| [**Vibes de coucher de soleil**](/help/firefly/graph/templates/sunset-vibes.md) | Ce modèle de graphique permet de créer une image typographique 3D à partir d’une invite de texte. Le modèle gère automatiquement le positionnement et la balance des couleurs. | Voyage, Boissons, Commerce de détail |

## Segmentation et composition

| Modèle de graphique | Description | [!BADGE Cas d’utilisation]{type=Informative tooltip="Exemples d’utilisation"} |
|---|---|---|
| [**Prise en main : segmentation d&#39;une image**](/help/firefly/graph/templates/get-started-segment-image.md) | Dans ce modèle de graphique, vous chargez une image source et exécutez le nœud de segmentation pour isoler le sujet de son arrière-plan. Associez-le à un nœud de remplacement d’arrière-plan pour un découpage net. | Santé, Commerce de détail, Automobile |
| [**Composer et fusionner des calques**](/help/firefly/graph/templates/composite-blend-layers.md) | Dans ce modèle de graphique, vous superposez un découpage de produit et une scène d’arrière-plan en tant qu’entrées de calque distinctes. Réglez le mode de fusion et les nœuds d’éclairage jusqu’à ce que la composition soit lue en une seule prise. | Boissons, Commerce de détail, Voyages |
| [**Correction sélective des couleurs**](/help/firefly/graph/templates/selective-color-correction.md) | Dans ce modèle de graphique, vous masquez une zone spécifique qui doit être corrigée et définissez la couleur cible sur ce nœud uniquement. Le reste de l’image traverse le graphique sans être touché. | Communications et télécommunications, Commerce de détail, Finance |

## Vidéo et mouvement

| Modèle de graphique | Description | [!BADGE Cas d’utilisation]{type=Informative tooltip="Exemples d’utilisation"} |
|---|---|---|
| [**Prise en main - Génération de vidéos**](/help/firefly/graph/templates/get-started-video-gen.md) | Dans ce modèle de graphique, vous insérez une image clé fixe approuvée et une courte invite de mouvement. Le modèle génère une séquence vidéo construite à partir de cette même illustration plutôt qu’une nouvelle prise de vue. | Finance, Boissons, Commerce de détail |
| [**Bullet Time VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) | Dans ce modèle de graphique, vous insérez un produit phare ou une image de sujet pour générer une séquence d’angles autour de celui-ci, puis coupez automatiquement le balayage de l’image figée. | Extérieur, Commerce de détail, Automobile |

## Création de storyboards

| Modèle de graphique | Description | [!BADGE Cas d’utilisation]{type=Informative tooltip="Exemples d’utilisation"} |
|---|---|---|
| [**Texte sur storyboard**](/help/firefly/graph/templates/text-to-storyboard.md) | Dans ce modèle de graphique, vous remplacez les nœuds d’entrée de texte par les éléments de votre article. Chaque ligne devient sa propre image de storyboard, générée dans l’ordre et présentée pour révision sous la forme d’un ensemble de panneaux unique. | Finance, Commerce de détail, Technologie |
| [**Créateur de storyboards**](/help/firefly/graph/templates/storyboard-builder.md) | Dans ce modèle de graphique, vous créez une scène de storyboard par scène en ajoutant un nœud par battement du récit. Réorganisez les nœuds pour tester une séquence différente avant de verrouiller l’ordre final des panneaux. | Communications et télécommunications, Boissons, Voyages |

## 3D et caractère

| Modèle de graphique | Description | [!BADGE Cas d’utilisation]{type=Informative tooltip="Exemples d’utilisation"} |
|---|---|---|
| [**Nuanceurs en temps réel**](/help/firefly/graph/templates/real-time-shaders.md) | Dans ce modèle de graphique, vous commencez par une image, appliquez trois ombrages personnalisés différents et prévisualisez le résultat en temps réel. Ajustez les paramètres du shader directement sur le nœud plutôt que d’effectuer un nouveau rendu à partir de zéro. | Technologie, Automobile, Commerce de détail |
| [**Génération du modèle de caractère**](/help/firefly/graph/templates/character-model-generation.md) | Dans ce modèle de graphique, vous créez un style d’animation 3D pour une illustration. Le modèle génère une passe de modèle 3D de base prête à être remise à un modélisateur pour nettoyage, plutôt que de partir d’une scène vierge. | Plein air, Technologie, Éducation |
| [**Conception de jouet en vinyle**](/help/firefly/graph/templates/vinyl-toy-design.md) | Dans ce modèle de graphique, vous saisissez une référence de personnage ou de mascotte et en effectuez le rendu sous la forme d’un jouet en vinyle stylisé. Il existe des angles de retournement pour un dossier de licence ou d’examen de produit. | Commerce de détail, Boissons, Divertissement |
| [**Conversion d’esquisse en 3D**](/help/firefly/graph/templates/sketch-to-3d.md) | Dans ce modèle de graphique, vous transformez une esquisse en un caractère 3D. Le graphique crée un retournement 3D rotatif à partir de celui-ci, prêt pour une révision de conception interne avant tout prototype physique. | Technologie, automobile, divertissement |

## Maquettes de produits et de marques

| Modèle de graphique | Description | [!BADGE Cas d’utilisation]{type=Informative tooltip="Exemples d’utilisation"} |
|---|---|---|
| [**Visualisation de la marque**](/help/firefly/graph/templates/branding-visualization.md) | Dans ce modèle de graphique, apprenez à visualiser le logo ou la marque dans les scènes de produit. Ajoutez des directives de marque pour un logo et une palette de couleurs et le graphique produit des illustrations statiques et une courte passe de mouvement en une seule fois, de sorte que les deux formats restent visuellement alignés. | Technologie, boissons, finance |
| [**Maquette de produit de marque**](/help/firefly/graph/templates/brand-product-mockup.md) | Dans ce modèle de graphique, découvrez comment visualiser votre produit dans différentes scènes. Vous déposez un rendu de produit ou une photo dans le nœud de maquette et le graphique le place dans une scène entièrement marquée, avec un éclairage et une ombre automatiquement adaptés à cette scène. | Commerce de détail, Boissons, Technologie |
| [**Séance photo éditoriale**](/help/firefly/graph/templates/editorial-photoshoot.md) | Dans ce modèle de graphique, vous chargez une référence de modèle et permutez l’entrée du vêtement pour chaque nouveau look. Les nœuds de pose et d’éclairage restent verrouillés sur l’ensemble pour une sensation éditoriale cohérente. | Commerce de détail, Beauté, Plein air |
| [**Studio de photographie**](/help/firefly/graph/templates/photography-studio.md) | Dans ce modèle de graphique, vous placez un rendu de produit en arrière-plan de studio et ajustez l’éclairage jusqu’à ce que le résultat ressemble à une vraie capture de studio. | Boissons, Technologie, Commerce de détail |
| [**Appliquer la décalcomanie aux surfaces**](/help/firefly/graph/templates/decal-to-surfaces.md) | Dans ce modèle de graphique, vous chargez la maquette du produit de base et la décalcomanie ou le logo en tant qu’entrées distinctes. Le gabarit adapte la décalcomanie à la géométrie de la surface afin qu&#39;elle suive correctement les contours. | Extérieur, Automobile, Commerce de détail |

## Opérations par lots et de cohérence

| Modèle de graphique | Description | [!BADGE Cas d’utilisation]{type=Informative tooltip="Exemples d’utilisation"} |
|---|---|---|
| [**Concevoir le générateur de système**](/help/firefly/graph/templates/design-system-generator.md) | Ce modèle de graphique permet de générer une charte graphique à partir d’une capture d’écran de site web. Le graphique produit un ensemble d’icônes, de motifs et de composants de mise en page correspondants dans une seule exécution par lots. | Technologie, finance, communications et télécommunications |
| [**Génération de photos**](/help/firefly/graph/templates/headshots-generation.md) | Ce modèle de graphique permet d’harmoniser un lot de photos d’entreprise. Chargez les photos source, une par personne, et le graphique normalise l’éclairage, l’arrière-plan et le recadrage sur l’ensemble en une seule fois. | Technologie, finance, santé |

Revenez à [Commencer avec Firefly Graph](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph).