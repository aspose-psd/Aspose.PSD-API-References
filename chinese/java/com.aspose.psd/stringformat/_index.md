---
title: "StringFormat"
second_title: "Aspose.PSD 的 Java API 参考"
description: "封装文本布局信息，例如对齐方向、制表位显示以及省略号插入、数字本地化替换和 OpenType 特性等操作。"
type: docs
weight: 106
url: /zh/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

封装文本布局信息（例如对齐、方向和制表位）、显示操作（例如省略号插入和本地数字替换）以及 OpenType 功能。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StringFormat()](#StringFormat--) | 初始化一个新的  com.aspose.psd.StringFormat  对象。 |
| [StringFormat(int options)](#StringFormat-int-) | 使用指定的  com.aspose.psd.StringFormatFlags  枚举和语言初始化一个新的  com.aspose.psd.StringFormat  对象。 |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | 从指定的现有  com.aspose.psd.StringFormat  对象初始化一个新的  com.aspose.psd.StringFormat  对象。 |
## Methods

| Method | 描述 |
| --- | --- |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [deepClone()](#deepClone--) | 创建此  com.aspose.psd.StringFormat  对象的深度克隆。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 获取垂直方向上的文本对齐信息。 |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | 获取在本地数字替换为西方数字时使用的语言。 |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | 获取用于数字替换的方法。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getFirstTabOffset()](#getFirstTabOffset--) | 获取文本行起始位置与第一个制表位之间的空格数。 |
| [getFormatFlags()](#getFormatFlags--) | 获取包含格式信息的  com.aspose.psd.StringFormatFlags  枚举。 |
| [getGenericDefault()](#getGenericDefault--) | 获取通用默认的  com.aspose.psd.StringFormat  对象。 |
| [getGenericTypographic()](#getGenericTypographic--) | 获取通用排版的  com.aspose.psd.StringFormat  对象。 |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | 获取此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.HotkeyPrefix  对象。 |
| [getLineAlignment()](#getLineAlignment--) | 获取水平方向上的行对齐方式。 |
| [getTabStops()](#getTabStops--) | 获取制表位之间距离的数组，单位由  P:Aspose.Imaging.getGraphics().PageUnit  属性指定。 |
| [getTrimming()](#getTrimming--) | 获取此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.StringTrimming  枚举。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | 设置垂直方向上的文本对齐信息。 |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | 设置在本地数字替换为西方数字时使用的语言。 |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | 设置用于数字替换的方法。 |
| [setFormatFlags(int value)](#setFormatFlags-int-) | 设置包含格式信息的  com.aspose.psd.StringFormatFlags  枚举。 |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | 设置此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.HotkeyPrefix  对象。 |
| [setLineAlignment(int value)](#setLineAlignment-int-) | 设置水平方向上的行对齐方式。 |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | 为此  com.aspose.psd.StringFormat  对象设置制表位。 |
| [setTrimming(int value)](#setTrimming-int-) | 设置此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.StringTrimming  枚举。 |
| [toString()](#toString--) | 将此  com.aspose.psd.StringFormat  对象转换为可读的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


初始化一个新的  com.aspose.psd.StringFormat  对象。

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


使用指定的  com.aspose.psd.StringFormatFlags  枚举和语言初始化一个新的  com.aspose.psd.StringFormat  对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 选项 | int | 用于新  com.aspose.psd.StringFormat  对象的  com.aspose.psd.StringFormatFlags  枚举。 |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


从指定的现有  com.aspose.psd.StringFormat  对象初始化一个新的  com.aspose.psd.StringFormat  对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | 用于初始化新  com.aspose.psd.StringFormat  对象的  com.aspose.psd.StringFormat  对象。 |

### close() {#close--}
```
public void close()
```


实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。此方法仅调用 dispose 方法。

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


创建此  com.aspose.psd.StringFormat  对象的深度克隆。

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


释放当前实例。

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


获取垂直方向上的文本对齐信息。

**Returns:**
int - 指定文本对齐信息的  com.aspose.psd.StringAlignment  枚举。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


获取在本地数字替换为西方数字时使用的语言。

**Returns:**
int - 一个国家语言支持 (NLS) 语言标识符，用于标识在本地数字替换为西方数字时将使用的语言。您可以将  System.Globalization.CultureInfo  对象的  P:System.Globalization.CultureInfo.LCID  属性作为 NLS 语言标识符传递。例如，假设您通过将字符串 "ar-EG" 传递给  System.Globalization.CultureInfo  构造函数来创建一个  System.Globalization.CultureInfo  对象。如果将该  System.Globalization.CultureInfo  对象的  P:System.Globalization.CultureInfo.LCID  属性与  com.aspose.psd.StringDigitSubstitute.Traditional  一起传递给  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute)  方法，则阿拉伯-印度数字将在显示时替换为西方数字。

为已废弃的方法 setDigitSubstitution 引入了 setter。
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


获取用于数字替换的方法。

**Returns:**
int - 指定如何替换因当前字体不支持而无法显示的字符串中字符的  com.aspose.psd.StringDigitSubstitute  枚举值。

为已废弃的方法 SetDigitSubstitution 引入了 setter。
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


获取文本行起始位置与第一个制表位之间的空格数。

**Returns:**
float - 第一个制表符偏移量。

为已移除的方法 GetTabStops 引入了该属性。
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


获取包含格式信息的  com.aspose.psd.StringFormatFlags  枚举。

**Returns:**
int - 包含格式信息的  com.aspose.psd.StringFormatFlags  枚举。
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


获取通用默认的  com.aspose.psd.StringFormat  对象。

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


获取通用排版的  com.aspose.psd.StringFormat  对象。

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


获取此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.HotkeyPrefix  对象。

**Returns:**
int - 此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.HotkeyPrefix  对象，默认值为  F:Aspose.Imaging.HotkeyPrefix.None 。
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


获取水平方向上的行对齐方式。

**Returns:**
int - 表示行对齐方式的  com.aspose.psd.StringAlignment  枚举。
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


获取制表位之间距离的数组，单位由  P:Aspose.Imaging.getGraphics().PageUnit  属性指定。

**Returns:**
float[] - 制表位。

为已移除的方法 GetTabStops 引入了该属性。
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


获取此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.StringTrimming  枚举。

**Returns:**
int - 指示使用此  com.aspose.psd.StringFormat  对象绘制的文本在超出布局矩形边界时如何修剪的  com.aspose.psd.StringTrimming  枚举。
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


设置垂直方向上的文本对齐信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 指定文本对齐信息的  com.aspose.psd.StringAlignment  枚举。 |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


设置在本地数字替换为西方数字时使用的语言。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | int | 一个国家语言支持 (NLS) 语言标识符，用于标识在本地数字替换为西方数字时将使用的语言。您可以将  System.Globalization.CultureInfo  对象的  P:System.Globalization.CultureInfo.LCID  属性作为 NLS 语言标识符传递。例如，假设您通过将字符串 "ar-EG" 传递给  System.Globalization.CultureInfo  构造函数来创建一个  System.Globalization.CultureInfo  对象。如果将该  System.Globalization.CultureInfo  对象的  P:System.Globalization.CultureInfo.LCID  属性与  com.aspose.psd.StringDigitSubstitute.Traditional  一起传递给  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute)  方法，则阿拉伯-印度数字将在显示时替换为西方数字。 |

为已废弃的方法 SetDigitSubstitution 引入了 setter。 |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


设置用于数字替换的方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | int | 指定如何替换因当前字体不支持而无法显示的字符串中字符的  com.aspose.psd.StringDigitSubstitute  枚举值。 |

为已废弃的方法 SetDigitSubstitution 引入了 setter。 |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


设置包含格式信息的  com.aspose.psd.StringFormatFlags  枚举。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 包含格式信息的  com.aspose.psd.StringFormatFlags  枚举。 |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


设置此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.HotkeyPrefix  对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.HotkeyPrefix  对象，默认值为  F:Aspose.Imaging.HotkeyPrefix.None 。 |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


设置水平方向上的行对齐方式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 表示行对齐方式的  com.aspose.psd.StringAlignment  枚举。 |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


为此  com.aspose.psd.StringFormat  对象设置制表位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| firstTabOffset | float | 文本行起始与第一个制表位之间的空格数。 |
| tabStops | float[] | 一个数组，包含制表位之间的距离，单位由 com.aspose.psd.Graphics.PageUnit 属性指定。 |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


设置此  com.aspose.psd.StringFormat  对象的  com.aspose.psd.StringTrimming  枚举。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 一个 com.aspose.psd.StringTrimming 枚举，指示使用此 com.aspose.psd.StringFormat 对象绘制的文本在超出布局矩形边界时如何修剪。 |

### toString() {#toString--}
```
public String toString()
```


将此  com.aspose.psd.StringFormat  对象转换为可读的字符串。

**Returns:**
java.lang.String - 此 com.aspose.psd.StringFormat 对象的字符串表示。
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

