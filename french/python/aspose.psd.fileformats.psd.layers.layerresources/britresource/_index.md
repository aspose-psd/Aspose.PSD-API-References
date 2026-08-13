---
title: "BritResource Classe"
type: docs
weight: 120
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BritResource()](#BritResource__1) | Initialise une nouvelle instance de la classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Initialise une nouvelle instance de la classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(bytes)](#BritResource_bytes_3) | Initialise une nouvelle instance de la classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            La spécification du format PSD contient la description suivante :<br/>            2 Luminosité<br/>            2 Contraste<br/>            2 Valeur moyenne pour la luminosité et le contraste<br/>            1 Couleur Lab uniquement<br/>            Elle n'est pas utilisée dans les PSD modernes (CS5 et plus) où CgEd est présent. CgEd stocke les propriétés d'information |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| luminosité | short | r/w | Obtient ou définit la luminosité. |
| contraste | short | r/w | Obtient ou définit le contraste. |
| clé | int | r | Obtient la clé de ressource du calque. |
| lab_color | bool | r/w | Obtient ou définit une valeur indiquant si [lab color]. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| mean_value_for_brightness_and_contrast | short | r/w | Obtient ou définit la valeur moyenne pour la luminosité et le contraste. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Initialise une nouvelle instance de la classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Initialise une nouvelle instance de la classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| luminosité | short | La luminosité. |
| contraste | short | Le contraste. |
| mean_value_for_brightness_and_contrast | short | La valeur moyenne pour la luminosité et le contraste. |
| lab_color | bool | si défini sur <c>true</c> [couleur Lab]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Initialise une nouvelle instance de la classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            La spécification du format PSD contient la description suivante :<br/>            2 Luminosité<br/>            2 Contraste<br/>            2 Valeur moyenne pour la luminosité et le contraste<br/>            1 Couleur Lab uniquement<br/>            Elle n'est pas utilisée dans les PSD modernes (CS5 et plus) où CgEd est présent. CgEd stocke les propriétés d'information

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | byte | Les octets. |

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

