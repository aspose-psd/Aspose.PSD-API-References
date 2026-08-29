---
title: "XmpPackageBaseCollection Sınıfı"
type: docs
weight: 440
url: /tr/python-net/aspose.psd.xmp/xmppackagebasecollection/
---

**Summary:** Represents collection of [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/).

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackageBaseCollection

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection__1) | XmpPackageBaseCollection sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| sayım | int | r | Koleksiyondaki öğe sayısını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(package)](#add_package_1) | Yeni bir [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) örneği ekler. |
| clear() | Koleksiyon içindeki tüm [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) öğelerini temizler. |
| [get_package(namespace_uri)](#get_package_namespace_uri_2) | NamespaceURI'sine göre [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) alır. |
| [get_packages()](#get_packages__3) | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) dizisini al. |
| [remove(package)](#remove_package_4) | Belirtilen XMP paketini kaldırır. |


### Constructor: XmpPackageBaseCollection() {#XmpPackageBaseCollection__1}


```
 XmpPackageBaseCollection() 
```

XmpPackageBaseCollection sınıfının yeni bir örneğini başlatır

### Method: add(package) {#add_package_1}


```
 add(package) 
```

Yeni bir [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) örneği ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Eklenecek XMP paketi. |

### Method: get_package(namespace_uri) {#get_package_namespace_uri_2}


```
 get_package(namespace_uri) 
```

NamespaceURI'sine göre [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| namespace_uri | string | Paketin alınacağı ad alanı URI'si. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Belirtilen ad alanı URI'si için XMP paketini döndürür. |


### Method: get_packages() {#get_packages__3}


```
 get_packages() 
```

[XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) dizisini al.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | XMP paketlerinin bir dizisini döndürür. |


### Method: remove(package) {#remove_package_4}


```
 remove(package) 
```

Belirtilen XMP paketini kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Kaldırılacak XMP paketi. |

