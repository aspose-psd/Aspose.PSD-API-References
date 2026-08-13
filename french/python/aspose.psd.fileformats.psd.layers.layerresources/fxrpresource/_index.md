---
title: "Classe FxrpResource"
type: docs
weight: 320
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/
---

**Summary:** Class FxrpResource. The reference point of layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FxrpResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FxrpResource()](#FxrpResource__1) | Initialise une nouvelle instance de la classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/). |
| [FxrpResource(data)](#FxrpResource_data_2) | Initialise une nouvelle instance de la classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).<br/>            Avec une valeur personnalisée ou inconnue |
| [FxrpResource(x, y)](#FxrpResource_x_y_3) | Initialise une nouvelle instance de la classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| x | double | r/w | Obtient ou définit le x du point de référence |
| y | double | r/w | Obtient ou définit le y du point de référence |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre dans le conteneur de flux spécifié. |


### Constructor: FxrpResource() {#FxrpResource__1}


```
 FxrpResource() 
```

Initialise une nouvelle instance de la classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).

### Constructor: FxrpResource(data) {#FxrpResource_data_2}


```
 FxrpResource(data) 
```

Initialise une nouvelle instance de la classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).<br/>            Avec une valeur personnalisée ou inconnue

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données de la ressource. |

### Constructor: FxrpResource(x, y) {#FxrpResource_x_y_3}


```
 FxrpResource(x, y) 
```

Initialise une nouvelle instance de la classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | La coordonnée x du point de référence |
| y | double | La coordonnée y du point de référence |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |
| psd_version | int | La version PSD. |

