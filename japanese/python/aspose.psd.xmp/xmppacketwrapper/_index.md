---
title: "XmpPacketWrapper クラス"
type: docs
weight: 450
url: /ja/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) クラスの新しいインスタンスを初期化します。 |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | ヘッダーの処理指示を取得します。 |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | XMP メタを取得します。オプションです。 |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | XMP 内の [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) 配列を取得します。 |
| packages_count | int | r | XMP 構造内のパッケージ数を取得します。 |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | トレーラーの処理指示を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | パッケージを追加します。 |
| clear_packages() | XMP 内のすべての [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) を削除します。 |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | パッケージが XMP ラッパーに存在するかどうかを判断します。 |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | 名前空間 URI によるパッケージを取得します。 |
| [remove_package(package)](#remove_package_package_4) | XMP パッケージを削除します。 |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

[XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) クラスの新しいインスタンスを初期化します。

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

[XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | 処理指示の XMP ヘッダーです。 |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | 処理指示の XMP トレーラーです。 |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | XMP メタデータです。 |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

パッケージを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | パッケージです。 |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

パッケージが XMP ラッパーに存在するかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| namespace_uri | string | パッケージ スキーマ URI。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された名前空間 URI を持つパッケージが XMP ラッパーに存在する場合、true を返します。 |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

名前空間 URI によるパッケージを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| namespace_uri | string | パッケージ スキーマ URIです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 指定された名前空間 URI の XMP パッケージを返します。 |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

XMP パッケージを削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | パッケージです。 |

