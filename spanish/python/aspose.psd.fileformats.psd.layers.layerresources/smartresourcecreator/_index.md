---
title: "Clase SmartResourceCreator"
type: docs
weight: 910
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | Inicializa una nueva instancia de la clase [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | Inicializa una nueva instancia de la clase [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | Inicializa una nueva instancia de la clase [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) <br/>            con la plantilla proporcionada. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | Genera el recurso colocado. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | Genera el recurso de objeto inteligente incrustado. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | Genera el recurso de objeto inteligente externo. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

Inicializa una nueva instancia de la clase [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

Inicializa una nueva instancia de la clase [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| is_custom | bool | si se establece en <c>true</c> [es personalizado]. |
| has_comp_info | bool | si se establece en <c>true</c> [tiene información de composición]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

Inicializa una nueva instancia de la clase [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) <br/>            con la plantilla proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | La plantilla del recurso de objeto inteligente. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

Genera el recurso colocado.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | La instancia generada de [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/). |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

Genera el recurso de objeto inteligente incrustado.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | La instancia generada de [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/). |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

Genera el recurso de objeto inteligente externo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | La instancia generada de [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/). |


