---
title: "Класс SmartObjectProvider"
type: docs
weight: 1940
url: /ru/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Преобразует слои в встроенный smart object. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Преобразует слои в встроенный smart object. |
| embed_all_linked() | Встраивает все связанные smart object в изображение. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Создаёт новый слой smart object, копируя исходный. |
| update_all_modified_content() | Обновляет содержимое всех изменённых smart object в изображении. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Преобразует слои в встроенный smart object.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer_numbers | int | Номера слоёв. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Созданный экземпляр [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Преобразует слои в встроенный smart object.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Слои. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Созданный экземпляр [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Создаёт новый слой smart object, копируя исходный.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Исходный слой. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Клонированный экземпляр [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


