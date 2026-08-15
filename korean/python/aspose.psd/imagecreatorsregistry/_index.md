---
title: "ImageCreatorsRegistry 클래스"
type: docs
weight: 2210
url: /ko/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | 등록된 디스크립터를 가져옵니다. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 등록된 이미지 생성 형식을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | 지정된 조건에 적합한 첫 번째 생성자를 생성합니다. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | 지정된 조건에 적합한 첫 번째 지원되는 설명자를 가져옵니다. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | 지정된 이미지 생성자 설명자를 등록합니다. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | 생성자를 등록합니다. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | 생성자의 등록을 취소합니다. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

지정된 조건에 적합한 첫 번째 생성자를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이미지 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | 지정된 항목을 지원하는 생성자이며, 해당 생성자를 찾을 수 없으면 null을 반환합니다. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

지정된 조건에 적합한 첫 번째 지원되는 설명자를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이미지 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 지정된 항목을 지원하는 생성자 설명자이며, 해당 설명자를 찾을 수 없으면 null을 반환합니다. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

지정된 이미지 생성자 설명자를 등록합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 이미지 생성자 설명자입니다. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

생성자를 등록합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 등록할 생성자 설명자. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

생성자의 등록을 취소합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 생성자 설명자. |

