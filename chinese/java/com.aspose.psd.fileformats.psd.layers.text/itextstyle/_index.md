---
title: "ITextStyle"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于处理文本样式的接口"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

用于处理文本样式的接口
## Methods

| Method | 描述 |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | 应用指定的样式。 |
| [getAutoKerning()](#getAutoKerning--) | 获取或设置自动字距调整。 |
| [getAutoLeading()](#getAutoLeading--) | 获取或设置一个值，指示是否[automatic leading]。 |
| [getBaselineShift()](#getBaselineShift--) | 基线偏移。 |
| [getContextualAlternates()](#getContextualAlternates--) | 用于连接字母的上下文替代字符。 |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | 用于连接字母的可选连字，尤其在手写体字体中。 |
| [getFauxBold()](#getFauxBold--) | 获取或设置是否启用伪粗体。 |
| [getFauxItalic()](#getFauxItalic--) | 获取或设置是否启用伪粗体。 |
| [getFillColor()](#getFillColor--) | 获取或设置填充颜色。 |
| [getFontBaseline()](#getFontBaseline--) | 字体基线。 |
| [getFontCaps()](#getFontCaps--) | 字体大写字母。 |
| [getFontIndex()](#getFontIndex--) | 获取字体索引。 |
| [getFontName()](#getFontName--) | 获取或设置字体名称。 |
| [getFontSize()](#getFontSize--) | 获取或设置字体大小。 |
| [getFractions()](#getFractions--) | 分数字符可以替换为特殊字形。 |
| [getHindiNumbers()](#getHindiNumbers--) | 获取或设置一个指示是否为[hindi numbers]的值。 |
| [getHorizontalScale()](#getHorizontalScale--) | 水平比例。 |
| [getKerning()](#getKerning--) | 获取或设置字距。 |
| [getLanguageIndex()](#getLanguageIndex--) | 获取语言索引。 |
| [getLeading()](#getLeading--) | 获取或设置行距。 |
| [getStandardLigatures()](#getStandardLigatures--) | 用于连接字母的标准上下文连字。 |
| [getStrikethrough()](#getStrikethrough--) | 获取或设置一个指示是否为[strikethrough]的值。 |
| [getStrokeColor()](#getStrokeColor--) | 获取或设置描边颜色。 |
| [getTracking()](#getTracking--) | 获取或设置字形间距。 |
| [getUnderline()](#getUnderline--) | 获取或设置一个指示是否为[underline]的值。 |
| [getVerticalScale()](#getVerticalScale--) | 垂直比例。 |
| [get_noBreak()](#get-noBreak--) | 获取或设置不换行值。 |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | 确定指定的样式是否相等。 |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | 获取或设置标准垂直罗马对齐方式。 |
| [setAutoKerning(int value)](#setAutoKerning-int-) | 获取或设置自动字距调整。 |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | 获取或设置一个值，指示是否[automatic leading]。 |
| [setBaselineShift(double value)](#setBaselineShift-double-) | 基线偏移。 |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | 用于连接字母的上下文替代字符。 |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | 用于连接字母的可选连字，尤其在手写体字体中。 |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | 获取或设置是否启用伪粗体。 |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | 获取或设置是否启用伪粗体。 |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | 获取或设置填充颜色。 |
| [setFontBaseline(int value)](#setFontBaseline-int-) | 字体基线。 |
| [setFontCaps(int value)](#setFontCaps-int-) | 字体大写字母。 |
| [setFontName(String value)](#setFontName-java.lang.String-) | 获取或设置字体名称。 |
| [setFontSize(double value)](#setFontSize-double-) | 获取或设置字体大小。 |
| [setFractions(boolean value)](#setFractions-boolean-) | 分数字符可以替换为特殊字形。 |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | 获取或设置一个指示是否为[hindi numbers]的值。 |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | 水平比例。 |
| [setKerning(int value)](#setKerning-int-) | 获取或设置字距。 |
| [setLeading(double value)](#setLeading-double-) | 获取或设置行距。 |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | 用于连接字母的标准上下文连字。 |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | 获取或设置一个指示是否为[strikethrough]的值。 |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | 获取或设置描边颜色。 |
| [setTracking(int value)](#setTracking-int-) | 获取或设置字形间距。 |
| [setUnderline(boolean value)](#setUnderline-boolean-) | 获取或设置一个指示是否为[underline]的值。 |
| [setVerticalScale(double value)](#setVerticalScale-double-) | 垂直比例。 |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | 获取或设置标准垂直罗马对齐方式。 |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | 获取或设置不换行值。 |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


应用指定的样式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | 样式。 |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


获取或设置自动字距调整。

Value: 两个字符之间的自动字距。

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


获取或设置一个值，指示是否[automatic leading]。

Value: 如果 [automatic leading] 为 true，则为 true；否则为 false。

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


基线偏移。

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


用于连接字母的上下文替代字符。

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


用于连接字母的可选连字，尤其在手写体字体中。

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


获取或设置是否启用伪粗体。

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


获取或设置是否启用伪粗体。

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


获取或设置填充颜色。

Value: 填充的颜色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


字体基线。

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


字体大写字母。

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


获取字体索引。

Value: 字体。

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


获取或设置字体名称。

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


获取或设置字体大小。

Value: 字体的大小。

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


分数字符可以替换为特殊字形。

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


获取或设置一个指示是否为[hindi numbers]的值。

Value: 如果 [hindi numbers] 为 true，则为 true；否则为 false。

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


水平比例。

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


获取或设置字距。

Value: 两个字符之间的字距。

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


获取语言索引。

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


获取或设置行距。

Value: 行距。

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


用于连接字母的标准上下文连字。

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


获取或设置一个指示是否为[strikethrough]的值。

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


获取或设置描边颜色。

Value: 笔画的颜色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


获取或设置字形间距。

Value: 字符间距。

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


获取或设置一个指示是否为[underline]的值。

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


垂直比例。

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


获取或设置不换行值。

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


确定指定的样式是否相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | 样式。 |

**Returns:**
boolean - 如果指定的样式相等，则为 true；否则为 false。
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


获取或设置标准的垂直罗马对齐方式。此基于 BaselineDirection 资源值的设置仅在文本方向为 [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) 时适用。

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


获取或设置自动字距调整。

Value: 两个字符之间的自动字距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


获取或设置一个值，指示是否[automatic leading]。

Value: 如果 [automatic leading] 为 true，则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


基线偏移。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


用于连接字母的上下文替代字符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


用于连接字母的可选连字，尤其在手写体字体中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


获取或设置是否启用伪粗体。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


获取或设置是否启用伪粗体。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


获取或设置填充颜色。

Value: 填充的颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


字体基线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


字体大写字母。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


获取或设置字体名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


获取或设置字体大小。

Value: 字体的大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


分数字符可以替换为特殊字形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


获取或设置一个指示是否为[hindi numbers]的值。

Value: 如果 [hindi numbers] 为 true，则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


水平比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


获取或设置字距。

Value: 两个字符之间的字距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


获取或设置行距。

Value: 行距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


用于连接字母的标准上下文连字。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


获取或设置一个指示是否为[strikethrough]的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


获取或设置描边颜色。

Value: 笔画的颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


获取或设置字形间距。

Value: 字符间距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


获取或设置一个指示是否为[underline]的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


垂直比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


获取或设置标准的垂直罗马对齐方式。此基于 BaselineDirection 资源值的设置仅在文本方向为 [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) 时适用。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


获取或设置不换行值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

