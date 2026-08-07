---
title: "GrdmResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Klasse GrdmResource."
type: docs
weight: 35
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

Klasse GrdmResource. Enthält Informationen über die Gradient-Map-Ebene.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | Initialisiert eine neue Instanz der [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | Die Standard-Skala. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Die PSB‑Header‑Version |
| [PsbResourceSignature](#PsbResourceSignature) | Die PSB‑spezifische Ressourcen‑Signatur. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Die PSD‑Header‑Version |
| [ResourceSignature](#ResourceSignature) | Die allgemeine Ressourcen‑Signatur. |
| [TypeToolKey](#TypeToolKey) | Der Typ-Tool-Info-Schlüssel. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Die Venture-Lizenz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Farbmodell. |
| [getColorPoints()](#getColorPoints--) | Liest oder setzt die Farbpunkte. |
| [getData()](#getData--) | Liest oder setzt die Daten. |
| [getDither()](#getDither--) | Ist der Gradient gerastert. |
| [getExpansionCount()](#getExpansionCount--) | Erweiterungsanzahl ( = 2 für Photoshop 6.0). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | Länge(= 32 für Photoshop 6.0) Keine Information darüber, wofür sie verantwortlich ist. |
| [getGradientMode()](#getGradientMode--) | Modus für diesen Farbverlauf bestimmt 'Gradient Type' = 'Solid/Noise' (0/1). |
| [getGradientName()](#getGradientName--) | Name des Farbverlaufs: Unicode-Zeichenkette, gepolstert. |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getInterpolation()](#getInterpolation--) | Interpolation. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Liest oder setzt die Interpolationsmethode für den Verlauf. |
| [getKey()](#getKey--) | Ermittelt den Schichtressourcen-Schlüssel. |
| [getLength()](#getLength--) | Ermittelt die Länge der Schichtressource in Bytes. |
| [getMaximumColor()](#getMaximumColor--) | Maximale Farbe des PixelDataFormat.Rgba64Bpp-Formats. |
| [getMinimumColor()](#getMinimumColor--) | Minimale Farbe des PixelDataFormat.Rgba64Bpp-Formats. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ermittelt die Präfixlänge. |
| [getPsdVersion()](#getPsdVersion--) | Ermittelt die minimale PSD-Version, die für diese Ressource erforderlich ist. |
| [getReverse()](#getReverse--) | Ist der Farbverlauf umgekehrt. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Der Zufallszahl-Seed, der zum Erzeugen von Farben für den Rauschverlauf verwendet wird. |
| [getRoughness()](#getRoughness--) | Rauheitsfaktor Wenn 'Gradient type' = 'Noise', können wir 'Roughness' (0 - 2048) zuweisen. |
| [getShowTransparency()](#getShowTransparency--) | Flag zum Anzeigen von Transparenz Wenn 'Gradient type' = 'Noise', können wir 'Add transparency' auf true setzen. |
| [getSignature()](#getSignature--) | Ermittelt die Signatur der Schichtressource. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Liest oder setzt die Transparenzpunkte. |
| [getUseVectorColor()](#getUseVectorColor--) | Flag für die Verwendung von Vektorfarbe. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | Initialisiert die Länge des Farbverlaufs. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestimmt, ob die Ressource PSB-spezifisch ist. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Speichert Ressourcendaten im angegebenen Stream-Container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Speichert den benutzerdefinierten Ressourcen-Header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Speichert die Header-Signatur, den Bezeichner und die Länge. |
| [setColorModel(short value)](#setColorModel-short-) | Farbmodell. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Liest oder setzt die Farbpunkte. |
| [setDither(boolean value)](#setDither-boolean-) | Ist der Gradient gerastert. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Erweiterungsanzahl ( = 2 für Photoshop 6.0). |
| [setGradientMode(int value)](#setGradientMode-int-) | Modus für diesen Farbverlauf bestimmt 'Gradient Type' = 'Solid/Noise' (0/1). |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Name des Farbverlaufs: Unicode-Zeichenkette, gepolstert. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolation. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Liest oder setzt die Interpolationsmethode für den Verlauf. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Maximale Farbe des PixelDataFormat.Rgba64Bpp-Formats. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Minimale Farbe des PixelDataFormat.Rgba64Bpp-Formats. |
| [setReverse(boolean value)](#setReverse-boolean-) | Ist der Farbverlauf umgekehrt. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Der Zufallszahl-Seed, der zum Erzeugen von Farben für den Rauschverlauf verwendet wird. |
| [setRoughness(int value)](#setRoughness-int-) | Rauheitsfaktor Wenn 'Gradient type' = 'Noise', können wir 'Roughness' (0 - 2048) zuweisen. |
| [setShowTransparency(short value)](#setShowTransparency-short-) | Flag zum Anzeigen von Transparenz Wenn 'Gradient type' = 'Noise', können wir 'Add transparency' auf true setzen. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Liest oder setzt die Transparenzpunkte. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | Flag für die Verwendung von Vektorfarbe. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


Initialisiert eine neue Instanz der [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdVersion | int | Die PSD-Version der Ressource. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


Die Standard-Skala.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Die PSB‑Header‑Version

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Die PSB‑spezifische Ressourcen‑Signatur.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Die PSD‑Header‑Version

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Die allgemeine Ressourcen‑Signatur.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Der Typ-Tool-Info-Schlüssel.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Die Venture-Lizenz.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. Einige Ressourcen werden derzeit nicht erkannt, aber wir haben eine vollständige Liste von PSB-spezifischen Ressourcen, die ihr Verhalten beim Speichern ändern. Daher müssen wir dies zumindest in UnknownResource überprüfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | int | Der Schlüssel. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Farbmodell. Wenn 'Gradient type' = 'Noise', können wir 'Color Model' auf RGB/SHB/LAB (3/4/6) setzen.

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Liest oder setzt die Farbpunkte.

Wert: Die Farbpunkte.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Ist der Gradient gerastert.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Erweiterungsanzahl ( = 2 für Photoshop 6.0).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


Länge(= 32 für Photoshop 6.0) Keine Information darüber, wofür sie verantwortlich ist.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Modus für diesen Farbverlauf bestimmt 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Name des Farbverlaufs: Unicode-Zeichenkette, gepolstert.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolation. Bestimmt die Glätte, wenn 'Gradient Type' = 'Solid' (GradientMode = 0).

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Liest oder setzt die Interpolationsmethode für den Verlauf.

**Returns:**
long
### getKey() {#getKey--}
```
public final int getKey()
```


Ermittelt den Schichtressourcen-Schlüssel.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Ermittelt die Länge der Schichtressource in Bytes.

**Returns:**
int
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Maximale Farbe des PixelDataFormat.Rgba64Bpp-Formats. Die Farbe hat ARGB-Kanäle, jeder Kanal ist 16 Bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Minimale Farbe des PixelDataFormat.Rgba64Bpp-Formats. Die Farbe hat ARGB-Kanäle, jeder Kanal ist 16 Bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Ermittelt die Präfixlänge. Standardwert ist 12 für 8BIM-Ressourcen und 16 für 8B64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdVersion | int | Die PSD‑Version. |

**Returns:**
int - Die Präfixlänge.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Ermittelt die minimale PSD-Version, die für diese Ressource erforderlich ist. Version 3 wird benötigt, wenn die Interpolationsmethode explizit gespeichert wird.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Ist der Farbverlauf umgekehrt.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Der Zufallszahl-Seed, der zum Erzeugen von Farben für den Rauschverlauf verwendet wird.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Rauheitsfaktor Wenn 'Gradient type' = 'Noise', können wir 'Roughness' (0 - 2048) zuweisen.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


Flag zum Anzeigen von Transparenz Wenn 'Gradient type' = 'Noise', können wir 'Add transparency' auf true setzen.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ermittelt die Signatur der Schichtressource.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Liest oder setzt die Transparenzpunkte.

Wert: Die Transparenzpunkte.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


Flag für die Verwendung von Vektorfarbe.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


Initialisiert die Länge des Farbverlaufs. GradientLength ist schreibgeschützt, sodass es nur einmal zugewiesen werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | Der Wert. |

### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Bestimmt, ob die Ressource PSB-spezifisch ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | int | Der Ressourcen-Schlüssel. |

**Returns:**
boolean -  true  wenn die Ressource PSB-spezifisch ist; andernfalls  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist.

Wert:  true  wenn diese Instanz ressourcen-PSB-spezifisch ist; andernfalls  false .

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


Speichert Ressourcendaten im angegebenen Stream-Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| psdVersion | int | Die PSD‑Version. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Speichert den benutzerdefinierten Ressourcen-Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| Signatur | int | Die Signatur. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Speichert die Header-Signatur, den Bezeichner und die Länge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| Signatur | int | Die Signatur. |
| isLengthLong | boolean | wenn auf  true  gesetzt, ist die Länge lang. |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Farbmodell. Wenn 'Gradient type' = 'Noise', können wir 'Color Model' auf RGB/SHB/LAB (3/4/6) setzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Liest oder setzt die Farbpunkte.

Wert: Die Farbpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Ist der Gradient gerastert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Erweiterungsanzahl ( = 2 für Photoshop 6.0).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Modus für diesen Farbverlauf bestimmt 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Name des Farbverlaufs: Unicode-Zeichenkette, gepolstert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolation. Bestimmt die Glätte, wenn 'Gradient Type' = 'Solid' (GradientMode = 0).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Liest oder setzt die Interpolationsmethode für den Verlauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Maximale Farbe des PixelDataFormat.Rgba64Bpp-Formats. Die Farbe hat ARGB-Kanäle, jeder Kanal ist 16 Bit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Minimale Farbe des PixelDataFormat.Rgba64Bpp-Formats. Die Farbe hat ARGB-Kanäle, jeder Kanal ist 16 Bit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Ist der Farbverlauf umgekehrt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Der Zufallszahl-Seed, der zum Erzeugen von Farben für den Rauschverlauf verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Rauheitsfaktor Wenn 'Gradient type' = 'Noise', können wir 'Roughness' (0 - 2048) zuweisen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


Flag zum Anzeigen von Transparenz Wenn 'Gradient type' = 'Noise', können wir 'Add transparency' auf true setzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Liest oder setzt die Transparenzpunkte.

Wert: Die Transparenzpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


Flag für die Verwendung von Vektorfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
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

