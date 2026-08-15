---
title: "IImageExporterDescriptor 클래스"
type: docs
weight: 1800
url: /ko/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 지원되는 형식을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | 이미지 내보내기가 저장 옵션에 지정된 이미지 형식으로 지정된 이미지를 내보낼 수 있는지 여부를 결정합니다. |
| [create_instance()](#create_instance__2) | 새 내보내기 인스턴스를 생성합니다. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

이미지 내보내기가 저장 옵션에 지정된 이미지 형식으로 지정된 이미지를 내보낼 수 있는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 내보낼 이미지. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션 기본. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>True</c>이면 이 설명자에 의해 생성된 내보내기가 지정된 이미지를 지정된 파일 형식으로 내보낼 수 있습니다; 그렇지 않으면 <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

새 내보내기 인스턴스를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | 새 내보내기 인스턴스. |


