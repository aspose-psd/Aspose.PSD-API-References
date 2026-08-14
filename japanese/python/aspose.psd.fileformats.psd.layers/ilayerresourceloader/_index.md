---
title: "ILayerResourceLoader クラス"
type: docs
weight: 720
url: /ja/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | 指定された [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) からレイヤーリソースをロードできるかどうかを判断します。 |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) をロードします。 |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

指定された [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) からレイヤーリソースをロードできるかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <c>true</c> は、指定された [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) からレイヤーリソースをロードできる場合です。そうでない場合は <c>false</c> です。 |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

[LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) をロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ロード元のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | ロードされたリソースです。 |


