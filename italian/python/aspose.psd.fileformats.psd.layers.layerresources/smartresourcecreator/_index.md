---
title: "Classe SmartResourceCreator"
type: docs
weight: 910
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | Inizializza una nuova istanza della classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | Inizializza una nuova istanza della classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | Inizializza una nuova istanza della classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            con il modello fornito. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | Genera la risorsa posizionata. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | Genera la risorsa dell'oggetto intelligente incorporato. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | Genera la risorsa dell'oggetto intelligente esterno. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

Inizializza una nuova istanza della classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

Inizializza una nuova istanza della classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| is_custom | bool | se impostato su <c>true</c> [is custom]. |
| has_comp_info | bool | se impostato su <c>true</c> [has comp information]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

Inizializza una nuova istanza della classe [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            con il modello fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | Il modello di risorsa dell'oggetto intelligente. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

Genera la risorsa posizionata.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | L'istanza generata di [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/). |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

Genera la risorsa dell'oggetto intelligente incorporato.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | L'istanza generata di [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/). |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

Genera la risorsa dell'oggetto intelligente esterno.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | L'istanza generata di [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/). |


