---
title: "FontSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "通用成像矢量格式渲染器的字体设置。"
type: docs
weight: 47
url: /zh/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

通用成像矢量格式渲染器的字体设置。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | 通过字体族名称获取 Adobe 字体名称。 |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | 获取默认字体名称。 |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | 获取默认字体文件夹。 |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | 通过字体名称获取字体替换数组 |
| [getFontsFolders()](#getFontsFolders--) | 获取包含 Aspose.Imaging 查找 TrueType 字体的文件夹列表的数组副本。 |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | 获取或设置一个值，指示是否 [get alternative font]。 |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | 获取最合适的替代字体。 |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | 确定是否 [is font allowed] [the specified font name]。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | 删除字体缓存文件。 |
| [reset()](#reset--) | 将字体文件夹和默认字体名称重置为系统默认值。 |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | 通过字体列表限制字体使用。 |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | 设置默认字体名称。 |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | 设置字体替换列表。 |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | 覆盖针对  folder 的字体文件夹列表。 |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | 覆盖针对  folders 的字体文件夹列表。 |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | 设置加载 TrueType 字体的文件夹，并清除所有已加载的字体。 |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | 获取或设置一个值，指示是否 [get alternative font]。 |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | 更新包含文字图层的 PSD 文件的字体缓存。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


通过字体族名称获取 Adobe 字体名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontFamilyName | java.lang.String | 字体族名称。 |

**Returns:**
java.lang.String - 根据字体族名称的 Adobe 字体名称。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


获取默认字体名称。

**Returns:**
java.lang.String - 默认字体的名称
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


获取默认字体文件夹。

**Returns:**
java.lang.String[] - 返回系统文件夹
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


通过字体名称获取字体替换数组

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体的名称。 |

**Returns:**
java.lang.String[] - 提供的字体的替代名称数组
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


获取包含 Aspose.Imaging 查找 TrueType 字体的文件夹列表的数组副本。

返回的值是 Aspose.Imaging 使用的数据的副本。如果更改返回数组中的条目，将不会影响文档渲染。要指定新的字体位置，请使用 setFontsFolders 方法。

**Returns:**
java.lang.String[] - 当前字体位置的副本。
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


获取或设置一个值，指示是否 [get alternative font]。

值： true 如果 [get alternative font]；否则， false 。

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


获取最合适的替代字体。如果所有替代字体均不被允许，则返回第一个被允许且可用的字体。如果没有可用的字体，则返回参数中的字体。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体的名称。 |

**Returns:**
java.lang.String - 被替换字体的名称
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


确定是否 [is font allowed] [the specified font name]。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体的名称。 |

**Returns:**
boolean -  true 如果 [is font allowed] [the specified font name]；否则， false 。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


删除字体缓存文件。

### reset() {#reset--}
```
public static void reset()
```


将字体文件夹和默认字体名称重置为系统默认值。

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


通过字体列表限制字体的使用。请在限制前检查真实的字体名称。将允许的字体列表设置为 Null 可移除限制。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontList | java.lang.String[] | 字体列表。 |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


设置默认字体名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体的默认名称。 |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


设置字体替换列表。如果字体不被允许，则会寻找替代字体。列表中的第一个字体将优先使用。如果它也被限制，则会选择列表中的下一个字体。如果字体没有替代或所有替代都不被允许，则会使用允许字体列表中的第一个允许的字体。如果没有允许且可用的字体，库将尝试使用系统默认字体，即使它不在允许范围内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fontToReplace | java.lang.String | 要替换的字体。 |
| fontNames | java.lang.String[] | 按相似度顺序排列的替代字体名称。 |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


覆盖针对  folder 的字体文件夹列表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| folder | java.lang.String | 包含 TrueType 字体的文件夹。 |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


覆盖针对  folders 的字体文件夹列表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| folders | java.lang.String[] | 文件夹数组 |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


设置加载 TrueType 字体的文件夹并清除所有已加载的字体。对字体文件夹不执行任何检查。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| folders | java.lang.String[] | 字体文件夹。 |
| recursive | boolean | 如果设置为 true [recursive]。 |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


获取或设置一个值，指示是否 [get alternative font]。

值： true 如果 [get alternative font]；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


更新包含文字图层的 PSD 文件的字体缓存。此方法确保在处理 PSD 文件时，会考虑通过 FontSettings.setFontsFolder(fontsFolder) 方法指定的 fontsFolder 文件夹中的字体，或在使用 FontSettings.reset() 重置字体后得到的字体。请在每次为 PSD 图像调用 FontSettings.setFontsFolder(fontsFolder) 或 FontSettings.reset() 时使用此方法。如果未调用此方法，则无法保证字体会被更新。

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

