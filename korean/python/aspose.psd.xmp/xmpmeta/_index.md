---
title: "XmpMeta 클래스"
type: docs
weight: 410
url: /ko/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) 클래스의 새 인스턴스를 초기화합니다. |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | 문자열 | r/w | Adobe Xmp 툴킷 버전을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | 속성을 추가합니다. |
| clear_attributes() | 모든 속성을 제거합니다. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | 속성을 가져옵니다. |
| [get_xml_value()](#get_xml_value__3) | XMP 값을 XML 표현으로 변환합니다. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

[XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) 클래스의 새 인스턴스를 초기화합니다.

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

[XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| toolkit_version | 문자열 | Adobe XMP 툴킷 버전입니다. |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

속성을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| attribute | 문자열 | 속성입니다. |
| 값 | 문자열 | 값입니다. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

속성을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| attribute | 문자열 | 속성입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 지정된 속성 이름에 대한 속성을 반환합니다. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP 값을 XML 표현으로 변환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | XMP 값을 XML 표현으로 변환한 결과를 반환합니다. |


