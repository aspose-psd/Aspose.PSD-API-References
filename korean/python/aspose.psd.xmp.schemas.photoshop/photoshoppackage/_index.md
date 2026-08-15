---
title: "PhotoshopPackage 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Summary:** Represents Adobe Photoshop namespace.

**Module:** [aspose.psd.xmp.schemas.photoshop](/psd/python-net/aspose.psd.xmp.schemas.photoshop/)

**Full Name:** aspose.psd.xmp.schemas.photoshop.PhotoshopPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PhotoshopPackage()](#PhotoshopPackage__1) | PhotoshopPackage 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| URGENCY_MAX [static] | int | r | 긴급도 최대값. |
| URGENCY_MIN [static] | int | r | 긴급도 최소값. |
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
| [set_authors_position(authors_position)](#set_authors_position_authors_position_5) | 작성자 위치를 설정합니다. |
| [set_caption_writer(caption_writer)](#set_caption_writer_caption_writer_6) | 캡션 작성자를 설정합니다. |
| [set_category(category)](#set_category_category_7) | 카테고리를 설정합니다. |
| [set_city(city)](#set_city_city_8) | 도시를 설정합니다. |
| [set_color_mode(color_mode)](#set_color_mode_color_mode_9) | 색상 모드를 설정합니다. |
| [set_country(country)](#set_country_country_10) | 국가를 설정합니다. |
| [set_created_date(created_date)](#set_created_date_created_date_11) | 생성 날짜를 설정합니다. |
| [set_credit(credit)](#set_credit_credit_12) | 크레딧을 설정합니다. |
| [set_document_ancestors(ancestors)](#set_document_ancestors_ancestors_13) | 문서 조상을 설정합니다. |
| [set_headline(headline)](#set_headline_headline_14) | 헤드라인을 설정합니다. |
| [set_history(history)](#set_history_history_15) | 히스토리를 설정합니다. |
| [set_icc_profile(icc_profile)](#set_icc_profile_icc_profile_16) | ICC 프로파일을 설정합니다. |
| [set_instructions(instructions)](#set_instructions_instructions_17) | 지침을 설정합니다. |
| [set_source(source)](#set_source_source_18) | 소스를 설정합니다. |
| [set_state(state)](#set_state_state_19) | 주를 설정합니다. |
| [set_supplemental_categories(supplemental_categories)](#set_supplemental_categories_supplemental_categories_20) | 보조 카테고리를 설정합니다. |
| [set_transmission_reference(transmission_reference)](#set_transmission_reference_transmission_reference_21) | 전송 참조를 설정합니다. |
| [set_urgency(urgency)](#set_urgency_urgency_22) | 긴급도를 설정합니다. |
| [set_value(key, value)](#set_value_key_value_23) | 값을 설정합니다. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | XMP 유형 값을 설정합니다. |


### Constructor: PhotoshopPackage() {#PhotoshopPackage__1}


```
 PhotoshopPackage() 
```

PhotoshopPackage 클래스의 새 인스턴스를 초기화합니다

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


### Method: set_authors_position(authors_position) {#set_authors_position_authors_position_5}


```
 set_authors_position(authors_position) 
```

작성자 위치를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| authors_position | 문자열 | 저자의 위치. |

### Method: set_caption_writer(caption_writer) {#set_caption_writer_caption_writer_6}


```
 set_caption_writer(caption_writer) 
```

캡션 작성자를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| caption_writer | 문자열 | 캡션 작성자. |

### Method: set_category(category) {#set_category_category_7}


```
 set_category(category) 
```

카테고리를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| category | 문자열 | 카테고리. |

### Method: set_city(city) {#set_city_city_8}


```
 set_city(city) 
```

도시를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| city | 문자열 | 도시 이름. |

### Method: set_color_mode(color_mode) {#set_color_mode_color_mode_9}


```
 set_color_mode(color_mode) 
```

색상 모드를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | 색상 모드. |

### Method: set_country(country) {#set_country_country_10}


```
 set_country(country) 
```

국가를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| country | 문자열 | 국가. |

### Method: set_created_date(created_date) {#set_created_date_created_date_11}


```
 set_created_date(created_date) 
```

생성 날짜를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| created_date | datetime | 생성 날짜. |

### Method: set_credit(credit) {#set_credit_credit_12}


```
 set_credit(credit) 
```

크레딧을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| credit | 문자열 | 크레딧. |

### Method: set_document_ancestors(ancestors) {#set_document_ancestors_ancestors_13}


```
 set_document_ancestors(ancestors) 
```

문서 조상을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| ancestors | 문자열 | 조상들. |

### Method: set_headline(headline) {#set_headline_headline_14}


```
 set_headline(headline) 
```

헤드라인을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| headline | 문자열 | 헤드라인. |

### Method: set_history(history) {#set_history_history_15}


```
 set_history(history) 
```

히스토리를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| history | 문자열 | 역사. |

### Method: set_icc_profile(icc_profile) {#set_icc_profile_icc_profile_16}


```
 set_icc_profile(icc_profile) 
```

ICC 프로파일을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| icc_profile | 문자열 | ICC 프로필. |

### Method: set_instructions(instructions) {#set_instructions_instructions_17}


```
 set_instructions(instructions) 
```

지침을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| instructions | 문자열 | 지침. |

### Method: set_source(source) {#set_source_source_18}


```
 set_source(source) 
```

소스를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source | 문자열 | 출처. |

### Method: set_state(state) {#set_state_state_19}


```
 set_state(state) 
```

주를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| state | 문자열 | 상태. |

### Method: set_supplemental_categories(supplemental_categories) {#set_supplemental_categories_supplemental_categories_20}


```
 set_supplemental_categories(supplemental_categories) 
```

보조 카테고리를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| supplemental_categories | 문자열 | 보조 카테고리. |

### Method: set_transmission_reference(transmission_reference) {#set_transmission_reference_transmission_reference_21}


```
 set_transmission_reference(transmission_reference) 
```

전송 참조를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| transmission_reference | 문자열 | 전송 참조. |

### Method: set_urgency(urgency) {#set_urgency_urgency_22}


```
 set_urgency(urgency) 
```

긴급도를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| urgency | int | 긴급도. |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 추가된 값과 식별되는 키의 문자열 표현입니다. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 추가할 값. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

XMP 유형 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 키 | 문자열 | 설정된 값으로 식별되는 키의 문자열 표현. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 설정할 값. |

