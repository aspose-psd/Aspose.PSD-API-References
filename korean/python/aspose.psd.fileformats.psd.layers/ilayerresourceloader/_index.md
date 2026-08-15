---
title: "ILayerResourceLoader 클래스"
type: docs
weight: 720
url: /ko/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **설명** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | 지정된 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)에서 레이어 리소스를 로드할 수 있는지 여부를 결정합니다. |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)을 로드합니다. |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

지정된 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)에서 레이어 리소스를 로드할 수 있는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| psd_version | int | PSD 버전. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/)에서 레이어 리소스를 로드할 수 있으면 <c>true</c>, 그렇지 않으면 <c>false</c>입니다. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

[LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)을 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 로드할 스트림 컨테이너입니다. |
| psd_version | int | PSD 버전. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | 로드된 리소스입니다. |


