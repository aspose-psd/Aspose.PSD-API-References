---
title: "SmartResourceCreator Klasse"
type: docs
weight: 910
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | Initialiseert een nieuw exemplaar van de [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) klasse. |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | Initialiseert een nieuw exemplaar van de [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) klasse. |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | Initialiseert een nieuw exemplaar van de [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) klasse<br/>
            met de opgegeven sjabloon. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | Genereert de geplaatste bron. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | Genereert de ingebedde slimme objectbron. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | Genereert de externe slimme objectbron. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

Initialiseert een nieuw exemplaar van de [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) klasse.

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

Initialiseert een nieuw exemplaar van de [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| is_custom | bool | indien ingesteld op <c>true</c> [is custom]. |
| has_comp_info | bool | indien ingesteld op <c>true</c> [has comp information]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

Initialiseert een nieuw exemplaar van de [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) klasse<br/>
            met de opgegeven sjabloon.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | De sjabloon voor de slimme objectbron. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

Genereert de geplaatste bron.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | De gegenereerde [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) instantie. |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

Genereert de ingebedde slimme objectbron.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | De gegenereerde [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) instantie. |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

Genereert de externe slimme objectbron.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | De gegenereerde [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) instantie. |


