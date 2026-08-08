---
title: "PatternFillSettings"
second_title: "Aspose.PSD för Java API-referens"
description: "Mönsterfyllningseffektinställningar"
type: docs
weight: 20
url: /sv/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Mönsterfyllningseffektinställningar
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Initierar en ny instans av klassen [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Genererar LFX2-resursnoderna. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Hämtar eller anger ett värde som indikerar om [link with layer]. |
| [getAngle()](#getAngle--) | Hämtar eller anger vinkeln. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Hämtar eller anger färgen. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Fylltypen |
| [getHorizontalOffset()](#getHorizontalOffset--) | Hämtar eller anger den horisontella förskjutningen. |
| [getLinked()](#getLinked--) | Hämtar eller anger ett värde som indikerar om denna [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) är länkad. |
| [getPatternData()](#getPatternData--) | Hämtar eller anger mönsterdata. |
| [getPatternHeight()](#getPatternHeight--) | Hämtar eller anger mönstrets höjd. |
| [getPatternId()](#getPatternId--) | Hämtar eller anger mönsteridentifieraren. |
| [getPatternName()](#getPatternName--) | Hämtar eller anger mönstrets namn. |
| [getPatternWidth()](#getPatternWidth--) | Hämtar eller anger mönstrets bredd. |
| [getPhase_internalized()](#getPhase-internalized--) | Hämtar eller anger fasen. |
| [getPointType()](#getPointType--) | Hämtar eller anger typen av punkten. |
| [getScale()](#getScale--) | Hämtar eller anger skalan. |
| [getVerticalOffset()](#getVerticalOffset--) | Hämtar eller anger den vertikala förskjutningen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Utlöser värdeändring. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Hämtar eller anger ett värde som indikerar om [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Hämtar eller anger vinkeln. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Hämtar eller anger färgen. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Hämtar eller anger den horisontella förskjutningen. |
| [setLinked(boolean value)](#setLinked-boolean-) | Hämtar eller anger ett värde som indikerar om denna [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) är länkad. |
| [setPatternData(int[] value)](#setPatternData-int---) | Hämtar eller anger mönsterdata. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Anger mönstrets pixelbuffert och komprimeringsläget som ska användas vid sparande. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Hämtar eller anger mönstrets höjd. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Hämtar eller anger mönsteridentifieraren. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Hämtar eller anger mönstrets namn. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Hämtar eller anger mönstrets bredd. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Hämtar eller anger fasen. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Hämtar eller anger typen av punkten. |
| [setScale(double value)](#setScale-double-) | Hämtar eller anger skalan. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Hämtar eller anger den vertikala förskjutningen. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Ställer in standarddata för mönstret till [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) instans. |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Uppdaterar mönsteregenskaperna från [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) instans. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Initierar en ny instans av klassen [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Genererar LFX2-resursnoderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pointType | java.lang.String | Punktens typ. |
| color | [Color](../../com.aspose.psd/color) | Färgen. |
| patternName | java.lang.String | Mönstrets namn. |
| identifier | java.lang.String | Identifieraren. |
| skala | double | Skalan. |
| linked | boolean | om satt till  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | Förskjutningen. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Lista över [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Hämtar eller anger ett värde som indikerar om [link with layer].

Värde:  true  om [länk med lager]; annars,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Hämtar eller anger vinkeln.

Värde: Vinkeln.

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


Hämtar eller anger färgen.

Värde: Färgen.

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


Fylltypen

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Hämtar eller anger den horisontella förskjutningen.

Värde: Den horisontella förskjutningen.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Hämtar eller anger ett värde som indikerar om denna [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) är länkad.

Värde:  true  om länkat; annars,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Hämtar eller anger mönsterdata.

Värde: Mönsterdata.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Hämtar eller anger mönstrets höjd.

Värde: Mönstrets höjd.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Hämtar eller anger mönsteridentifieraren.

Värde: Mönsteridentifieraren.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Hämtar eller anger mönstrets namn.

Värde: Namnet på mönstret.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Hämtar eller anger mönstrets bredd.

Värde: Mönstrets bredd.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Hämtar eller anger fasen.

Värde: Fas.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Hämtar eller anger typen av punkten.

Värde: Punktens typ.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Hämtar eller anger skalan.

Värde: Skalan.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Hämtar eller anger den vertikala förskjutningen.

Värde: Den vertikala förskjutningen.

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


Utlöser värdeändring.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Hämtar eller anger ett värde som indikerar om [link with layer].

Värde:  true  om [länk med lager]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Hämtar eller anger vinkeln.

Värde: Vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Hämtar eller anger färgen.

Värde: Färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Hämtar eller anger den horisontella förskjutningen.

Värde: Den horisontella förskjutningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) är länkad.

Värde:  true  om länkat; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Hämtar eller anger mönsterdata.

Värde: Mönsterdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Anger mönstrets pixelbuffert och komprimeringsläget som ska användas vid sparande.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| patternData | int[] | 32-bitars pixlar i  0xAARRGGBB . |
| compressionModeOnSave | byte | Komprimeringsläget som används för att definiera komprimeringen av mönsterdata vid sparning av psd‑fil. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Hämtar eller anger mönstrets höjd.

Värde: Mönstrets höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Hämtar eller anger mönsteridentifieraren.

Värde: Mönsteridentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Hämtar eller anger mönstrets namn.

Värde: Namnet på mönstret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Hämtar eller anger mönstrets bredd.

Värde: Mönstrets bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Hämtar eller anger fasen.

Värde: Fas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Hämtar eller anger typen av punkten.

Värde: Punktens typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Hämtar eller anger skalan.

Värde: Skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Hämtar eller anger den vertikala förskjutningen.

Värde: Den vertikala förskjutningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Ställer in standarddata för mönstret till [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Mönsterfyllningsinställningarna. |

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


Uppdaterar mönsteregenskaperna från [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Instansen av [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) med mönsterdata. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

