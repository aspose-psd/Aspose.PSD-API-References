---
title: "Класс SmartResourceCreator"
type: docs
weight: 910
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | Инициализирует новый экземпляр класса [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | Инициализирует новый экземпляр класса [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/). |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | Инициализирует новый экземпляр класса [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            с заданным шаблоном. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | Создаёт размещённый ресурс. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | Создаёт встроенный ресурс смарт‑объекта. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | Создаёт внешний ресурс смарт‑объекта. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

Инициализирует новый экземпляр класса [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

Инициализирует новый экземпляр класса [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| is_custom | bool | если установлено в <c>true</c> [is custom]. |
| has_comp_info | bool | если установлено в <c>true</c> [has comp information]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

Инициализирует новый экземпляр класса [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            с заданным шаблоном.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | Шаблон ресурса смарт‑объекта. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

Создаёт размещённый ресурс.

**Returns**

| Тип | Описание |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | Сгенерированный экземпляр [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/). |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

Создаёт встроенный ресурс смарт‑объекта.

**Returns**

| Тип | Описание |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | Сгенерированный экземпляр [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/). |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

Создаёт внешний ресурс смарт‑объекта.

**Returns**

| Тип | Описание |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | Сгенерированный экземпляр [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/). |


