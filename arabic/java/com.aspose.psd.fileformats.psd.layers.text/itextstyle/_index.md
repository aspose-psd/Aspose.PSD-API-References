---
title: "ITextStyle"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "واجهة للعمل مع نمط النص."
type: docs
weight: 14
url: /ar/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

واجهة للعمل مع نمط النص.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | يطبق النمط المحدد. |
| [getAutoKerning()](#getAutoKerning--) | يحصل أو يضبط الـ kerning التلقائي. |
| [getAutoLeading()](#getAutoLeading--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | إزاحة الخط الأساسي. |
| [getContextualAlternates()](#getContextualAlternates--) | البدائل السياقية المستخدمة لربط الأحرف معًا. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | الروابط الاختيارية المستخدمة لربط الأحرف، خاصةً في الخطوط المكتوبة. |
| [getFauxBold()](#getFauxBold--) | يحصل أو يضبط ما إذا كان الـ faux bold مفعلاً. |
| [getFauxItalic()](#getFauxItalic--) | يحصل أو يضبط ما إذا كان الـ faux bold مفعلاً. |
| [getFillColor()](#getFillColor--) | يحصل أو يضبط لون التعبئة. |
| [getFontBaseline()](#getFontBaseline--) | خط الأساس للخط. |
| [getFontCaps()](#getFontCaps--) | حروف الخط الكبيرة. |
| [getFontIndex()](#getFontIndex--) | يحصل على فهرس الخط. |
| [getFontName()](#getFontName--) | يحصل أو يضبط اسم الخط. |
| [getFontSize()](#getFontSize--) | يحصل أو يضبط حجم الخط. |
| [getFractions()](#getFractions--) | يمكن استبدال رموز الكسور برمز خاص. |
| [getHindiNumbers()](#getHindiNumbers--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | المقياس الأفقي. |
| [getKerning()](#getKerning--) | يحصل أو يضبط الـ kerning. |
| [getLanguageIndex()](#getLanguageIndex--) | يحصل على فهرس اللغة. |
| [getLeading()](#getLeading--) | يحصل أو يضبط الـ leading. |
| [getStandardLigatures()](#getStandardLigatures--) | الربط السياقي القياسي المستخدم لربط الأحرف معًا. |
| [getStrikethrough()](#getStrikethrough--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هناك [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | يحصل أو يعيّن لون الخط. |
| [getTracking()](#getTracking--) | يحصل أو يعيّن التتبع. |
| [getUnderline()](#getUnderline--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هناك [underline]. |
| [getVerticalScale()](#getVerticalScale--) | المقياس العمودي. |
| [get_noBreak()](#get-noBreak--) | يحصل أو يعيّن قيمة عدم الانقطاع. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | يحدد ما إذا كان النمط المحدد متساويًا. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | يحصل أو يعيّن المحاذاة الرومانية العمودية القياسية. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | يحصل أو يضبط الـ kerning التلقائي. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | إزاحة الخط الأساسي. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | البدائل السياقية المستخدمة لربط الأحرف معًا. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | الروابط الاختيارية المستخدمة لربط الأحرف، خاصةً في الخطوط المكتوبة. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | يحصل أو يضبط ما إذا كان الـ faux bold مفعلاً. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | يحصل أو يضبط ما إذا كان الـ faux bold مفعلاً. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | يحصل أو يضبط لون التعبئة. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | خط الأساس للخط. |
| [setFontCaps(int value)](#setFontCaps-int-) | حروف الخط الكبيرة. |
| [setFontName(String value)](#setFontName-java.lang.String-) | يحصل أو يضبط اسم الخط. |
| [setFontSize(double value)](#setFontSize-double-) | يحصل أو يضبط حجم الخط. |
| [setFractions(boolean value)](#setFractions-boolean-) | يمكن استبدال رموز الكسور برمز خاص. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | المقياس الأفقي. |
| [setKerning(int value)](#setKerning-int-) | يحصل أو يضبط الـ kerning. |
| [setLeading(double value)](#setLeading-double-) | يحصل أو يضبط الـ leading. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | الربط السياقي القياسي المستخدم لربط الأحرف معًا. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هناك [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | يحصل أو يعيّن لون الخط. |
| [setTracking(int value)](#setTracking-int-) | يحصل أو يعيّن التتبع. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هناك [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | المقياس العمودي. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | يحصل أو يعيّن المحاذاة الرومانية العمودية القياسية. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | يحصل أو يعيّن قيمة عدم الانقطاع. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


يطبق النمط المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | النمط. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


يحصل أو يضبط الـ kerning التلقائي.

القيمة: التباعد التلقائي بين حرفين.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [automatic leading].

القيمة:  true  إذا كان هناك [automatic leading]؛ وإلا،  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


إزاحة الخط الأساسي.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


البدائل السياقية المستخدمة لربط الأحرف معًا.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


الروابط الاختيارية المستخدمة لربط الأحرف، خاصةً في الخطوط المكتوبة.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


يحصل أو يضبط ما إذا كان الـ faux bold مفعلاً.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


يحصل أو يضبط ما إذا كان الـ faux bold مفعلاً.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


يحصل أو يضبط لون التعبئة.

القيمة: لون التعبئة.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


خط الأساس للخط.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


حروف الخط الكبيرة.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


يحصل على فهرس الخط.

القيمة: الخط.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


يحصل أو يضبط اسم الخط.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


يحصل أو يضبط حجم الخط.

القيمة: حجم الخط.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


يمكن استبدال رموز الكسور برمز خاص.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [hindi numbers].

القيمة:  true  إذا كان هناك [hindi numbers]؛ وإلا،  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


المقياس الأفقي.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


يحصل أو يضبط الـ kerning.

القيمة: التباعد بين حرفين.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


يحصل على فهرس اللغة.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


يحصل أو يضبط الـ leading.

القيمة: المسافة الرأسية.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


الربط السياقي القياسي المستخدم لربط الأحرف معًا.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هناك [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


يحصل أو يعيّن لون الخط.

القيمة: لون الخط.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


يحصل أو يعيّن التتبع.

القيمة: التتبع.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هناك [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


المقياس العمودي.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


يحصل أو يعيّن قيمة عدم الانقطاع.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


يحدد ما إذا كان النمط المحدد متساويًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | النمط. |

**Returns:**
منطقي -  true  إذا كان النمط المحدد متساويًا؛ وإلا،  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


يحصل أو يعيّن المحاذاة الرومانية العمودية القياسية. هذا يعتمد على قيمة مورد BaselineDirection ويطبق فقط عندما يكون اتجاه النص هو [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


يحصل أو يضبط الـ kerning التلقائي.

القيمة: التباعد التلقائي بين حرفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [automatic leading].

القيمة:  true  إذا كان هناك [automatic leading]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


إزاحة الخط الأساسي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


البدائل السياقية المستخدمة لربط الأحرف معًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


الروابط الاختيارية المستخدمة لربط الأحرف، خاصةً في الخطوط المكتوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


يحصل أو يضبط ما إذا كان الـ faux bold مفعلاً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


يحصل أو يضبط ما إذا كان الـ faux bold مفعلاً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


يحصل أو يضبط لون التعبئة.

القيمة: لون التعبئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


خط الأساس للخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


حروف الخط الكبيرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


يحصل أو يضبط اسم الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


يحصل أو يضبط حجم الخط.

القيمة: حجم الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


يمكن استبدال رموز الكسور برمز خاص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [hindi numbers].

القيمة:  true  إذا كان هناك [hindi numbers]؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


المقياس الأفقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


يحصل أو يضبط الـ kerning.

القيمة: التباعد بين حرفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


يحصل أو يضبط الـ leading.

القيمة: المسافة الرأسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


الربط السياقي القياسي المستخدم لربط الأحرف معًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هناك [strikethrough].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


يحصل أو يعيّن لون الخط.

القيمة: لون الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


يحصل أو يعيّن التتبع.

القيمة: التتبع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هناك [underline].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


المقياس العمودي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


يحصل أو يعيّن المحاذاة الرومانية العمودية القياسية. هذا يعتمد على قيمة مورد BaselineDirection ويطبق فقط عندما يكون اتجاه النص هو [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


يحصل أو يعيّن قيمة عدم الانقطاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

