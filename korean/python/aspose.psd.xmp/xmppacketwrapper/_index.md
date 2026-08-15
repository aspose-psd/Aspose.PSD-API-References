---
title: "XmpPacketWrapper 클래스"
type: docs
weight: 450
url: /ko/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | 새 인스턴스를 초기화합니다 [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) 클래스. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | 새 인스턴스를 초기화합니다 [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | 헤더 처리 지시문을 가져옵니다. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | XMP 메타를 가져옵니다. 선택 사항. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | XMP 내부의 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) 배열을 가져옵니다. |
| packages_count | int | r | XMP 구조 내부의 패키지 수를 가져옵니다. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | 트레일러 처리 지시문을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | 패키지를 추가합니다. |
| clear_packages() | XMP 내부의 모든 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/)을 제거합니다. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | 패키지가 xmp 래퍼에 존재하는지 확인합니다. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | 네임스페이스 URI로 패키지를 가져옵니다. |
| [remove_package(package)](#remove_package_package_4) | XMP 패키지를 제거합니다. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

새 인스턴스를 초기화합니다 [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) 클래스.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

새 인스턴스를 초기화합니다 [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | 처리 지시문의 XMP 헤더. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | 처리 지시문의 XMP 트레일러. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | XMP 메타데이터. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

패키지를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 패키지. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

패키지가 xmp 래퍼에 존재하는지 확인합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| namespace_uri | 문자열 | 패키지 스키마 URI. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 네임스페이스 URI를 가진 패키지가 XMP 래퍼에 존재하면 true를 반환합니다. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

네임스페이스 URI로 패키지를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| namespace_uri | 문자열 | 패키지 스키마 URI. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 지정된 네임스페이스 URI에 대한 XMP 패키지를 반환합니다. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

XMP 패키지를 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 패키지. |

