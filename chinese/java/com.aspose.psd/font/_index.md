---
title: "Font"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义文本的特定格式，包括字体、大小和样式属性。"
type: docs
weight: 46
url: /zh/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

定义文本的特定格式，包括字体、大小和样式属性。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | 初始化一个新的  com.aspose.psd.Font ，它使用指定的现有  com.aspose.psd.Font  和  com.aspose.psd.FontStyle  枚举。 |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | 使用指定的大小初始化一个新的  com.aspose.psd.Font 。 |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | 使用指定的大小和样式初始化一个新的  com.aspose.psd.Font 。 |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | 使用指定的大小、样式、单位和字符集初始化一个新的  com.aspose.psd.Font 。 |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | 使用指定的大小、样式和单位初始化一个新的  com.aspose.psd.Font 。 |
## Methods

| Method | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此 Font 的精确深拷贝。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指示指定的对象是否为 com.aspose.psd.Font 且其属性值与此 com.aspose.psd.Font 相同。 |
| [getBold()](#getBold--) | 获取一个值，指示此 Font 是否为粗体。 |
| [getCharacterSet()](#getCharacterSet--) | 获取一个字节值，指定此 Font 使用的字符集。 |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | 获取一个值，指示此 Font 是否为斜体。 |
| [getName()](#getName--) | 获取此 Font 的字体名称。 |
| [getSize()](#getSize--) | 获取此 Font 的 em 大小，单位由 P:Aspose.Imaging.Font.Unit 属性指定。 |
| [getStrikeout()](#getStrikeout--) | 获取一个值，指示此 Font 是否在字体上指定水平划线。 |
| [getStyle()](#getStyle--) | 获取此 Font 的样式信息。 |
| [getUnderline()](#getUnderline--) | 获取一个值，指示此 Font 是否带下划线。 |
| [getUnit()](#getUnit--) | 获取此 Font 的度量单位。 |
| [hashCode()](#hashCode--) | 获取此 com.aspose.psd.Font 的哈希码。 |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | 使用指定的大小和单位初始化一个新的 com.aspose.psd.Font。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回此 com.aspose.psd.Font 的可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


初始化一个新的  com.aspose.psd.Font ，它使用指定的现有  com.aspose.psd.Font  和  com.aspose.psd.FontStyle  枚举。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | 用于创建新 com.aspose.psd.Font 的现有 com.aspose.psd.Font。 |
| newStyle | int | 要应用于新 com.aspose.psd.Font 的 com.aspose.psd.FontStyle。com.aspose.psd.FontStyle 枚举的多个值可以使用 OR 运算符组合。 |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


使用指定的大小初始化一个新的 com.aspose.psd.Font。字符集设置为 F:Aspose.Imaging.CharacterSet.Default，图形单位设置为 F:Aspose.Imaging.GraphicsUnit.Point，字体样式设置为 F:Aspose.Imaging.FontStyle.Regular。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小（以点为单位）。 |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


使用指定的大小和样式初始化一个新的 com.aspose.psd.Font。字符集设置为 F:Aspose.Imaging.CharacterSet.Default，图形单位设置为 F:Aspose.Imaging.GraphicsUnit.Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小（以点为单位）。 |
| style | int | 新字体的 com.aspose.psd.FontStyle。 |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


使用指定的大小、样式、单位和字符集初始化一个新的  com.aspose.psd.Font 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小，单位由 unit 参数指定。 |
| style | int | 新字体的 com.aspose.psd.FontStyle。 |
| 单位 | int | 新字体的  com.aspose.psd.GraphicsUnit  。 |
| 字符集 | int | 用于此字体的字符集。 |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


使用指定的大小、样式和单位初始化一个新的  com.aspose.psd.Font 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小，单位由 unit 参数指定。 |
| style | int | 新字体的 com.aspose.psd.FontStyle。 |
| 单位 | int | 新字体的  com.aspose.psd.GraphicsUnit  。 |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


创建此 Font 的精确深拷贝。

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指示指定的对象是否为 com.aspose.psd.Font 且其属性值与此 com.aspose.psd.Font 相同。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果  obj  参数是一个  com.aspose.psd.Font  并且其属性值与此  com.aspose.psd.Font 相同，则为 True；否则为 false。
### getBold() {#getBold--}
```
public boolean getBold()
```


获取一个值，指示此 Font 是否为粗体。

**Returns:**
boolean - 如果此  Font  为粗体，则为 True；否则为 false。
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


获取一个字节值，指定此 Font 使用的字符集。

**Returns:**
int - 此  Font  使用的字符集。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


获取一个值，指示此 Font 是否为斜体。

**Returns:**
boolean - 如果此  Font  为斜体，则为 True；否则为 false。
### getName() {#getName--}
```
public String getName()
```


获取此 Font 的字体名称。

**Returns:**
java.lang.String - 此  Font  的字体名称的字符串表示。
### getSize() {#getSize--}
```
public float getSize()
```


获取此 Font 的 em 大小，单位由 P:Aspose.Imaging.Font.Unit 属性指定。

**Returns:**
float - 此  Font  的 em 大小。
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


获取一个值，指示此 Font 是否在字体上指定水平划线。

**Returns:**
boolean - 如果此  Font  有水平划线，则为 True；否则为 false。
### getStyle() {#getStyle--}
```
public int getStyle()
```


获取此 Font 的样式信息。

**Returns:**
int - 包含此  Font  的样式信息的  FontStyle  枚举。
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


获取一个值，指示此 Font 是否带下划线。

**Returns:**
boolean - 如果此  Font  为下划线，则为 True；否则为 false。
### getUnit() {#getUnit--}
```
public int getUnit()
```


获取此 Font 的度量单位。

**Returns:**
int - 表示此  Font  的度量单位的  GraphicsUnit  。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此 com.aspose.psd.Font 的哈希码。

**Returns:**
int - 此  com.aspose.psd.Font  的哈希码。
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


使用指定的大小和单位初始化一个新的  com.aspose.psd.Font 。字符集设置为  F:Aspose.Imaging.CharacterSet.Default ，样式设置为  F:Aspose.Imaging.FontStyle.Regular 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小，单位由 unit 参数指定。 |
| 单位 | int | 新字体的  com.aspose.psd.GraphicsUnit  。 |

**Returns:**
[Font](../../com.aspose.psd/font)
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


返回此 com.aspose.psd.Font 的可读字符串表示。

**Returns:**
java.lang.String - 表示此  com.aspose.psd.Font  的字符串。
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

