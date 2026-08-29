---
title: "SmartResourceCreator Sınıfı"
type: docs
weight: 910
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | Yeni bir [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) sınıfının bir örneğini başlatır. |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | Yeni bir [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) sınıfının bir örneğini başlatır. |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | Yeni bir [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) sınıfının bir örneğini başlatır<br/>            verilen şablonla. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | Yerleştirilen kaynağı oluşturur. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | Gömülü akıllı nesne kaynağını oluşturur. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | Harici akıllı nesne kaynağını oluşturur. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

Yeni bir [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) sınıfının bir örneğini başlatır.

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

Yeni bir [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| is_custom | bool | eğer <c>true</c> olarak ayarlanırsa [is custom]. |
| has_comp_info | bool | eğer <c>true</c> olarak ayarlanırsa [has comp information]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

Yeni bir [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) sınıfının bir örneğini başlatır<br/>            verilen şablonla.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | Akıllı nesne kaynağı şablonu. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

Yerleştirilen kaynağı oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | Oluşturulan [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) örneği. |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

Gömülü akıllı nesne kaynağını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | Oluşturulan [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) örneği. |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

Harici akıllı nesne kaynağını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | Oluşturulan [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) örneği. |


