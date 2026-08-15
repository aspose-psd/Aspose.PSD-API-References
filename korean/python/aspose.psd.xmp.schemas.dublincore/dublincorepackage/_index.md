---
title: "DublinCorePackage 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Summary:** Represents Dublic Core schema.

**Module:** [aspose.psd.xmp.schemas.dublincore](/psd/python-net/aspose.psd.xmp.schemas.dublincore/)

**Full Name:** aspose.psd.xmp.schemas.dublincore.DublinCorePackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [DublinCorePackage()](#DublinCorePackage__1) | DublinCorePackage 클래스의 새 인스턴스를 초기화합니다 |
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
| [set_author(author)](#set_author_author_5) | 저자를 추가합니다. |
| [set_author(author)](#set_author_author_6) | 저자를 추가합니다. |
| [set_description(desc)](#set_description_desc_7) | 설명을 추가합니다. |
| [set_description(desc)](#set_description_desc_8) | 설명을 추가합니다. |
| [set_publisher(publisher)](#set_publisher_publisher_9) | 출판사를 추가합니다. |
| [set_publisher(publisher)](#set_publisher_publisher_10) | 출판사를 추가합니다. |
| [set_subject(subject)](#set_subject_subject_11) | 주제를 추가합니다. |
| [set_subject(subject)](#set_subject_subject_12) | 주제를 추가합니다. |
| [set_title(title)](#set_title_title_13) | Dublin Core 제목을 추가합니다. |
| [set_title(title)](#set_title_title_14) | Dublin Core 제목을 추가합니다. |
| [set_value(key, value)](#set_value_key_value_15) | 값을 설정합니다. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | XMP 유형 값을 설정합니다. |


### Constructor: DublinCorePackage() {#DublinCorePackage__1}


```
 DublinCorePackage() 
```

DublinCorePackage 클래스의 새 인스턴스를 초기화합니다

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


### Method: set_author(author) {#set_author_author_5}


```
 set_author(author) 
```

저자를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 저자 | 문자열 | 저자입니다. |

### Method: set_author(author) {#set_author_author_6}


```
 set_author(author) 
```

저자를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 저자 | 문자열 | 저자입니다. |

### Method: set_description(desc) {#set_description_desc_7}


```
 set_description(desc) 
```

설명을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 설명 | 문자열 | 설명입니다. |

### Method: set_description(desc) {#set_description_desc_8}


```
 set_description(desc) 
```

설명을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| desc | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | 설명입니다. |

### Method: set_publisher(publisher) {#set_publisher_publisher_9}


```
 set_publisher(publisher) 
```

출판사를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 출판사 | 문자열 | 출판사입니다. |

### Method: set_publisher(publisher) {#set_publisher_publisher_10}


```
 set_publisher(publisher) 
```

출판사를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 출판사 | 문자열 | 출판사입니다. |

### Method: set_subject(subject) {#set_subject_subject_11}


```
 set_subject(subject) 
```

주제를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 주제 | 문자열 | 주제입니다. |

### Method: set_subject(subject) {#set_subject_subject_12}


```
 set_subject(subject) 
```

주제를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 주제 | 문자열 | 주제입니다. |

### Method: set_title(title) {#set_title_title_13}


```
 set_title(title) 
```

Dublin Core 제목을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| title | 문자열 | 제목입니다. |

### Method: set_title(title) {#set_title_title_14}


```
 set_title(title) 
```

Dublin Core 제목을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| title | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | 제목입니다. |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 추가된 값과 식별되는 키의 문자열 표현입니다. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 추가할 값. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

XMP 유형 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 설정된 값으로 식별되는 키의 문자열 표현. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 설정할 값. |

