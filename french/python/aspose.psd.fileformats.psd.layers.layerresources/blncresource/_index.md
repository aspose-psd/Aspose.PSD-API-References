---
title: "Classe BlncResource"
type: docs
weight: 80
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Initialise une nouvelle instance de la classe [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| highlights_cyan_red_balance | short | r/w | Obtient ou définit l'équilibre Cyan Rouge des hautes lumières. |
| highlights_magenta_green_balance | short | r/w | Obtient ou définit l'équilibre Magenta Vert des hautes lumières. |
| highlights_yellow_blue_balance | short | r/w | Obtient ou définit l'équilibre Jaune Bleu des hautes lumières. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| midtones_cyan_red_balance | short | r/w | Obtient ou définit l'équilibre Cyan Rouge des tons moyens. |
| midtones_magenta_green_balance | short | r/w | Obtient ou définit le Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | Obtient ou définit le Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | Obtient ou définit une valeur indiquant si ce [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) préserve la luminosité. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| shadows_cyan_red_balance | short | r/w | Obtient ou définit le Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | Obtient ou définit le Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | Obtient ou définit l'équilibre des ombres jaune bleu. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Initialise une nouvelle instance de la classe [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/).

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre la ressource dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |
| psd_version | int | La version PSD. |

