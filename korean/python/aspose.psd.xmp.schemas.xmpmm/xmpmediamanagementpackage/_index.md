---
title: "XmpMediaManagementPackage 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | XmpMediaManagementPackage 클래스의 새 인스턴스를 초기화합니다 |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | derived from을 설정합니다. |
| [set_document_id(guid)](#set_document_id_guid_6) | 문서 식별자를 설정합니다. |
| [set_document_id(guid)](#set_document_id_guid_7) | 문서 식별자를 설정합니다. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | 인스턴스 ID를 설정합니다. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | 인스턴스 ID를 설정합니다. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | 원본 문서 ID를 설정합니다. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | 원본 문서 ID를 설정합니다. |
| [set_value(key, value)](#set_value_key_value_12) | 값을 설정합니다. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | XMP 유형 값을 설정합니다. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

XmpMediaManagementPackage 클래스의 새 인스턴스를 초기화합니다

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

derived from을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | 리소스 참조. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

문서 식별자를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| guid | Guid | 고유 식별자. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

문서 식별자를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| guid | 문자열 | 고유 식별자. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

인스턴스 ID를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| guid | Guid | 고유 식별자. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

인스턴스 ID를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| guid | 문자열 | 고유 식별자. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

원본 문서 ID를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| guid | Guid | 고유 식별자. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

원본 문서 ID를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| guid | 문자열 | 고유 식별자. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 추가된 값과 식별되는 키의 문자열 표현입니다. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 추가할 값. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

XMP 유형 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 설정된 값으로 식별되는 키의 문자열 표현. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 설정할 값. |

