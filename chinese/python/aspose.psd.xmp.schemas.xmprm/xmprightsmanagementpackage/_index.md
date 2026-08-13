---
title: "XmpRightsManagementPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | 初始化 XmpRightsManagementPackage 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | 字符串 | r | 获取命名空间 URI。 |
| 前缀 | 字符串 | r | 获取前缀。 |
| xml_namespace | 字符串 | r | 获取 XML 命名空间。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 添加字符串属性。 |
| clear() | 清除此实例。 |
| [contains_key(key)](#contains_key_key_2) | 确定指定的键是否包含键。 |
| [get_xml_value()](#get_xml_value__3) | 将 XMP 值转换为 XML 表示形式。 |
| [remove(key)](#remove_key_4) | 删除具有指定键的值。 |
| [set_certificate(certificate)](#set_certificate_certificate_5) | 设置证书。 |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | 标记为受权管理内容 |
| [set_owners(owners)](#set_owners_owners_7) | 设置所有者。 |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | 设置使用条款。 |
| [set_value(key, value)](#set_value_key_value_9) | 设置值。 |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | 设置 Web 声明。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | 设置 XMP 类型值。 |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

初始化 XmpRightsManagementPackage 类的新实例。

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

添加字符串属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | 字符串 | 字符串值。 |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

确定指定的键是否包含键。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 要检查的键。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的键包含键，则返回 true。 |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示形式。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 返回转换为 XML 表示形式的 XMP 值。 |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

删除具有指定键的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已删除值的 key 的字符串表示形式。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果具有指定键的值已被删除，则返回 true。 |


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

设置证书。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 证书 | 字符串 | 该证书。 |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

标记为受权管理内容

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | bool | 如果设置为 <c>true</c>，则此为受权管理资源。 |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

设置所有者。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 所有者 | 字符串 | 所有者。 |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

设置使用条款。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | 使用条款。 |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 要添加的值。 |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

设置 Web 声明。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| web_statement_url | 字符串 | 网页声明 URL。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 键的字符串表示形式，该键与设置的值关联。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 要设置的值。 |

