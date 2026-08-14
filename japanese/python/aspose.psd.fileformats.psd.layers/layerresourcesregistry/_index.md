---
title: "LayerResourcesRegistry クラス"
type: docs
weight: 1010
url: /ja/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | 登録された記述子を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | 最初にサポートされているオープナー記述子を取得します。 |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | タイプ名で最初にサポートされている記述子を取得します。 |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | 指定された <paramref name="stream" /> に適した最初に見つかったオープナーを使用して、[LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) をロードします。 |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | オープナーを登録します。 |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | オープナーの登録を解除します。 |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

最初にサポートされているオープナー記述子を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ストリーム。 |
| psd_version | int | PSD バージョンです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | レイヤーリソースローダー記述子、またはそのようなストリームでローダー記述子がサポートされていない場合は null。 |


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
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 最初に見つかったオープナー記述子、またはそのような記述子が見つからない場合は null。 |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

指定された <paramref name="stream" /> に適した最初に見つかったオープナーを使用して、[LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) をロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ストリーム。 |
| psd_version | int | PSD バージョンです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | ロードされた[LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)、またはオープナーが見つからない場合は null。 |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

オープナーを登録します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 登録するオープナー記述子。 |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

オープナーの登録を解除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 登録解除するオープナー記述子。 |

