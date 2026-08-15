---
title: "XmpDate 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.psd.xmp.types.basic](/psd/python-net/aspose.psd.xmp.types.basic/)

**Full Name:** aspose.psd.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | 새 인스턴스를 초기화합니다 [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) 클래스. |
| [XmpDate(date_time)](#XmpDate_date_time_2) | 새 인스턴스를 초기화합니다 [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | 문자열 | r | ISO 8601 (라운드트립) 형식 문자열. |
| 형식 | 문자열 | r | 현재 값에 대한 형식 문자열을 가져옵니다. |
| 값 | datetime | r/w | 날짜 값을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP 형식으로 포함된 문자열 값을 반환합니다. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

새 인스턴스를 초기화합니다 [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| date_string | 문자열 | 날짜의 문자열 표현입니다. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

새 인스턴스를 초기화합니다 [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| date_time | datetime | ISO RFC 8601 형식의 하위 집합을 사용하여 표현되는 날짜-시간 값입니다. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP 형식으로 포함된 문자열 값을 반환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | XMP 형식으로 포함된 문자열 값을 반환합니다. |


