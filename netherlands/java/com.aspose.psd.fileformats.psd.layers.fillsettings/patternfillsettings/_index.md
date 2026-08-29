---
title: "PatternFillSettings"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Patroonvul-effectinstellingen"
type: docs
weight: 20
url: /nl/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Patroonvul-effectinstellingen
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Initialiseert een nieuw exemplaar van de klasse [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Genereert de LFX2 resource‑knooppunten. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Haalt een waarde op of stelt deze in die aangeeft of [link with layer]. |
| [getAngle()](#getAngle--) | Haalt de hoek op of stelt deze in. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Haalt de kleur op of stelt deze in. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Het vultype |
| [getHorizontalOffset()](#getHorizontalOffset--) | Haalt de horizontale offset op of stelt deze in. |
| [getLinked()](#getLinked--) | Haalt een waarde op of stelt deze in die aangeeft of deze [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) gekoppeld is. |
| [getPatternData()](#getPatternData--) | Haalt de patroongegevens op of stelt deze in. |
| [getPatternHeight()](#getPatternHeight--) | Haalt de hoogte van het patroon op of stelt deze in. |
| [getPatternId()](#getPatternId--) | Haalt de patroon‑identificatie op of stelt deze in. |
| [getPatternName()](#getPatternName--) | Haalt de naam van het patroon op of stelt deze in. |
| [getPatternWidth()](#getPatternWidth--) | Haalt de breedte van het patroon op of stelt deze in. |
| [getPhase_internalized()](#getPhase-internalized--) | Haalt de fase op of stelt deze in. |
| [getPointType()](#getPointType--) | Haalt het type van het punt op of stelt dit in. |
| [getScale()](#getScale--) | Geeft of stelt de schaal in. |
| [getVerticalOffset()](#getVerticalOffset--) | Haalt de verticale offset op of stelt deze in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Activeert de waarde gewijzigd. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Haalt de hoek op of stelt deze in. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Haalt de kleur op of stelt deze in. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Haalt de horizontale offset op of stelt deze in. |
| [setLinked(boolean value)](#setLinked-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of deze [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) gekoppeld is. |
| [setPatternData(int[] value)](#setPatternData-int---) | Haalt de patroongegevens op of stelt deze in. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Stelt de pixelbuffer van het patroon en de compressiemodus in die bij het opslaan moet worden gebruikt. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Haalt de hoogte van het patroon op of stelt deze in. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Haalt de patroon‑identificatie op of stelt deze in. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Haalt de naam van het patroon op of stelt deze in. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Haalt de breedte van het patroon op of stelt deze in. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Haalt de fase op of stelt deze in. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Haalt het type van het punt op of stelt dit in. |
| [setScale(double value)](#setScale-double-) | Geeft of stelt de schaal in. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Haalt de verticale offset op of stelt deze in. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Stelt de standaardgegevens van het patroon in op een [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)‑instantie. |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Werk de patroon‑eigenschappen bij vanuit een [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)‑instantie. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Initialiseert een nieuw exemplaar van de klasse [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Genereert de LFX2 resource‑knooppunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pointType | java.lang.String | Type van het punt. |
| color | [Color](../../com.aspose.psd/color) | De kleur. |
| patternName | java.lang.String | Naam van het patroon. |
| identificatie | java.lang.String | De identificatie. |
| scale | double | De schaal. |
| gelinkt | boolean | als ingesteld op  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | De offset. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Lijst van [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Haalt een waarde op of stelt deze in die aangeeft of [link with layer].

Waarde:  true  als [link with layer]; anders,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Haalt de hoek op of stelt deze in.

Waarde: De hoek.

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


Haalt de kleur op of stelt deze in.

Waarde: De kleur.

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


Het vultype

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Haalt de horizontale offset op of stelt deze in.

Waarde: De horizontale offset.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Haalt een waarde op of stelt deze in die aangeeft of deze [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) gekoppeld is.

Waarde:  true  als gelinkt; anders,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Haalt de patroongegevens op of stelt deze in.

Waarde: De patroongegevens.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Haalt de hoogte van het patroon op of stelt deze in.

Waarde: De hoogte van het patroon.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Haalt de patroon‑identificatie op of stelt deze in.

Waarde: De patroonidentificatie.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Haalt de naam van het patroon op of stelt deze in.

Waarde: De naam van het patroon.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Haalt de breedte van het patroon op of stelt deze in.

Waarde: De breedte van het patroon.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Haalt de fase op of stelt deze in.

Waarde: De fase.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Haalt het type van het punt op of stelt dit in.

Waarde: Het type van het punt.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Geeft of stelt de schaal in.

Waarde: De schaal.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Haalt de verticale offset op of stelt deze in.

Waarde: De verticale offset.

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


Activeert de waarde gewijzigd.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of [link with layer].

Waarde:  true  als [link with layer]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Haalt de hoek op of stelt deze in.

Waarde: De hoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Haalt de kleur op of stelt deze in.

Waarde: De kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Haalt de horizontale offset op of stelt deze in.

Waarde: De horizontale offset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of deze [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) gekoppeld is.

Waarde:  true  als gelinkt; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Haalt de patroongegevens op of stelt deze in.

Waarde: De patroongegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Stelt de pixelbuffer van het patroon en de compressiemodus in die bij het opslaan moet worden gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| patternData | int[] | 32-bit pixels in  0xAARRGGBB . |
| compressionModeOnSave | byte | De compressiemodus die wordt gebruikt om de compressie van patroongegevens bij het opslaan van een psd-bestand te definiëren. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Haalt de hoogte van het patroon op of stelt deze in.

Waarde: De hoogte van het patroon.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Haalt de patroon‑identificatie op of stelt deze in.

Waarde: De patroonidentificatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Haalt de naam van het patroon op of stelt deze in.

Waarde: De naam van het patroon.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Haalt de breedte van het patroon op of stelt deze in.

Waarde: De breedte van het patroon.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Haalt de fase op of stelt deze in.

Waarde: De fase.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Haalt het type van het punt op of stelt dit in.

Waarde: Het type van het punt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Geeft of stelt de schaal in.

Waarde: De schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Haalt de verticale offset op of stelt deze in.

Waarde: De verticale offset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Stelt de standaardgegevens van het patroon in op een [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)‑instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | De patroonvullingsinstellingen. |

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


Werk de patroon‑eigenschappen bij vanuit een [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)‑instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | De [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) instantie met patroongegevens. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

