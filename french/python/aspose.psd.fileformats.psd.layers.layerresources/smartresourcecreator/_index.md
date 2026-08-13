---
title: "Classe SmartResourceCreator"
type: docs
weight: 910
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | Initialise une nouvelle instance de la classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | Initialise une nouvelle instance de la classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | Initialise une nouvelle instance de la classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            avec le modèle fourni. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | Génère la ressource placée. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | Génère la ressource d'objet intelligent intégré. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | Génère la ressource d'objet intelligent externe. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

Initialise une nouvelle instance de la classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

Initialise une nouvelle instance de la classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| is_custom | bool | si défini sur <c>true</c> [is custom]. |
| has_comp_info | bool | si défini sur <c>true</c> [has comp information]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

Initialise une nouvelle instance de la classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            avec le modèle fourni.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | Le modèle de ressource d'objet intelligent. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

Génère la ressource placée.

**Returns**

| Type | Description |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | L'instance générée de [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/). |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

Génère la ressource d'objet intelligent intégré.

**Returns**

| Type | Description |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | L'instance générée de [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/). |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

Génère la ressource d'objet intelligent externe.

**Returns**

| Type | Description |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | L'instance générée de [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/). |


