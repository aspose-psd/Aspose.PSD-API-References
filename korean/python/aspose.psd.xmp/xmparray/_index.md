---
title: "XmpArray 클래스"
type: docs
weight: 290
url: /ko/python-net/aspose.psd.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/). TODO: Array may contain complex data.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpArray

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [XmpArray(type)](#XmpArray_type_1) | [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 클래스의 새 인스턴스를 초기화합니다. |
| [XmpArray(type, items)](#XmpArray_type_items_2) | [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| values | string | r | [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 내부의 값 배열을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_item(item)](#add_item_item_1) | 새 항목을 추가합니다. |
| [get_xml_value()](#get_xml_value__2) | XMP 값을 XML 표현으로 변환합니다. |


### Constructor: XmpArray(type) {#XmpArray_type_1}


```
 XmpArray(type) 
```

[XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | 배열의 유형입니다. |

### Constructor: XmpArray(type, items) {#XmpArray_type_items_2}


```
 XmpArray(type, items) 
```

[XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | 배열의 유형입니다. |
| 항목들 | 문자열 | 항목 목록. |

### Method: add_item(item) {#add_item_item_1}


```
 add_item(item) 
```

새 항목을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 항목 | 문자열 | 항목 목록에 추가될 항목입니다. |

### Method: get_xml_value() {#get_xml_value__2}


```
 get_xml_value() 
```

XMP 값을 XML 표현으로 변환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | XMP 값을 XML 표현으로 변환한 결과를 반환합니다. |


