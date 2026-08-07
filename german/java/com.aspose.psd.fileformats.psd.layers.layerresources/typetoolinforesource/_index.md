---
title: "TypeToolInfoResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Informationen zum Typwerkzeug."
type: docs
weight: 79
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

Die Type-Tool-Information. Für PSD-Versionen unter 6.0.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | Initialisiert eine neue Instanz der [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource)-Klasse. |
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
| [getAComponent()](#getAComponent--) | Liest oder setzt eine Komponente. |
| [getBComponent()](#getBComponent--) | Liest oder setzt die b-Komponente. |
| [getCharacterCount()](#getCharacterCount--) | Liest oder setzt die Zeichenanzahl. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | Liest oder setzt den Farbraumwert. |
| [getFontVersion()](#getFontVersion--) | Liest oder setzt die Schriftversion. |
| [getFonts()](#getFonts--) | Liest oder setzt die Schriftarten. |
| [getFontsCount()](#getFontsCount--) | Liest die Anzahl der Schriftarten. |
| [getGComponent()](#getGComponent--) | Liest oder setzt die g-Komponente. |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | Liest oder setzt die horizontale Platzierung. |
| [getKey()](#getKey--) | Ermittelt den Schichtressourcen-Schlüssel. |
| [getLength()](#getLength--) | Ermittelt die Länge der Schichtressource in Bytes. |
| [getLineCount()](#getLineCount--) | Liest die Zeilenanzahl. |
| [getLines()](#getLines--) | Liest oder setzt die Zeilen. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ermittelt die Präfixlänge. |
| [getPsdVersion()](#getPsdVersion--) | Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. |
| [getRComponent()](#getRComponent--) | Liest oder setzt die r-Komponente. |
| [getScaleFactor()](#getScaleFactor--) | Liest oder setzt den Skalierungsfaktor. |
| [getSelectionEnd()](#getSelectionEnd--) | Liest oder setzt das Ende der Auswahl. |
| [getSelectionStart()](#getSelectionStart--) | Liest oder setzt den Anfang der Auswahl. |
| [getSignature()](#getSignature--) | Ermittelt die Signatur der Schichtressource. |
| [getStyles()](#getStyles--) | Liest oder setzt die Schriftstile. |
| [getStylesCount()](#getStylesCount--) | Liest die Anzahl der Stile. |
| [getTransformMatrix()](#getTransformMatrix--) | Liest oder setzt die Transformationsmatrix. |
| [getTypeValue()](#getTypeValue--) | Liest oder setzt den Typwert. |
| [getVersion()](#getVersion--) | Liest oder setzt die Version. |
| [getVerticalPlacement()](#getVerticalPlacement--) | Liest oder setzt die vertikale Platzierung. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestimmt, ob die Ressource PSB-spezifisch ist. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Speichert den angegebenen Stream-Container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Speichert den benutzerdefinierten Ressourcen-Header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Speichert die Header-Signatur, den Bezeichner und die Länge. |
| [setAComponent(short value)](#setAComponent-short-) | Liest oder setzt eine Komponente. |
| [setBComponent(short value)](#setBComponent-short-) | Liest oder setzt die b-Komponente. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | Liest oder setzt die Zeichenanzahl. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | Liest oder setzt die rohen Farbdaten. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | Liest oder setzt den Farbraumwert. |
| [setFontVersion(short value)](#setFontVersion-short-) | Liest oder setzt die Schriftversion. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | Liest oder setzt die Schriftarten. |
| [setGComponent(short value)](#setGComponent-short-) | Liest oder setzt die g-Komponente. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | Liest oder setzt die horizontale Platzierung. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | Liest oder setzt die Zeilen. |
| [setRComponent(short value)](#setRComponent-short-) | Liest oder setzt die r-Komponente. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | Liest oder setzt den Skalierungsfaktor. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | Liest oder setzt das Ende der Auswahl. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | Liest oder setzt den Anfang der Auswahl. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | Liest oder setzt die Schriftstile. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Liest oder setzt die Transformationsmatrix. |
| [setTypeValue(short value)](#setTypeValue-short-) | Liest oder setzt den Typwert. |
| [setVersion(short value)](#setVersion-short-) | Liest oder setzt die Version. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | Liest oder setzt die vertikale Platzierung. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


Initialisiert eine neue Instanz der [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource)-Klasse.

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


Liest oder setzt eine Komponente.

Wert: eine Komponente.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


Liest oder setzt die b-Komponente.

Wert: Die b-Komponente.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


Liest oder setzt die Zeichenanzahl.

Wert: Die Zeichenanzahl.

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


Liest oder setzt den Farbraumwert.

Wert: Der Farbraumwert.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


Liest oder setzt die Schriftversion.

Wert: Die Schriftartversion.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


Liest oder setzt die Schriftarten.

Wert: Die Schriftarten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


Liest die Anzahl der Schriftarten.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


Liest oder setzt die g-Komponente.

Wert: Die g-Komponente.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


Liest oder setzt die horizontale Platzierung.

Wert: Die horizontale Platzierung.

**Returns:**
int
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
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


Liest die Zeilenanzahl.

Wert: Die Zeilenanzahl.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


Liest oder setzt die Zeilen.

Wert: Die Zeilen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
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
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


Liest oder setzt die r-Komponente.

Wert: Die r-Komponente.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


Liest oder setzt den Skalierungsfaktor.

Wert: Der Skalierungsfaktor.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


Liest oder setzt das Ende der Auswahl.

Wert: Das Auswahlende.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


Liest oder setzt den Anfang der Auswahl.

Wert: Der Auswahlbeginn.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ermittelt die Signatur der Schichtressource.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


Liest oder setzt die Schriftstile.

Wert: Die Schriftstile.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


Liest die Anzahl der Stile.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Liest oder setzt die Transformationsmatrix.

Wert: Die Transformationsmatrix.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


Liest oder setzt den Typwert.

Wert: Der Typwert.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Liest oder setzt die Version.

Wert: Die Version.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


Liest oder setzt die vertikale Platzierung.

Wert: Die vertikale Platzierung.

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


Speichert den angegebenen Stream-Container.

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

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


Liest oder setzt eine Komponente.

Wert: eine Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


Liest oder setzt die b-Komponente.

Wert: Die b-Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


Liest oder setzt die Zeichenanzahl.

Wert: Die Zeichenanzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


Liest oder setzt die rohen Farbdaten.

Wert: Die rohen Farbdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


Liest oder setzt den Farbraumwert.

Wert: Der Farbraumwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


Liest oder setzt die Schriftversion.

Wert: Die Schriftartversion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


Liest oder setzt die Schriftarten.

Wert: Die Schriftarten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


Liest oder setzt die g-Komponente.

Wert: Die g-Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

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

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


Liest oder setzt die horizontale Platzierung.

Wert: Die horizontale Platzierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


Liest oder setzt die Zeilen.

Wert: Die Zeilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


Liest oder setzt die r-Komponente.

Wert: Die r-Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


Liest oder setzt den Skalierungsfaktor.

Wert: Der Skalierungsfaktor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


Liest oder setzt das Ende der Auswahl.

Wert: Das Auswahlende.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


Liest oder setzt den Anfang der Auswahl.

Wert: Der Auswahlbeginn.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


Liest oder setzt die Schriftstile.

Wert: Die Schriftstile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Liest oder setzt die Transformationsmatrix.

Wert: Die Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


Liest oder setzt den Typwert.

Wert: Der Typwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Liest oder setzt die Version.

Wert: Die Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


Liest oder setzt die vertikale Platzierung.

Wert: Die vertikale Platzierung.

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

