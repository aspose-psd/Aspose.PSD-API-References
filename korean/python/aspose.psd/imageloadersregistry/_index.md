---
title: "ImageLoadersRegistry 클래스"
type: docs
weight: 2260
url: /ko/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | 등록된 디스크립터를 가져옵니다. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 등록된 이미지 로드 형식을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | 지정된 <paramref name=\"stream\" />에 적합하고 선택적으로 <paramref name=\"loadOptions\" />에 적합한 첫 번째 로더를 생성합니다. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | 지정된 <paramref name=\"stream\" />에 적합하고 선택적으로 <paramref name=\"loadOptions\" />에 적합한 첫 번째 지원되는 설명자를 가져옵니다. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | 형식 이름으로 첫 번째 지원되는 파일 형식을 가져옵니다. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | 형식 이름으로 첫 번째 지원되는 디스크립터를 가져옵니다. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | 지정된 이미지 로더 설명자를 등록합니다. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | 로더를 등록합니다. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | 로더의 등록을 취소합니다. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

지정된 <paramref name=\"stream\" />에 적합하고 선택적으로 <paramref name=\"loadOptions\" />에 적합한 첫 번째 로더를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 스트림. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 로드 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | 지정된 <paramref name=\"stream\" /> 및 <paramref name=\"loadOptions\" />를 지원하는 로더이며, 해당 로더가 없으면 null을 반환합니다. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

지정된 <paramref name=\"stream\" />에 적합하고 선택적으로 <paramref name=\"loadOptions\" />에 적합한 첫 번째 지원되는 설명자를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 스트림. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 로드 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 지정된 <paramref name=\"stream\" /> 및 <paramref name=\"loadOptions\" />를 지원하는 로더 설명자이며, 해당 설명자가 없으면 null을 반환합니다. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

형식 이름으로 첫 번째 지원되는 파일 형식을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | 지원되는 설명자 파일 형식입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 첫 번째로 찾은 로더 설명자이며, 해당 설명자가 없으면 null을 반환합니다. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


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
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 첫 번째로 찾은 로더 설명자이며, 해당 설명자가 없으면 null을 반환합니다. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

지정된 이미지 로더 설명자를 등록합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 이미지 로더 설명자입니다. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

로더를 등록합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 등록할 로더 설명자입니다. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

로더의 등록을 취소합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 등록 취소할 로더 설명자입니다. |

