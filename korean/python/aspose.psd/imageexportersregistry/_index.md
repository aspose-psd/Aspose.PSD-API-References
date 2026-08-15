---
title: "ImageExportersRegistry 클래스"
type: docs
weight: 2230
url: /ko/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | 등록된 내보내기 설명자를 가져옵니다. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 등록된 내보내기 형식을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | 지정된 저장 옵션 및 이미지에 적합한 첫 번째 내보내기를 생성합니다. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | 지정된 저장 옵션 및 이미지에 적합한 첫 번째 지원되는 설명자를 가져옵니다. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | 지정된 이미지 내보내기 설명자를 등록합니다. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | 내보내기를 등록합니다. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | 내보내기의 등록을 취소합니다. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

지정된 저장 옵션 및 이미지에 적합한 첫 번째 내보내기를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 내보낼 이미지. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 내보내기에 사용할 저장 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | 지정된 이미지와 저장 옵션을 지원하는 내보내기 도구이며, 해당 내보내기 도구가 없으면 null을 반환합니다. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

지정된 저장 옵션 및 이미지에 적합한 첫 번째 지원되는 설명자를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 내보낼 이미지. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 지정된 이미지와 저장 옵션을 지원하는 내보내기 설명자이며, 해당 설명자가 없으면 null을 반환합니다. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

지정된 이미지 내보내기 설명자를 등록합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 이미지 내보내기 설명자. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

내보내기를 등록합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 등록할 내보내기 설명자. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

내보내기의 등록을 취소합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 등록 취소할 내보내기 설명자. |

