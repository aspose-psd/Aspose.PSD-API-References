---
title: PatternFillSettings
second_title: Aspose.PSD for Java API Reference
description: Pattern fill effect settings
type: docs
weight: 19
url: /java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Pattern fill effect settings
## Constructors

| Constructor | Description |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Initializes a new instance of the [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) class. |
## Fields

| Field | Description |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Generates the LFX2 resource nodes. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Gets or sets a value indicating whether [link with layer]. |
| [getAngle()](#getAngle--) | Gets or sets the angle. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets or sets the color. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | The fill type |
| [getHorizontalOffset()](#getHorizontalOffset--) | Gets or sets the horizontal offset. |
| [getLinked()](#getLinked--) | Gets or sets a value indicating whether this [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) is linked. |
| [getPatternData()](#getPatternData--) | Gets or sets the pattern data. |
| [getPatternHeight()](#getPatternHeight--) | Gets or sets the height of the pattern. |
| [getPatternId()](#getPatternId--) | Gets or sets the pattern identifier. |
| [getPatternName()](#getPatternName--) | Gets or sets the name of the pattern. |
| [getPatternWidth()](#getPatternWidth--) | Gets or sets the width of the pattern. |
| [getPhase_internalized()](#getPhase-internalized--) | Gets or sets the phase. |
| [getPointType()](#getPointType--) | Gets or sets the type of the point. |
| [getScale()](#getScale--) | Gets or sets the scale. |
| [getVerticalOffset()](#getVerticalOffset--) | Gets or sets the vertical offset. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Raises the value changed. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Gets or sets a value indicating whether [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Gets or sets the angle. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Gets or sets the color. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Gets or sets the horizontal offset. |
| [setLinked(boolean value)](#setLinked-boolean-) | Gets or sets a value indicating whether this [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) is linked. |
| [setPatternData(int[] value)](#setPatternData-int---) | Gets or sets the pattern data. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Sets the pattern\\u2019s pixel buffer and the compression mode to use when saving. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Gets or sets the height of the pattern. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Gets or sets the pattern identifier. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Gets or sets the name of the pattern. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Gets or sets the width of the pattern. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Gets or sets the phase. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Gets or sets the type of the point. |
| [setScale(double value)](#setScale-double-) | Gets or sets the scale. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Gets or sets the vertical offset. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Setups the default data of pattern to [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) instance. |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Updates the pattern properties from [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Initializes a new instance of the [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) class.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Generates the LFX2 resource nodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pointType | java.lang.String | Type of the point. |
| color | [Color](../../com.aspose.psd/color) | The color. |
| patternName | java.lang.String | Name of the pattern. |
| identifier | java.lang.String | The identifier. |
| scale | double | The scale. |
| linked | boolean | if set to  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | The offset. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - List of [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Gets or sets a value indicating whether [link with layer].

Value:  true  if [link with layer]; otherwise,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Gets or sets the angle.

Value: The angle.

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


Gets or sets the color.

Value: The color.

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


The fill type

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Gets or sets the horizontal offset.

Value: The horizontal offset.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Gets or sets a value indicating whether this [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) is linked.

Value:  true  if linked; otherwise,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Gets or sets the pattern data.

Value: The pattern data.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Gets or sets the height of the pattern.

Value: The height of the pattern.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Gets or sets the pattern identifier.

Value: The pattern identifier.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Gets or sets the name of the pattern.

Value: The name of the pattern.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Gets or sets the width of the pattern.

Value: The width of the pattern.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Gets or sets the phase.

Value: The phase.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Gets or sets the type of the point.

Value: The type of the point.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Gets or sets the scale.

Value: The scale.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Gets or sets the vertical offset.

Value: The vertical offset.

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


Raises the value changed.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Gets or sets a value indicating whether [link with layer].

Value:  true  if [link with layer]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Gets or sets the angle.

Value: The angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Gets or sets the color.

Value: The color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Gets or sets the horizontal offset.

Value: The horizontal offset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Gets or sets a value indicating whether this [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) is linked.

Value:  true  if linked; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Gets or sets the pattern data.

Value: The pattern data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Sets the pattern\\u2019s pixel buffer and the compression mode to use when saving.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| patternData | int[] | 32-bit pixels in  0xAARRGGBB . |
| compressionModeOnSave | byte | The compression mode used to define the compression of pattern data on psd file save. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Gets or sets the height of the pattern.

Value: The height of the pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Gets or sets the pattern identifier.

Value: The pattern identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Gets or sets the name of the pattern.

Value: The name of the pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Gets or sets the width of the pattern.

Value: The width of the pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Gets or sets the phase.

Value: The phase.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Gets or sets the type of the point.

Value: The type of the point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Gets or sets the scale.

Value: The scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Gets or sets the vertical offset.

Value: The vertical offset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Setups the default data of pattern to [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | The pattern fill settings. |

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


Updates the pattern properties from [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | The [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) instance with pattern data. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

