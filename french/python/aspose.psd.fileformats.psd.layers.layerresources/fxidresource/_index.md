---
title: "Classe FXidResource"
type: docs
weight: 290
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---

**Summary:** The Filter Effects resource contains channels, a user mask, and a sheet mask for the smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FXidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FXidResource(key, version, filter_effect_masks)](#FXidResource_key_version_filter_effect_masks_1) | Initialise une nouvelle instance de la classe [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| F_EID_TYPE_TOOL_KEY [statique] | int | r | La clé d'information de l'outil de type FEid. |
| F_XID_TYPE_TOOL_KEY [statique] | int | r | La clé d'information de l'outil de type FXid. |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | r | Obtient les masques d'effet de filtre. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| version | int | r | Obtient la version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: FXidResource(key, version, filter_effect_masks) {#FXidResource_key_version_filter_effect_masks_1}


```
 FXidResource(key, version, filter_effect_masks) 
```

Initialise une nouvelle instance de la classe [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | int | La clé de ressource. |
| version | int | La version. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | Les masques d'effet de filtre. |

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

