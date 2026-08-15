---
title: "PdfPackage 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | PdfPackage 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| namespace_uri | 문자열 | r | 네임스페이스 URI를 가져옵니다. |
| 접두사 | 문자열 | r | 접두사를 가져옵니다. |
| xml_namespace | 문자열 | r | XML 네임스페이스를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 문자열 속성을 추가합니다. |
| clear() | 이 인스턴스를 초기화합니다. |
| [contains_key(key)](#contains_key_key_2) | 지정된 키가 키를 포함하는지 확인합니다. |
| [get_xml_value()](#get_xml_value__3) | XMP 값을 XML 표현으로 변환합니다. |
| [remove(key)](#remove_key_4) | 지정된 키에 해당하는 값을 제거합니다. |
| [set_keywords(keywords)](#set_keywords_keywords_5) | 키워드를 설정합니다. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | PDF 버전을 설정합니다. |
| [set_producer(producer)](#set_producer_producer_7) | Pdf를 만든 도구의 이름을 설정합니다. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | 트래핑을 설정합니다. |
| [set_value(key, value)](#set_value_key_value_9) | 값을 설정합니다. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | XMP 유형 값을 설정합니다. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

PdfPackage 클래스의 새 인스턴스를 초기화합니다.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

문자열 속성을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 추가된 값과 식별되는 키의 문자열 표현입니다. |
| 값 | 문자열 | 문자열 값입니다. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

지정된 키가 키를 포함하는지 확인합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 확인할 키입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 키가 키를 포함하면 true를 반환합니다. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP 값을 XML 표현으로 변환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | XMP 값을 XML 표현으로 변환한 결과를 반환합니다. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

지정된 키에 해당하는 값을 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 제거된 값과 식별되는 키의 문자열 표현입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 키의 값이 제거되면 true를 반환합니다. |


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

키워드를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키워드 | 문자열 | 키워드입니다. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

PDF 버전을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| version | 문자열 | Pdf 버전, 예: 1.0, 1.3 등. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Pdf를 만든 도구의 이름을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 제작자 | 문자열 | 제작자 이름입니다. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

트래핑을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| is_trapped | bool | <c>true</c> 로 설정된 경우 문서가 트래핑되었습니다. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 추가된 값과 식별되는 키의 문자열 표현입니다. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 추가할 값. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

XMP 유형 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 설정된 값으로 식별되는 키의 문자열 표현. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 설정할 값. |

