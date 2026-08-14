---
title: "OSTypeStructuresRegistry クラス"
type: docs
weight: 720
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | 登録された記述子を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | 最初にサポートされているオープナー記述子を取得します。 |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | タイプ名で最初にサポートされている記述子を取得します。 |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | 指定された <paramref name="stream" /> に適した最初に見つかったオープナーを使用して、[OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) をロードします。 |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | オープナーを登録します。 |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | オープナーの登録を解除します。 |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

最初にサポートされているオープナー記述子を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | レイヤーリソースローダー記述子、またはそのようなストリームでローダー記述子がサポートされていない場合は null。 |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

タイプ名で最初にサポートされている記述子を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| descriptor_type_name | string | 記述子タイプ名。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | 最初に見つかったオープナー記述子、またはそのような記述子が見つからない場合は null。 |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

指定された <paramref name="stream" /> に適した最初に見つかったオープナーを使用して、[OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) をロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | ロードされた[LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)、またはオープナーが見つからない場合は null。 |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

オープナーを登録します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | 登録するオープナー記述子。 |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

オープナーの登録を解除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | 登録解除するオープナー記述子。 |

