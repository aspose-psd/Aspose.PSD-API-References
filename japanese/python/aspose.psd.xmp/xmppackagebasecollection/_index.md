---
title: "XmpPackageBaseCollection クラス"
type: docs
weight: 440
url: /ja/python-net/aspose.psd.xmp/xmppackagebasecollection/
---

**Summary:** Represents collection of [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/).

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackageBaseCollection

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection__1) | XmpPackageBaseCollection クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| count | int | r | コレクション内の要素数を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(package)](#add_package_1) | 新しい [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) のインスタンスを追加します。 |
| clear() | コレクション内のすべての [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) をクリアします。 |
| [get_package(namespace_uri)](#get_package_namespace_uri_2) | namespaceURI によって [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) を取得します。 |
| [get_packages()](#get_packages__3) | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) の配列を取得します。 |
| [remove(package)](#remove_package_4) | 指定された XMP パッケージを削除します。 |


### Constructor: XmpPackageBaseCollection() {#XmpPackageBaseCollection__1}


```
 XmpPackageBaseCollection() 
```

XmpPackageBaseCollection クラスの新しいインスタンスを初期化します。

### Method: add(package) {#add_package_1}


```
 add(package) 
```

新しい [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) のインスタンスを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 追加する XMP パッケージ。 |

### Method: get_package(namespace_uri) {#get_package_namespace_uri_2}


```
 get_package(namespace_uri) 
```

namespaceURI によって [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| namespace_uri | string | パッケージを取得するための namespace URI。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 指定された namespace Uri の XMP パッケージを返します。 |


### Method: get_packages() {#get_packages__3}


```
 get_packages() 
```

[XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) の配列を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | XMP パッケージの配列を返します。 |


### Method: remove(package) {#remove_package_4}


```
 remove(package) 
```

指定された XMP パッケージを削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 削除する XMP パッケージ。 |

