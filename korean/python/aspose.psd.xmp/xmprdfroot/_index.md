---
title: "XmpRdfRoot 클래스"
type: docs
weight: 460
url: /ko/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | XmpRdfRoot 클래스의 새 인스턴스를 초기화합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | 속성을 추가합니다. |
| clear_attributes() | 모든 속성을 제거합니다. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | 속성을 가져옵니다. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | 특정 접두사로 네임스페이스 URI를 가져옵니다. 접두사는 xmlns 없이 시작될 수 있습니다. |
| [get_xml_value()](#get_xml_value__4) | xmp 값을 XML 표현으로 변환합니다. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | 접두사로 네임스페이스 URI를 추가합니다. 접두사는 xmlns 없이 시작될 수 있습니다. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

XmpRdfRoot 클래스의 새 인스턴스를 초기화합니다.

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


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

특정 접두사로 네임스페이스 URI를 가져옵니다. 접두사는 xmlns 없이 시작될 수 있습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 접두사 | 문자열 | 접두사. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 패키지 스키마 URI를 반환합니다. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

xmp 값을 XML 표현으로 변환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | XMP 값을 XML 문자열로 변환하여 반환합니다. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

접두사로 네임스페이스 URI를 추가합니다. 접두사는 xmlns 없이 시작될 수 있습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 접두사 | 문자열 | 접두사. |
| namespace_uri | 문자열 | 패키지 스키마 URI. |

