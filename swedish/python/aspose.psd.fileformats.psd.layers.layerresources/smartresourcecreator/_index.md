---
title: "SmartResourceCreator-klass"
type: docs
weight: 910
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | Initierar en ny instans av klassen [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | Initierar en ny instans av klassen [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | Initierar en ny instans av klassen [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) klass<br/>            med den angivna mallen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | Genererar den placerade resursen. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | Genererar den inbäddade smarta objektresursen. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | Genererar den externa smarta objektresursen. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

Initierar en ny instans av klassen [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

Initierar en ny instans av klassen [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| is_custom | bool | om den är satt till <c>true</c> [är anpassad]. |
| has_comp_info | bool | om den är satt till <c>true</c> [har kompositionsinformation]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

Initierar en ny instans av klassen [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) klass<br/>            med den angivna mallen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | Mallen för smarta objektresursen. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

Genererar den placerade resursen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | Den genererade [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) instansen. |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

Genererar den inbäddade smarta objektresursen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | Den genererade [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) instansen. |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

Genererar den externa smarta objektresursen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | Den genererade [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) instansen. |


