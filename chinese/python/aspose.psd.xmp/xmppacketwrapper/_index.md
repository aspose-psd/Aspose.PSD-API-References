---
title: "XmpPacketWrapper 类"
type: docs
weight: 450
url: /zh/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | 初始化 [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) 类的新实例。 |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | 初始化 [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | 获取标题处理指令。 |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | 获取 XMP 元数据。可选。 |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | 获取 XMP 中的 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) 数组。 |
| packages_count | int | r | 获取 XMP 结构中包的数量。 |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | 获取尾部处理指令。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | 添加该包。 |
| clear_packages() | 移除 XMP 中的所有 [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/)。 |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | 确定包是否存在于 XMP 包装器中。 |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | 通过命名空间 URI 获取包。 |
| [remove_package(package)](#remove_package_package_4) | 移除 XMP 包。 |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

初始化 [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) 类的新实例。

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

初始化 [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | 处理指令的 XMP 标头。 |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | 处理指令的 XMP 尾部。 |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | XMP 元数据。 |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

添加该包。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 该包。 |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

确定包是否存在于 XMP 包装器中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| namespace_uri | 字符串 | 包的模式 URI。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果在 XMP 包装器中存在具有指定命名空间 URI 的包，则返回 true。 |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

通过命名空间 URI 获取包。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| namespace_uri | 字符串 | 包的模式 URI。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 返回指定命名空间 URI 的 XMP 包。 |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

移除 XMP 包。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | 该包。 |

