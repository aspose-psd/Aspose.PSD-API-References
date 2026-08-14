---
title: "SmartResourceCreator Klasse"
type: docs
weight: 910
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | Initialisiert eine neue Instanz der [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) Klasse. |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | Initialisiert eine neue Instanz der [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) Klasse. |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | Initialisiert eine neue Instanz der [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) Klasse<br/>            mit der angegebenen Vorlage. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | Erzeugt die platzierte Ressource. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | Erzeugt die eingebettete Smart‑Objekt‑Ressource. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | Erzeugt die externe Smart‑Objekt‑Ressource. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

Initialisiert eine neue Instanz der [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) Klasse.

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

Initialisiert eine neue Instanz der [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| is_custom | bool | wenn auf <c>true</c> [ist benutzerdefiniert]. |
| has_comp_info | bool | wenn auf <c>true</c> [hat Kompositionsinformationen]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

Initialisiert eine neue Instanz der [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) Klasse<br/>            mit der angegebenen Vorlage.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | Die Smart‑Objekt‑Ressourcenvorlage. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

Erzeugt die platzierte Ressource.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | Die erzeugte [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) Instanz. |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

Erzeugt die eingebettete Smart‑Objekt‑Ressource.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | Die erzeugte [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) Instanz. |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

Erzeugt die externe Smart‑Objekt‑Ressource.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | Die erzeugte [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) Instanz. |


