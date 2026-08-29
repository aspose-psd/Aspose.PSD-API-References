---
title: "PatternFillSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "图案填充效果设置"
type: docs
weight: 20
url: /zh/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

图案填充效果设置
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | 初始化一个新的 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 类实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | 生成 LFX2 资源节点。 |
| [getAlignWithLayer()](#getAlignWithLayer--) | 获取或设置一个值，指示 [link with layer]。 |
| [getAngle()](#getAngle--) | 获取或设置角度。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取或设置颜色。 |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | 填充类型 |
| [getHorizontalOffset()](#getHorizontalOffset--) | 获取或设置水平偏移。 |
| [getLinked()](#getLinked--) | 获取或设置一个值，指示此 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 是否已链接。 |
| [getPatternData()](#getPatternData--) | 获取或设置图案数据。 |
| [getPatternHeight()](#getPatternHeight--) | 获取或设置图案的高度。 |
| [getPatternId()](#getPatternId--) | 获取或设置图案标识符。 |
| [getPatternName()](#getPatternName--) | 获取或设置图案的名称。 |
| [getPatternWidth()](#getPatternWidth--) | 获取或设置图案的宽度。 |
| [getPhase_internalized()](#getPhase-internalized--) | 获取或设置相位。 |
| [getPointType()](#getPointType--) | 获取或设置点的类型。 |
| [getScale()](#getScale--) | 获取或设置比例。 |
| [getVerticalOffset()](#getVerticalOffset--) | 获取或设置垂直偏移量。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 引发值更改。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | 获取或设置一个值，指示 [link with layer]。 |
| [setAngle(double value)](#setAngle-double-) | 获取或设置角度。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 获取或设置颜色。 |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | 获取或设置水平偏移。 |
| [setLinked(boolean value)](#setLinked-boolean-) | 获取或设置一个值，指示此 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 是否已链接。 |
| [setPatternData(int[] value)](#setPatternData-int---) | 获取或设置图案数据。 |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | 设置图案的像素缓冲区以及保存时使用的压缩模式。 |
| [setPatternHeight(int value)](#setPatternHeight-int-) | 获取或设置图案的高度。 |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | 获取或设置图案标识符。 |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | 获取或设置图案的名称。 |
| [setPatternWidth(int value)](#setPatternWidth-int-) | 获取或设置图案的宽度。 |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | 获取或设置相位。 |
| [setPointType(String value)](#setPointType-java.lang.String-) | 获取或设置点的类型。 |
| [setScale(double value)](#setScale-double-) | 获取或设置比例。 |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | 获取或设置垂直偏移量。 |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | 将图案的默认数据设置为 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 实例。 |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | 从 [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 实例更新图案属性。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


初始化一个新的 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 类实例。

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


生成 LFX2 资源节点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pointType | java.lang.String | 点的类型。 |
| color | [Color](../../com.aspose.psd/color) | 颜色。 |
| patternName | java.lang.String | 图案的名称。 |
| identifier | java.lang.String | 标识符。 |
| 比例 | double | 比例。 |
| linked | boolean | 如果设置为 true [linked]。 |
| offset | [PointF](../../com.aspose.psd/pointf) | 偏移量。 |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 列表
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


获取或设置一个值，指示 [link with layer]。

值： true，如果 [link with layer]；否则， false。

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


获取或设置角度。

值：角度。

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


获取或设置颜色。

值：颜色。

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


填充类型

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


获取或设置水平偏移。

值：水平偏移量。

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


获取或设置一个值，指示此 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 是否已链接。

值： true，如果 linked；否则， false。

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


获取或设置图案数据。

值：图案数据。

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


获取或设置图案的高度。

值：图案的高度。

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


获取或设置图案标识符。

值：图案标识符。

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


获取或设置图案的名称。

值：图案的名称。

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


获取或设置图案的宽度。

值：图案的宽度。

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


获取或设置相位。

值：相位。

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


获取或设置点的类型。

值：点的类型。

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


获取或设置比例。

值：比例。

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


获取或设置垂直偏移量。

值：垂直偏移量。

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


引发值更改。

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


获取或设置一个值，指示 [link with layer]。

值： true，如果 [link with layer]；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


获取或设置角度。

值：角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


获取或设置颜色。

值：颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


获取或设置水平偏移。

值：水平偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


获取或设置一个值，指示此 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 是否已链接。

值： true，如果 linked；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


获取或设置图案数据。

值：图案数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


设置图案的像素缓冲区以及保存时使用的压缩模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| patternData | int[] | 32 位像素，格式为 0xAARRGGBB。 |
| compressionModeOnSave | byte | 用于在保存 PSD 文件时定义图案数据压缩的压缩模式。 |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


获取或设置图案的高度。

值：图案的高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


获取或设置图案标识符。

值：图案标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


获取或设置图案的名称。

值：图案的名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


获取或设置图案的宽度。

值：图案的宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


获取或设置相位。

值：相位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


获取或设置点的类型。

值：点的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


获取或设置比例。

值：比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


获取或设置垂直偏移量。

值：垂直偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


将图案的默认数据设置为 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | 图案填充设置。 |

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


从 [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 实例更新图案属性。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | 带有图案数据的 [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 实例。 |

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

