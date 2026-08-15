---
title: "XmpPackageBaseCollection 클래스"
type: docs
weight: 440
url: /ko/python-net/aspose.psd.xmp/xmppackagebasecollection/
---

**Summary:** Represents collection of [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/).

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackageBaseCollection

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection__1) | XmpPackageBaseCollection 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| count | int | r | 컬렉션의 요소 수를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add(package)](#add_package_1) | 새 인스턴스의 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/)를 추가합니다. |
| clear() | 컬렉션 내부의 모든 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/)를 삭제합니다. |
| [get_package(namespace_uri)](#get_package_namespace_uri_2) | namespaceURI로 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/)를 가져옵니다. |
| [get_packages()](#get_packages__3) | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) 배열을 가져옵니다. |
| [remove(package)](#remove_package_4) | 지정된 XMP 패키지를 제거합니다. |


### Constructor: XmpPackageBaseCollection() {#XmpPackageBaseCollection__1}


```
 XmpPackageBaseCollection() 
```

XmpPackageBaseCollection 클래스의 새 인스턴스를 초기화합니다.

### Method: add(package) {#add_package_1}


```
 add(package) 
```

새 인스턴스의 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/)를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 추가할 XMP 패키지. |

### Method: get_package(namespace_uri) {#get_package_namespace_uri_2}


```
 get_package(namespace_uri) 
```

namespaceURI로 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/)를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| namespace_uri | 문자열 | 패키지를 가져올 namespace URI. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 지정된 namespace Uri에 대한 XMP 패키지를 반환합니다. |


### Method: get_packages() {#get_packages__3}


```
 get_packages() 
```

[XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) 배열을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | XMP 패키지 배열을 반환합니다. |


### Method: remove(package) {#remove_package_4}


```
 remove(package) 
```

지정된 XMP 패키지를 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 제거할 XMP 패키지. |

