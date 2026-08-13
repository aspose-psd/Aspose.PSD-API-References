---
title: "SmartObjectProvider 类"
type: docs
weight: 1940
url: /zh/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | 将图层转换为嵌入的智能对象。 |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | 将图层转换为嵌入的智能对象。 |
| embed_all_linked() | 在图像中嵌入所有已链接的智能对象。 |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | 通过复制源图层创建新的智能对象图层。 |
| update_all_modified_content() | 更新图像中所有已修改智能对象的内容。 |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

将图层转换为嵌入的智能对象。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer_numbers | int | 图层编号。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 创建的 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 实例。 |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

将图层转换为嵌入的智能对象。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 图层。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 创建的 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 实例。 |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

通过复制源图层创建新的智能对象图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 源图层。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 克隆的 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 实例。 |


