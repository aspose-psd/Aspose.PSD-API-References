---
title: "LayerResourcesRegistry 클래스"
type: docs
weight: 1010
url: /ko/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | 등록된 디스크립터를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | 첫 번째 지원되는 오프너 디스크립터를 가져옵니다. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | 형식 이름으로 첫 번째 지원되는 디스크립터를 가져옵니다. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | 지정된 <paramref name="stream" />에 적합한 첫 번째 발견된 오프너를 사용하여 [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)를 로드합니다. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | 오프너를 등록합니다. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | 오프너의 등록을 취소합니다. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

첫 번째 지원되는 오프너 디스크립터를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 스트림. |
| psd_version | int | PSD 버전. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 해당 스트림에 대해 지원되는 로더 디스크립터가 없으면 null인 레이어 리소스 로더 디스크립터. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

형식 이름으로 첫 번째 지원되는 디스크립터를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| descriptor_type_name | 문자열 | 디스크립터 유형 이름. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 첫 번째로 발견된 오프너 디스크립터 또는 해당 디스크립터가 없으면 null. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

지정된 <paramref name="stream" />에 적합한 첫 번째 발견된 오프너를 사용하여 [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)를 로드합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 스트림. |
| psd_version | int | PSD 버전. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | 로드된 [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) 또는 오프너가 없으면 null. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

오프너를 등록합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 등록할 오프너 디스크립터. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

오프너의 등록을 취소합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 등록 취소할 오프너 디스크립터. |

