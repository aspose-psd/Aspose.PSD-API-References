---
title: "XmpPackage 클래스"
type: docs
weight: 430
url: /ko/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| namespace_uri | 문자열 | r | 네임스페이스 URI를 가져옵니다. |
| 접두사 | 문자열 | r | 접두사를 가져옵니다. |
| xml_namespace | 문자열 | r | XML 네임스페이스를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 값을 추가합니다. |
| clear() | 이 인스턴스를 초기화합니다. |
| [contains_key(key)](#contains_key_key_2) | 지정된 키가 키를 포함하는지 확인합니다. |
| [get_xml_value()](#get_xml_value__3) | XMP 값을 XML 표현으로 변환합니다. |
| [remove(key)](#remove_key_4) | 지정된 키에 해당하는 값을 제거합니다. |
| [set_value(key, value)](#set_value_key_value_5) | 값을 설정합니다. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | XMP 유형 값을 설정합니다. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

값을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 추가된 값과 식별되는 키의 문자열 표현입니다. |
| 값 | 문자열 | 추가할 값. |

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


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 추가된 값과 식별되는 키의 문자열 표현입니다. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 추가할 값. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

XMP 유형 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 설정된 값으로 식별되는 키의 문자열 표현. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 설정할 값. |

