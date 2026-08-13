---
title: "Classe CgEdResource"
type: docs
weight: 130
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Initialise une nouvelle instance de la classe CgEdResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| auto | bool | r/w | Obtient ou définit une valeur indiquant si ce [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) est automatique. |
| luminosité | int | r/w | Obtient ou définit la luminosité. |
| contraste | int | r/w | Obtient ou définit le contraste. |
| clé | int | r | Obtient la clé de ressource du calque. |
| lab_color | bool | r/w | Obtient ou définit une valeur indiquant si [lab color] est utilisé. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| mean_value_for_brightness_and_contrast | int | r/w | Obtient ou définit la valeur moyenne pour la luminosité et le contraste. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| use_legacy | bool | r/w | Obtient ou définit une valeur indiquant si [use legacy] est utilisé. |
| version | int | r/w | Obtient ou définit la version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Initialise une nouvelle instance de la classe CgEdResource

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

