---
title: "SmartResourceCreator 클래스"
type: docs
weight: 910
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/
---

**Summary:** Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartResourceCreator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [SmartResourceCreator()](#SmartResourceCreator__1) | 새 인스턴스를 초기화합니다 [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) 클래스. |
| [SmartResourceCreator(is_custom, has_comp_info)](#SmartResourceCreator_is_custom_has_comp_info_2) | 새 인스턴스를 초기화합니다 [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) 클래스. |
| [SmartResourceCreator(template)](#SmartResourceCreator_template_3) | 새 인스턴스를 초기화합니다 [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) 클래스<br/>            주어진 템플릿과 함께. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [generate_placed_resource()](#generate_placed_resource__1) | 배치된 리소스를 생성합니다. |
| [generate_smart_embedded_resource()](#generate_smart_embedded_resource__2) | 임베드된 스마트 오브젝트 리소스를 생성합니다. |
| [generate_smart_external_resource()](#generate_smart_external_resource__3) | 외부 스마트 오브젝트 리소스를 생성합니다. |


### Constructor: SmartResourceCreator() {#SmartResourceCreator__1}


```
 SmartResourceCreator() 
```

새 인스턴스를 초기화합니다 [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) 클래스.

### Constructor: SmartResourceCreator(is_custom, has_comp_info) {#SmartResourceCreator_is_custom_has_comp_info_2}


```
 SmartResourceCreator(is_custom, has_comp_info) 
```

새 인스턴스를 초기화합니다 [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| is_custom | bool | 설정된 경우 <c>true</c> [is custom]. |
| has_comp_info | bool | 설정된 경우 <c>true</c> [has comp information]. |

### Constructor: SmartResourceCreator(template) {#SmartResourceCreator_template_3}


```
 SmartResourceCreator(template) 
```

새 인스턴스를 초기화합니다 [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) 클래스<br/>            주어진 템플릿과 함께.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| template | [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource) | 스마트 오브젝트 리소스 템플릿. |

### Method: generate_placed_resource() {#generate_placed_resource__1}


```
 generate_placed_resource() 
```

배치된 리소스를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource) | 생성된 [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) 인스턴스. |


### Method: generate_smart_embedded_resource() {#generate_smart_embedded_resource__2}


```
 generate_smart_embedded_resource() 
```

임베드된 스마트 오브젝트 리소스를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource) | 생성된 [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) 인스턴스. |


### Method: generate_smart_external_resource() {#generate_smart_external_resource__3}


```
 generate_smart_external_resource() 
```

외부 스마트 오브젝트 리소스를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource) | 생성된 [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) 인스턴스. |


