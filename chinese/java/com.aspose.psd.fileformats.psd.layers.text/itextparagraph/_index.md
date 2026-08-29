---
title: "ITextParagraph"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于处理段落的接口"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

用于处理段落的接口
## Methods

| Method | 描述 |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 应用指定的段落。 |
| [getAutoHyphenate()](#getAutoHyphenate--) | 获取或设置一个值，指示是否 [automatic hyphenate]。 |
| [getAutoLeading()](#getAutoLeading--) | 获取或设置自动行距。 |
| [getBurasagari()](#getBurasagari--) | 获取或设置一个值，指示此 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 是否为burasagiri。 |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | 获取或设置连续连字符。 |
| [getEndIndent()](#getEndIndent--) | 获取或设置末尾缩进。 |
| [getEveryLineComposer()](#getEveryLineComposer--) | 获取或设置一个值，指示是否 [every line composer]。 |
| [getFirstLineIndent()](#getFirstLineIndent--) | 获取或设置首行缩进。 |
| [getGlyphSpacing()](#getGlyphSpacing--) | 获取或设置字形间距。 |
| [getHanging()](#getHanging--) | 获取或设置一个值，指示此 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 是否为悬挂。 |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | 获取或设置连字符单词的大小。 |
| [getJustification()](#getJustification--) | 获取或设置对齐方式。 |
| [getKinsokuOrder()](#getKinsokuOrder--) | 获取或设置禁则顺序。 |
| [getLeadingType()](#getLeadingType--) | 获取或设置行距的类型。 |
| [getLetterSpacing()](#getLetterSpacing--) | 获取或设置字母间距。 |
| [getPostHyphen()](#getPostHyphen--) | 获取或设置后置连字符。 |
| [getPreHyphen()](#getPreHyphen--) | 获取或设置前置连字符。 |
| [getSpaceAfter()](#getSpaceAfter--) | 获取或设置后置空格。 |
| [getSpaceBefore()](#getSpaceBefore--) | 获取或设置前置空格。 |
| [getStartIndent()](#getStartIndent--) | 获取或设置起始缩进。 |
| [getWordSpacing()](#getWordSpacing--) | 获取或设置单词间距。 |
| [getZone()](#getZone--) | 获取或设置区域。 |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 确定指定的段落是否相等。 |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | 获取或设置一个值，指示是否 [automatic hyphenate]。 |
| [setAutoLeading(double value)](#setAutoLeading-double-) | 获取或设置自动行距。 |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | 获取或设置一个值，指示此 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 是否为burasagiri。 |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | 获取或设置连续连字符。 |
| [setEndIndent(double value)](#setEndIndent-double-) | 获取或设置末尾缩进。 |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | 获取或设置一个值，指示是否 [every line composer]。 |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | 获取或设置首行缩进。 |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | 获取或设置字形间距。 |
| [setHanging(boolean value)](#setHanging-boolean-) | 获取或设置一个值，指示此 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 是否为悬挂。 |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | 获取或设置连字符单词的大小。 |
| [setJustification(int value)](#setJustification-int-) | 获取或设置对齐方式。 |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | 获取或设置禁则顺序。 |
| [setLeadingType(int value)](#setLeadingType-int-) | 获取或设置行距的类型。 |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | 获取或设置字母间距。 |
| [setPostHyphen(int value)](#setPostHyphen-int-) | 获取或设置后置连字符。 |
| [setPreHyphen(int value)](#setPreHyphen-int-) | 获取或设置前置连字符。 |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | 获取或设置后置空格。 |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | 获取或设置前置空格。 |
| [setStartIndent(double value)](#setStartIndent-double-) | 获取或设置起始缩进。 |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | 获取或设置单词间距。 |
| [setZone(double value)](#setZone-double-) | 获取或设置区域。 |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


应用指定的段落。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | 段落。 |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


获取或设置一个值，指示是否 [automatic hyphenate]。

值：  true  如果 [automatic hyphenate]；否则，  false 。

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


获取或设置自动行距。

值： 自动行距。

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


获取或设置一个值，指示此 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 是否为burasagiri。

Value:  true  如果是burasagiri；否则，  false 。

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


获取或设置连续连字符。

Value: 连续的连字符。

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


获取或设置末尾缩进。

Value: 结束缩进。

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


获取或设置一个值，指示是否 [every line composer]。

Value:  true  如果是[every line composer]；否则，  false 。

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


获取或设置首行缩进。

Value: 首行缩进。

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


获取或设置字形间距。

Value: 字形间距。

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


获取或设置一个值，指示此 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 是否为悬挂。

Value:  true  如果是悬挂；否则，  false 。

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


获取或设置连字符单词的大小。

Value: 连字符单词的大小。

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


获取或设置对齐方式。

Value: 对齐方式。

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


获取或设置禁则顺序。

Value: 禁则顺序。

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


获取或设置行距的类型。

Value: 行距的类型。

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


获取或设置字母间距。

Value: 字母间距。

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


获取或设置后置连字符。

Value: 后置连字符。

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


获取或设置前置连字符。

Value: 前置连字符。

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


获取或设置后置空格。

Value: 后面的空格。

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


获取或设置前置空格。

Value: 前面的空格。

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


获取或设置起始缩进。

Value: 起始缩进。

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


获取或设置单词间距。

Value: 单词间距。

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


获取或设置区域。

Value: 区域。

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


确定指定的段落是否相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | 段落。 |

**Returns:**
boolean -  true  如果指定的段落相等；否则，  false 。
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


获取或设置一个值，指示是否 [automatic hyphenate]。

值：  true  如果 [automatic hyphenate]；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


获取或设置自动行距。

值： 自动行距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


获取或设置一个值，指示此 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 是否为burasagiri。

Value:  true  如果是burasagiri；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


获取或设置连续连字符。

Value: 连续的连字符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


获取或设置末尾缩进。

Value: 结束缩进。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


获取或设置一个值，指示是否 [every line composer]。

Value:  true  如果是[every line composer]；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


获取或设置首行缩进。

Value: 首行缩进。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


获取或设置字形间距。

Value: 字形间距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


获取或设置一个值，指示此 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 是否为悬挂。

Value:  true  如果是悬挂；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


获取或设置连字符单词的大小。

Value: 连字符单词的大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


获取或设置对齐方式。

Value: 对齐方式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


获取或设置禁则顺序。

Value: 禁则顺序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


获取或设置行距的类型。

Value: 行距的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


获取或设置字母间距。

Value: 字母间距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


获取或设置后置连字符。

Value: 后置连字符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


获取或设置前置连字符。

Value: 前置连字符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


获取或设置后置空格。

Value: 后面的空格。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


获取或设置前置空格。

Value: 前面的空格。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


获取或设置起始缩进。

Value: 起始缩进。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


获取或设置单词间距。

Value: 单词间距。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


获取或设置区域。

Value: 区域。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

