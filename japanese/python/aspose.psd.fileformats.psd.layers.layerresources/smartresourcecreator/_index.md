---
title: "SmartResourceCreator クラス"
type: docs
weight: 910
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | 新しい [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) クラスのインスタンスを初期化します。 |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | 新しい [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) クラスのインスタンスを初期化します。 |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | 新しい [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) クラスのインスタンスを、指定されたテンプレートで初期化します。<br/>             |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | 配置されたリソースを生成します。 |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | 埋め込みスマートオブジェクトリソースを生成します。 |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | 外部スマートオブジェクトリソースを生成します。 |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

新しい [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) クラスのインスタンスを初期化します。

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

新しい [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| is_custom | bool | <c>true</c> に設定された場合、[is custom]です。 |
| has_comp_info | bool | <c>true</c> に設定された場合、[has comp information]です。 |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

新しい [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) クラスのインスタンスを、指定されたテンプレートで初期化します。<br/>            

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | スマートオブジェクトリソーステンプレートです。 |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

配置されたリソースを生成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | 生成された [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) インスタンスです。 |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

埋め込みスマートオブジェクトリソースを生成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | 生成された [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) インスタンスです。 |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

外部スマートオブジェクトリソースを生成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | 生成された [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) インスタンスです。 |


