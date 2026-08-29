---
title: "Font"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 XMP 字体。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

表示 XMP 字体。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Font()](#Font--) | 初始化 Font 类的新实例。 |
| [Font(String fontFamily)](#Font-java.lang.String-) | 初始化 Font 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 添加指定的键。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | 获取或设置组成复合字体的字体文件名数组。 |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | 获取或设置字体面。 |
| [getFontFamily()](#getFontFamily--) | 获取或设置字体族。 |
| [getFontFileName()](#getFontFileName--) | 获取或设置不含完整路径的字体文件名。 |
| [getFontName()](#getFontName--) | 获取或设置 PostScript 字体名称。 |
| [getFontType()](#getFontType--) | 获取或设置字体类型。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取默认命名空间 URI。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getVersion()](#getVersion--) | 获取或设置字体版本。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | 获取或设置指示此字体是否为复合字体的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | 获取或设置组成复合字体的字体文件名数组。 |
| [setComposite(boolean value)](#setComposite-boolean-) | 获取或设置指示此字体是否为复合字体的值。 |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | 获取或设置字体面。 |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | 获取或设置字体族。 |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | 获取或设置不含完整路径的字体文件名。 |
| [setFontName(String value)](#setFontName-java.lang.String-) | 获取或设置 PostScript 字体名称。 |
| [setFontType(String value)](#setFontType-java.lang.String-) | 获取或设置字体类型。 |
| [setVersion(String value)](#setVersion-java.lang.String-) | 获取或设置字体版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


初始化 Font 类的新实例。

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


初始化 Font 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontFamily | java.lang.String | 字体族。 |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


添加指定的键。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | key 的字符串表示形式，用于标识已添加的值。 |
| 值 | java.lang.Object | 要添加到的值。 |

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
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


获取或设置组成复合字体的字体文件名数组。

值：组成复合字体的字体文件名数组。

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


获取或设置字体面。

值：字体面。

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


获取或设置字体族。

值：字体族。

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


获取或设置不含完整路径的字体文件名。

值：不含完整路径的字体文件名。

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


获取或设置 PostScript 字体名称。

值：PostScript 字体名称。

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


获取或设置字体类型。

TrueType、Type 1、Open Type 等。值：字体类型。

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取默认命名空间 URI。

**Returns:**
java.lang.String - 默认的命名空间 URI。
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

**Returns:**
java.lang.String - 前缀。
### getVersion() {#getVersion--}
```
public String getVersion()
```


获取或设置字体版本。

/version 用于 Type1 字体的 nameId 5，适用于 Apple True Type 和 OpenType；/CIDFontVersion 用于 CID 字体；位图字体使用空字符串。值：字体版本。

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式的字符串值。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


获取或设置指示此字体是否为复合字体的值。

值：如果此字体是复合的，则为 true；否则为 false。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


获取或设置组成复合字体的字体文件名数组。

值：组成复合字体的字体文件名数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


获取或设置指示此字体是否为复合字体的值。

值：如果此字体是复合的，则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


获取或设置字体面。

值：字体面。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


获取或设置字体族。

值：字体族。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


获取或设置不含完整路径的字体文件名。

值：不含完整路径的字体文件名。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


获取或设置 PostScript 字体名称。

值：PostScript 字体名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


获取或设置字体类型。

TrueType、Type 1、Open Type 等。值：字体类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


获取或设置字体版本。

/version 用于 Type1 字体的 nameId 5，适用于 Apple True Type 和 OpenType；/CIDFontVersion 用于 CID 字体；位图字体使用空字符串。值：字体版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

