---
title: "XmpArray"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 XmpPackage 中的 Xmp Array。"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

表示 XmpPackage 中的 Xmp Array。todo: 数组可能包含复杂数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | 初始化 XmpArray 类的新实例。 |
| [XmpArray(int type)](#XmpArray-int-) | 初始化 XmpArray 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | 添加新项。 |
| [addItem(String item)](#addItem-java.lang.String-) | 添加新项。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | 获取位于 [XmpArray](../../com.aspose.psd.xmp/xmparray) 内的值数组。 |
| [getValues()](#getValues--) | 获取位于 XmpArray 内的值数组。 |
| [getXmlValue()](#getXmlValue--) | 将 XMP 值转换为 XML 表示。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回 一个  System.String  表示此实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


初始化 XmpArray 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | 数组的类型。 |
| items | java.lang.String[] | 项目列表。 |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


初始化 XmpArray 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | 数组的类型。 |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


添加新项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 要添加到项目列表的元素。 |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


添加新项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 项 | java.lang.String | 要添加到项目列表的项。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements_internalized() {#getElements-internalized--}
```
public final XmpPackage[] getElements_internalized()
```


获取位于 [XmpArray](../../com.aspose.psd.xmp/xmparray) 内的值数组。

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


获取位于 XmpArray 内的值数组。

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 XMP 值转换为 XML 表示。

**Returns:**
java.lang.String - 返回转换为 XML 表示的 XMP 值。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


返回 一个  System.String  表示此实例。

**Returns:**
java.lang.String - 一个  System.String  表示此实例。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

