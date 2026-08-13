---
title: "Classe BlwhResource"
type: docs
weight: 90
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Initialise une nouvelle instance de la classe BlwhResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| black_and_white_preset_file_name | chaîne | r/w | Obtient ou définit le nom de fichier du préréglage noir et blanc. |
| bleus | int | r/w | Obtient ou définit la valeur des bleus. |
| bw_preset_kind | int | r/w | Obtient ou définit la valeur du type de préréglage noir et blanc. |
| cyans | int | r/w | Obtient ou définit la valeur des cyans. |
| verts | int | r/w | Obtient ou définit la valeur des verts. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| magentas | int | r/w | Obtient ou définit la valeur des magentas. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| rouges | int | r/w | Obtient ou définit la valeur des rouges. |
| signature | int | r | Obtient la signature. |
| tint_color | int | r/w | Obtient ou définit la valeur ARGB de la couleur de teinte. |
| use_tint | bool | r/w | Obtient ou définit une valeur indiquant si [tint color] est utilisé. |
| yellows | int | r/w | Obtient ou définit la valeur des jaunes. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Initialise une nouvelle instance de la classe BlwhResource

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

