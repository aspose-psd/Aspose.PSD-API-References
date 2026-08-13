---
title: "Classe GrdmResource"
type: docs
weight: 340
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Initialise une nouvelle instance de la classe [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| color_model | short | r/w | Modèle de couleur.<br/>            Lorsque 'Gradient type' = 'Noise', nous pouvons assigner 'Color Model' à RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Obtient ou définit les points de couleur. |
| tramage | bool | r/w | Le dégradé est trafiqué. |
| expansion_count | short | r/w | Nombre d'expansion ( = 2 pour Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Mode pour ce dégradé<br/>            Détermine 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | chaîne | r/w | Nom du dégradé : chaîne Unicode, remplie. |
| interpolation | short | r/w | Interpolation. Détermine la douceur, lorsque 'Gradient Type' = 'Solid' (GradientMode = 0). |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Couleur maximale du format PixelDataFormat.Rgba64Bpp.<br/>            La couleur possède des canaux ARGB, chaque canal est de 16 bits. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Couleur minimale du format PixelDataFormat.Rgba64Bpp.<br/>            La couleur possède des canaux ARGB, chaque canal est de 16 bits. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| inverser | bool | r/w | Le dégradé est inversé. |
| rnd_number_seed | int | r/w | La graine aléatoire utilisée pour générer les couleurs du dégradé Noise. |
| roughness | int | r/w | Facteur de rugosité<br/>            Lorsque 'Gradient type' = 'Noise', nous pouvons assigner 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | Indicateur d'affichage de la transparence<br/>            Lorsque 'Gradient type' = 'Noise', nous pouvons assigner 'Add transparency' à true. |
| signature | int | r | Obtient la signature. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Obtient ou définit les points de transparence. |
| use_vector_color | short | r/w | Indicateur d'utilisation de la couleur vectorielle. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre les données de la ressource dans le conteneur de flux spécifié. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Initialise une nouvelle instance de la classe [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| psd_version | int | La version psd de la ressource. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre les données de la ressource dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |
| psd_version | int | La version PSD. |

