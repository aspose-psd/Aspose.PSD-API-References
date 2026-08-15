---
title: "IImageLoaderDescriptor 클래스"
type: docs
weight: 1820
url: /ko/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 지원되는 형식을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | 지정된 스트림에서 새 이미지를 읽을 수 있는지 여부를 판단하고, 선택적으로 <paramref name="loadOptions" />를 사용합니다. |
| [create_instance()](#create_instance__2) | 새 로더 인스턴스를 생성합니다. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

지정된 스트림에서 새 이미지를 읽을 수 있는지 여부를 판단하고, 선택적으로 <paramref name="loadOptions" />를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | <paramref name="loadOptions" />에 지정된 파일 형식 세부 정보입니다. <paramref name="loadOptions" />는 null일 수 있습니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 이 설명자에 의해 생성된 이미지 로더가 스트림에서 이미지를 읽을 수 있으면 <c>true</c>, 그렇지 않으면 <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

새 로더 인스턴스를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | 새 로더 인스턴스. |


