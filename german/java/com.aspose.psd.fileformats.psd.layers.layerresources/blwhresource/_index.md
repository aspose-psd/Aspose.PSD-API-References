---
title: "BlwhResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Klasse BlwhResource ist eine Ressource der Schwarz‑und‑Weiß‑Einstellungsebene."
type: docs
weight: 15
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

Die Klasse BlwhResource ist eine Ressource der Schwarz‑und‑Weiß‑Einstellungsebene.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Initialisiert eine neue Instanz der [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Liefert oder setzt den Dateinamen der Schwarz-Weiß-Voreinstellung. |
| [getBlues()](#getBlues--) | Liefert oder setzt den Blauwert. |
| [getBwPresetKind()](#getBwPresetKind--) | Liefert oder setzt den Typwert der Schwarz-Weiß-Voreinstellung. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Liest oder setzt den Cyanwert. |
| [getData()](#getData--) | Liest oder setzt die Daten. |
| [getGreens()](#getGreens--) | Liest oder setzt den Grünwert. |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getKey()](#getKey--) | Ermittelt den Schichtressourcen-Schlüssel. |
| [getLength()](#getLength--) | Ermittelt die Länge der Schichtressource in Bytes. |
| [getMagentas()](#getMagentas--) | Liest oder setzt den Magentawert. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ermittelt die Präfixlänge. |
| [getPsdVersion()](#getPsdVersion--) | Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. |
| [getReds()](#getReds--) | Liest oder setzt den Rotwert. |
| [getSignature()](#getSignature--) | Ermittelt die Signatur der Schichtressource. |
| [getTintColor()](#getTintColor--) | Liest die ARGB-Tönfarbe. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Liest oder setzt den Blue Tint Color‑Doppelwert. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Liest oder setzt den Green Tint Color‑Doppelwert. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Liest oder setzt den Red Tint Color‑Doppelwert. |
| [getUseTint()](#getUseTint--) | Liest oder setzt einen Wert, der angibt, ob [tint color] verwendet wird. |
| [getYellows()](#getYellows--) | Liest oder setzt den Gelbwert. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestimmt, ob die Ressource PSB-spezifisch ist. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Speichert die Ressource im angegebenen Stream-Container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Speichert den benutzerdefinierten Ressourcen-Header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Speichert die Header-Signatur, den Bezeichner und die Länge. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Liefert oder setzt den Dateinamen der Schwarz-Weiß-Voreinstellung. |
| [setBlues(int value)](#setBlues-int-) | Liefert oder setzt den Blauwert. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Liefert oder setzt den Typwert der Schwarz-Weiß-Voreinstellung. |
| [setCyans(int value)](#setCyans-int-) | Liest oder setzt den Cyanwert. |
| [setGreens(int value)](#setGreens-int-) | Liest oder setzt den Grünwert. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [setMagentas(int value)](#setMagentas-int-) | Liest oder setzt den Magentawert. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Setzt den Eigenschaftswert nach Typstruktur. |
| [setReds(int value)](#setReds-int-) | Liest oder setzt den Rotwert. |
| [setTintColor(int value)](#setTintColor-int-) | Setzt die Tönfarbe. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Liest oder setzt den Blue Tint Color‑Doppelwert. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Liest oder setzt den Green Tint Color‑Doppelwert. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Liest oder setzt den Red Tint Color‑Doppelwert. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | Liest oder setzt einen Wert, der angibt, ob [tint color] verwendet wird. |
| [setYellows(int value)](#setYellows-int-) | Liest oder setzt den Gelbwert. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Initialisiert eine neue Instanz der [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) Klasse.

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Liefert oder setzt den Dateinamen der Schwarz-Weiß-Voreinstellung.

Wert: Der Dateiname der Schwarz‑Weiß‑Voreinstellung.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Liefert oder setzt den Blauwert.

Wert: Der Blauwert.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Liefert oder setzt den Typwert der Schwarz-Weiß-Voreinstellung.

Wert: Der Wert für die Art der Schwarz‑Weiß‑Voreinstellung.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


Liest oder setzt den Cyanwert.

Wert: Der Cyanwert.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Liest oder setzt den Grünwert.

Wert: Der Grünwert.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Liest oder setzt den Magentawert.

Wert: Der Magentawert.

**Returns:**
int
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


Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen.

**Returns:**
int
### getReds() {#getReds--}
```
public final int getReds()
```


Liest oder setzt den Rotwert.

Wert: Der Rotwert.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ermittelt die Signatur der Schichtressource.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


Liest die ARGB-Tönfarbe.

**Returns:**
int - Die ARGB-Tönfarbe.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Liest oder setzt den Blue Tint Color‑Doppelwert.

Wert: Der Blue Tint Color‑Doppelwert.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Liest oder setzt den Green Tint Color‑Doppelwert.

Wert: Der Green Tint Color‑Doppelwert.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Liest oder setzt den Red Tint Color‑Doppelwert.

Wert: Der Red Tint Color‑Doppelwert.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


Liest oder setzt einen Wert, der angibt, ob [tint color] verwendet wird.

Wert:  true  wenn [tint color] verwendet wird; andernfalls,  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Liest oder setzt den Gelbwert.

Wert: Der Gelbwert.

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


Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert wird. |
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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Liefert oder setzt den Dateinamen der Schwarz-Weiß-Voreinstellung.

Wert: Der Dateiname der Schwarz‑Weiß‑Voreinstellung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Liefert oder setzt den Blauwert.

Wert: Der Blauwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Liefert oder setzt den Typwert der Schwarz-Weiß-Voreinstellung.

Wert: Der Wert für die Art der Schwarz‑Weiß‑Voreinstellung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Liest oder setzt den Cyanwert.

Wert: Der Cyanwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Liest oder setzt den Grünwert.

Wert: Der Grünwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Liest oder setzt den Magentawert.

Wert: Der Magentawert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Setzt den Eigenschaftswert nach Typstruktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Die Struktur. |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Liest oder setzt den Rotwert.

Wert: Der Rotwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Setzt die Tönfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Wert. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Liest oder setzt den Blue Tint Color‑Doppelwert.

Wert: Der Blue Tint Color‑Doppelwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Liest oder setzt den Green Tint Color‑Doppelwert.

Wert: Der Green Tint Color‑Doppelwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Liest oder setzt den Red Tint Color‑Doppelwert.

Wert: Der Red Tint Color‑Doppelwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [tint color] verwendet wird.

Wert:  true  wenn [tint color] verwendet wird; andernfalls,  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Liest oder setzt den Gelbwert.

Wert: Der Gelbwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

