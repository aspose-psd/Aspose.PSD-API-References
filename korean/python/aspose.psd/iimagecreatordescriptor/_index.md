---
title: "IImageCreatorDescriptor 클래스"
type: docs
weight: 1770
url: /ko/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 지원되는 형식을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | 이미지 생성기가 <paramref name="imageOptions" />을 사용하여 새 이미지를 만들 수 있는지 여부를 결정합니다. |
| [create_instance()](#create_instance__2) | 새 생성자 인스턴스를 생성합니다. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

이미지 생성기가 <paramref name="imageOptions" />을 사용하여 새 이미지를 만들 수 있는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이미지 옵션. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>True</c>는 이 설명자에 의해 생성된 이미지 생성기가 지정된 <paramref name="imageOptions" />을 사용하여 이미지 데이터를 생성할 수 있는 경우; 그렇지 않으면 <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

새 생성자 인스턴스를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | 새 생성자 인스턴스. |


