---
title: "PatternFillSettings"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Musterfüllungseffekt-Einstellungen"
type: docs
weight: 20
url: /de/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Musterfüllungseffekt-Einstellungen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Initialisiert eine neue Instanz der [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Erzeugt die LFX2-Ressourcenknoten. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Liest oder setzt einen Wert, der angibt, ob [link with layer]. |
| [getAngle()](#getAngle--) | Liest oder setzt den Winkel. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Liest oder setzt die Farbe. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Der Fülltyp |
| [getHorizontalOffset()](#getHorizontalOffset--) | Liest oder setzt den horizontalen Versatz. |
| [getLinked()](#getLinked--) | Liest oder setzt einen Wert, der angibt, ob diese [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) verknüpft ist. |
| [getPatternData()](#getPatternData--) | Liest oder setzt die Musterdaten. |
| [getPatternHeight()](#getPatternHeight--) | Liest oder setzt die Höhe des Musters. |
| [getPatternId()](#getPatternId--) | Liest oder setzt die Musterkennung. |
| [getPatternName()](#getPatternName--) | Liest oder setzt den Namen des Musters. |
| [getPatternWidth()](#getPatternWidth--) | Liest oder setzt die Breite des Musters. |
| [getPhase_internalized()](#getPhase-internalized--) | Liest oder setzt die Phase. |
| [getPointType()](#getPointType--) | Liest oder setzt den Typ des Punktes. |
| [getScale()](#getScale--) | Liest oder setzt die Skalierung. |
| [getVerticalOffset()](#getVerticalOffset--) | Liest oder setzt den vertikalen Versatz. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Löst die Wertänderung aus. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Liest oder setzt einen Wert, der angibt, ob [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Liest oder setzt den Winkel. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Liest oder setzt die Farbe. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Liest oder setzt den horizontalen Versatz. |
| [setLinked(boolean value)](#setLinked-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) verknüpft ist. |
| [setPatternData(int[] value)](#setPatternData-int---) | Liest oder setzt die Musterdaten. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Legt den Pixelpuffer von pattern\\u2019s und den beim Speichern zu verwendenden Komprimierungsmodus fest. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Liest oder setzt die Höhe des Musters. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Liest oder setzt die Musterkennung. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Liest oder setzt den Namen des Musters. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Liest oder setzt die Breite des Musters. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Liest oder setzt die Phase. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Liest oder setzt den Typ des Punktes. |
| [setScale(double value)](#setScale-double-) | Liest oder setzt die Skalierung. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Liest oder setzt den vertikalen Versatz. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Richtet die Standarddaten des Musters für die [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)-Instanz ein. |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Aktualisiert die Mustereigenschaften aus der [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)-Instanz. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Initialisiert eine neue Instanz der [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)-Klasse.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Erzeugt die LFX2-Ressourcenknoten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pointType | java.lang.String | Typ des Punktes. |
| color | [Color](../../com.aspose.psd/color) | Die Farbe. |
| patternName | java.lang.String | Name des Musters. |
| Kennung | java.lang.String | Der Bezeichner. |
| Skala | double | Die Skalierung. |
| verknüpft | boolean | wenn auf  true  [linked] gesetzt ist. |
| offset | [PointF](../../com.aspose.psd/pointf) | Der Versatz. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Liste von [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Liest oder setzt einen Wert, der angibt, ob [link with layer].

Wert:  true  wenn [link with layer]; andernfalls,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Liest oder setzt den Winkel.

Wert: Der Winkel.

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


Liest oder setzt die Farbe.

Wert: Die Farbe.

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


Der Fülltyp

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Liest oder setzt den horizontalen Versatz.

Wert: Der horizontale Versatz.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Liest oder setzt einen Wert, der angibt, ob diese [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) verknüpft ist.

Wert:  true  wenn verknüpft; andernfalls,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Liest oder setzt die Musterdaten.

Wert: Die Musterdaten.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Liest oder setzt die Höhe des Musters.

Wert: Die Höhe des Musters.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Liest oder setzt die Musterkennung.

Wert: Der Musterbezeichner.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Liest oder setzt den Namen des Musters.

Wert: Der Name des Musters.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Liest oder setzt die Breite des Musters.

Wert: Die Breite des Musters.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Liest oder setzt die Phase.

Wert: Die Phase.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Liest oder setzt den Typ des Punktes.

Wert: Der Typ des Punktes.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Liest oder setzt die Skalierung.

Wert: Die Skalierung.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Liest oder setzt den vertikalen Versatz.

Wert: Der vertikale Versatz.

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


Löst die Wertänderung aus.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [link with layer].

Wert:  true  wenn [link with layer]; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Liest oder setzt den Winkel.

Wert: Der Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Liest oder setzt die Farbe.

Wert: Die Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Liest oder setzt den horizontalen Versatz.

Wert: Der horizontale Versatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) verknüpft ist.

Wert:  true  wenn verknüpft; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Liest oder setzt die Musterdaten.

Wert: Die Musterdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Legt den Pixelpuffer von pattern\\u2019s und den beim Speichern zu verwendenden Komprimierungsmodus fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| patternData | int[] | 32-Bit-Pixel in  0xAARRGGBB . |
| compressionModeOnSave | byte | Der Komprimierungsmodus, der verwendet wird, um die Komprimierung von Musterdaten beim Speichern einer PSD-Datei zu definieren. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Liest oder setzt die Höhe des Musters.

Wert: Die Höhe des Musters.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Liest oder setzt die Musterkennung.

Wert: Der Musterbezeichner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Liest oder setzt den Namen des Musters.

Wert: Der Name des Musters.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Liest oder setzt die Breite des Musters.

Wert: Die Breite des Musters.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Liest oder setzt die Phase.

Wert: Die Phase.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Liest oder setzt den Typ des Punktes.

Wert: Der Typ des Punktes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Liest oder setzt die Skalierung.

Wert: Die Skalierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Liest oder setzt den vertikalen Versatz.

Wert: Der vertikale Versatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Richtet die Standarddaten des Musters für die [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)-Instanz ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Die Pattern-Füllungseinstellungen. |

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


Aktualisiert die Mustereigenschaften aus der [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)-Instanz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Die [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) Instanz mit Musterdaten. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

