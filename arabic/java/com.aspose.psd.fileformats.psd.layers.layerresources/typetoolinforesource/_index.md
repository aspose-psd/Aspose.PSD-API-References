---
title: "TypeToolInfoResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "معلومات أداة النوع."
type: docs
weight: 79
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

معلومات أداة النوع. لإصدار PSD أقل من 6.0.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | ينشئ مثيلاً جديدًا من الفئة [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | إصدار رأس PSB |
| [PsbResourceSignature](#PsbResourceSignature) | توقيع المورد الخاص بـ PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | إصدار رأس PSD |
| [ResourceSignature](#ResourceSignature) | توقيع المورد المشترك. |
| [TypeToolKey](#TypeToolKey) | مفتاح معلومات أداة النوع. |
| [ventureLicense_internalized](#ventureLicense-internalized) | رخصة المشروع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAComponent()](#getAComponent--) | يحصل أو يعيّن مكوّنًا. |
| [getBComponent()](#getBComponent--) | يحصل أو يعيّن المكوّن b. |
| [getCharacterCount()](#getCharacterCount--) | يحصل أو يعيّن عدد الأحرف. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | يحصل أو يعيّن قيمة مساحة اللون. |
| [getFontVersion()](#getFontVersion--) | يحصل أو يعيّن إصدار الخط. |
| [getFonts()](#getFonts--) | يحصل أو يعيّن الخطوط. |
| [getFontsCount()](#getFontsCount--) | يحصل على عدد الخطوط. |
| [getGComponent()](#getGComponent--) | يحصل أو يعيّن المكوّن g. |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | يحصل أو يعيّن الموضع الأفقي. |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getLength()](#getLength--) | يحصل على طول مورد الطبقة بالبايت. |
| [getLineCount()](#getLineCount--) | يحصل على عدد الأسطر. |
| [getLines()](#getLines--) | يحصل أو يعيّن الأسطر. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getRComponent()](#getRComponent--) | يحصل أو يعيّن المكوّن r. |
| [getScaleFactor()](#getScaleFactor--) | يحصل أو يعيّن معامل المقياس. |
| [getSelectionEnd()](#getSelectionEnd--) | يحصل أو يعيّن نهاية التحديد. |
| [getSelectionStart()](#getSelectionStart--) | يحصل أو يعيّن بداية التحديد. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [getStyles()](#getStyles--) | يحصل أو يعيّن أنماط الخط. |
| [getStylesCount()](#getStylesCount--) | يحصل على عدد الأنماط. |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل أو يعيّن مصفوفة التحويل. |
| [getTypeValue()](#getTypeValue--) | يحصل أو يضبط قيمة النوع. |
| [getVersion()](#getVersion--) | يحصل على أو يعيّن الإصدار. |
| [getVerticalPlacement()](#getVerticalPlacement--) | يحصل أو يضبط الموضع العمودي. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ حاوية الدفق المحددة. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setAComponent(short value)](#setAComponent-short-) | يحصل أو يعيّن مكوّنًا. |
| [setBComponent(short value)](#setBComponent-short-) | يحصل أو يعيّن المكوّن b. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | يحصل أو يعيّن عدد الأحرف. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | يحصل أو يضبط البيانات الخام للون. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | يحصل أو يعيّن قيمة مساحة اللون. |
| [setFontVersion(short value)](#setFontVersion-short-) | يحصل أو يعيّن إصدار الخط. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | يحصل أو يعيّن الخطوط. |
| [setGComponent(short value)](#setGComponent-short-) | يحصل أو يعيّن المكوّن g. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | يحصل أو يعيّن الموضع الأفقي. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | يحصل أو يعيّن الأسطر. |
| [setRComponent(short value)](#setRComponent-short-) | يحصل أو يعيّن المكوّن r. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | يحصل أو يعيّن معامل المقياس. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | يحصل أو يعيّن نهاية التحديد. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | يحصل أو يعيّن بداية التحديد. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | يحصل أو يعيّن أنماط الخط. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | يحصل أو يعيّن مصفوفة التحويل. |
| [setTypeValue(short value)](#setTypeValue-short-) | يحصل أو يضبط قيمة النوع. |
| [setVersion(short value)](#setVersion-short-) | يحصل على أو يعيّن الإصدار. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | يحصل أو يضبط الموضع العمودي. |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


ينشئ مثيلاً جديدًا من الفئة [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource).

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


إصدار رأس PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


توقيع المورد الخاص بـ PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


إصدار رأس PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


توقيع المورد المشترك.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


مفتاح معلومات أداة النوع.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


رخصة المشروع.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. بعض الموارد غير معروفة حاليًا، لكن لدينا قائمة كاملة بالموارد الخاصة بـ PSB التي تغير سلوكها عند الحفظ. لذلك نحتاج إلى التحقق من ذلك في UnknownResource على الأقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | المفتاح. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


يحصل أو يعيّن مكوّنًا.

القيمة: مكوّن.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


يحصل أو يعيّن المكوّن b.

القيمة: المكوّن b.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


يحصل أو يعيّن عدد الأحرف.

القيمة: عدد الأحرف.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpaceValue() {#getColorSpaceValue--}
```
public final short getColorSpaceValue()
```


يحصل أو يعيّن قيمة مساحة اللون.

القيمة: قيمة مساحة اللون.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


يحصل أو يعيّن إصدار الخط.

القيمة: إصدار الخط.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


يحصل أو يعيّن الخطوط.

القيمة: الخطوط.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


يحصل على عدد الخطوط.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


يحصل أو يعيّن المكوّن g.

القيمة: المكوّن g.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


يحصل أو يعيّن الموضع الأفقي.

القيمة: الموضع الأفقي.

**Returns:**
int
### getKey() {#getKey--}
```
public final int getKey()
```


يحصل على مفتاح مورد الطبقة.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


يحصل على طول مورد الطبقة بالبايت.

**Returns:**
int
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


يحصل على عدد الأسطر.

القيمة: عدد الأسطر.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


يحصل أو يعيّن الأسطر.

القيمة: الأسطر.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


يحصل على طول البادئة. القيمة الافتراضية هي 12 لموارد 8BIM و 16 لموارد 8B64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| psdVersion | int | إصدار PSD. |

**Returns:**
int - طول البادئة.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود.

**Returns:**
int
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


يحصل أو يعيّن المكوّن r.

القيمة: المكوّن r.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


يحصل أو يعيّن معامل المقياس.

القيمة: عامل القياس.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


يحصل أو يعيّن نهاية التحديد.

القيمة: نهاية التحديد.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


يحصل أو يعيّن بداية التحديد.

القيمة: بداية التحديد.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل على توقيع مورد الطبقة.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


يحصل أو يعيّن أنماط الخط.

القيمة: أنماط الخط.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


يحصل على عدد الأنماط.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


يحصل أو يعيّن مصفوفة التحويل.

القيمة: مصفوفة التحويل.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


يحصل أو يضبط قيمة النوع.

القيمة: قيمة النوع.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


يحصل على أو يعيّن الإصدار.

القيمة: الإصدار.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


يحصل أو يضبط الموضع العمودي.

القيمة: الموضع العمودي.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


يحدد ما إذا كان المورد خاصًا بـ PSB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | مفتاح المورد. |

**Returns:**
boolean -  true  إذا كان المورد خاصًا بـ PSD؛ وإلا،  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB.

القيمة:  true  إذا كان هذا الكائن خاصًا بـ PSB؛ وإلا،  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


يحفظ حاوية الدفق المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| psdVersion | int | إصدار PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


يحفظ رأس المورد المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| التوقيع | int | التوقيع. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


يحفظ توقيع الرأس، المعرف والطول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| التوقيع | int | التوقيع. |
| isLengthLong | boolean | إذا تم ضبطه على  true  يكون الطول طويلًا. |

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


يحصل أو يعيّن مكوّنًا.

القيمة: مكوّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


يحصل أو يعيّن المكوّن b.

القيمة: المكوّن b.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


يحصل أو يعيّن عدد الأحرف.

القيمة: عدد الأحرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


يحصل أو يضبط البيانات الخام للون.

القيمة: بيانات اللون الخام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


يحصل أو يعيّن قيمة مساحة اللون.

القيمة: قيمة مساحة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


يحصل أو يعيّن إصدار الخط.

القيمة: إصدار الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


يحصل أو يعيّن الخطوط.

القيمة: الخطوط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


يحصل أو يعيّن المكوّن g.

القيمة: المكوّن g.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


يحصل أو يعيّن الموضع الأفقي.

القيمة: الموضع الأفقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


يحصل أو يعيّن الأسطر.

القيمة: الأسطر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


يحصل أو يعيّن المكوّن r.

القيمة: المكوّن r.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


يحصل أو يعيّن معامل المقياس.

القيمة: عامل القياس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


يحصل أو يعيّن نهاية التحديد.

القيمة: نهاية التحديد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


يحصل أو يعيّن بداية التحديد.

القيمة: بداية التحديد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


يحصل أو يعيّن أنماط الخط.

القيمة: أنماط الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


يحصل أو يعيّن مصفوفة التحويل.

القيمة: مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


يحصل أو يضبط قيمة النوع.

القيمة: قيمة النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


يحصل على أو يعيّن الإصدار.

القيمة: الإصدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


يحصل أو يضبط الموضع العمودي.

القيمة: الموضع العمودي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل هذا الكائن.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

