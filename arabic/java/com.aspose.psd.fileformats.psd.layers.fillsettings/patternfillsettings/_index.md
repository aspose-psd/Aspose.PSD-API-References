---
title: "PatternFillSettings"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "إعدادات تأثير تعبئة النمط"
type: docs
weight: 20
url: /ar/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

إعدادات تأثير تعبئة النمط
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | ينشئ مثيلًا جديدًا من الفئة [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | يولد عقد موارد LFX2. |
| [getAlignWithLayer()](#getAlignWithLayer--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [link with layer]. |
| [getAngle()](#getAngle--) | يحصل أو يعيّن الزاوية. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | يحصل أو يعيّن اللون. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | نوع التعبئة |
| [getHorizontalOffset()](#getHorizontalOffset--) | يحصل أو يعيّن الإزاحة الأفقية. |
| [getLinked()](#getLinked--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) مرتبطًا. |
| [getPatternData()](#getPatternData--) | يحصل أو يعيّن بيانات النمط. |
| [getPatternHeight()](#getPatternHeight--) | يحصل أو يعيّن ارتفاع النمط. |
| [getPatternId()](#getPatternId--) | يحصل أو يعيّن معرف النمط. |
| [getPatternName()](#getPatternName--) | يحصل أو يعيّن اسم النمط. |
| [getPatternWidth()](#getPatternWidth--) | يحصل أو يعيّن عرض النمط. |
| [getPhase_internalized()](#getPhase-internalized--) | يحصل أو يعيّن الطور. |
| [getPointType()](#getPointType--) | يحصل أو يعيّن نوع النقطة. |
| [getScale()](#getScale--) | يحصل أو يضبط المقياس. |
| [getVerticalOffset()](#getVerticalOffset--) | يحصل أو يعيّن الإزاحة العمودية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | يُثير تغيير القيمة. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | يحصل أو يعيّن الزاوية. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | يحصل أو يعيّن اللون. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | يحصل أو يعيّن الإزاحة الأفقية. |
| [setLinked(boolean value)](#setLinked-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) مرتبطًا. |
| [setPatternData(int[] value)](#setPatternData-int---) | يحصل أو يعيّن بيانات النمط. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | يضبط مخزن البكسل للنمط ووضع الضغط لاستخدامه عند الحفظ. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | يحصل أو يعيّن ارتفاع النمط. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | يحصل أو يعيّن معرف النمط. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | يحصل أو يعيّن اسم النمط. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | يحصل أو يعيّن عرض النمط. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | يحصل أو يعيّن الطور. |
| [setPointType(String value)](#setPointType-java.lang.String-) | يحصل أو يعيّن نوع النقطة. |
| [setScale(double value)](#setScale-double-) | يحصل أو يضبط المقياس. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | يحصل أو يعيّن الإزاحة العمودية. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | يضبط البيانات الافتراضية للنمط إلى مثيل [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | يقوم بتحديث خصائص النمط من مثيل [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


ينشئ مثيلًا جديدًا من الفئة [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


يولد عقد موارد LFX2.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pointType | java.lang.String | نوع النقطة. |
| color | [Color](../../com.aspose.psd/color) | اللون. |
| patternName | java.lang.String | اسم النمط. |
| المعرّف | java.lang.String | المعرّف. |
| المقياس | double | المقياس. |
| مرتبط | boolean | إذا تم تعيينه إلى  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | الإزاحة. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - قائمة [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [link with layer].

القيمة:  true  إذا [link with layer]; وإلا,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


يحصل أو يعيّن الزاوية.

القيمة: الزاوية.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


يحصل أو يعيّن اللون.

القيمة: اللون.

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


نوع التعبئة

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


يحصل أو يعيّن الإزاحة الأفقية.

القيمة: الإزاحة الأفقية.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) مرتبطًا.

القيمة:  true  إذا مرتبط; وإلا,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


يحصل أو يعيّن بيانات النمط.

القيمة: بيانات النمط.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


يحصل أو يعيّن ارتفاع النمط.

القيمة: ارتفاع النمط.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


يحصل أو يعيّن معرف النمط.

القيمة: معرّف النمط.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


يحصل أو يعيّن اسم النمط.

القيمة: اسم النمط.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


يحصل أو يعيّن عرض النمط.

القيمة: عرض النمط.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


يحصل أو يعيّن الطور.

القيمة: المرحلة.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


يحصل أو يعيّن نوع النقطة.

القيمة: نوع النقطة.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


يحصل أو يضبط المقياس.

القيمة: المقياس.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


يحصل أو يعيّن الإزاحة العمودية.

القيمة: الإزاحة العمودية.

**Returns:**
int
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


يُثير تغيير القيمة.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [link with layer].

القيمة:  true  إذا [link with layer]; وإلا,  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


يحصل أو يعيّن الزاوية.

القيمة: الزاوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


يحصل أو يعيّن اللون.

القيمة: اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


يحصل أو يعيّن الإزاحة الأفقية.

القيمة: الإزاحة الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) مرتبطًا.

القيمة:  true  إذا مرتبط; وإلا,  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


يحصل أو يعيّن بيانات النمط.

القيمة: بيانات النمط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


يضبط مخزن البكسل للنمط ووضع الضغط لاستخدامه عند الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| patternData | int[] | بكسل 32-بت في  0xAARRGGBB . |
| compressionModeOnSave | byte | وضع الضغط المستخدم لتحديد ضغط بيانات النمط عند حفظ ملف psd. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


يحصل أو يعيّن ارتفاع النمط.

القيمة: ارتفاع النمط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


يحصل أو يعيّن معرف النمط.

القيمة: معرّف النمط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


يحصل أو يعيّن اسم النمط.

القيمة: اسم النمط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


يحصل أو يعيّن عرض النمط.

القيمة: عرض النمط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


يحصل أو يعيّن الطور.

القيمة: المرحلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


يحصل أو يعيّن نوع النقطة.

القيمة: نوع النقطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


يحصل أو يضبط المقياس.

القيمة: المقياس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


يحصل أو يعيّن الإزاحة العمودية.

القيمة: الإزاحة العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


يضبط البيانات الافتراضية للنمط إلى مثيل [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | إعدادات تعبئة النمط. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


يقوم بتحديث خصائص النمط من مثيل [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | المثيل [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) مع بيانات النمط. |

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

