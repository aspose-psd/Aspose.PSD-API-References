---
title: "Txt2Resource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Txt2 Ressourcenklasse"
type: docs
weight: 76
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class Txt2Resource extends LayerResource
```

Txt2 Ressourcenklasse
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Txt2Resource()](#Txt2Resource--) | Initialisiert eine neue Instanz der [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource) Klasse. |
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
| [addTextRecord(String text, RectangleF bounds)](#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-) | Fügt den Textdatensatz zu Resource hinzu und gibt die ID des Textdatensatzes zurück. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Liest oder setzt die Daten. |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getKey()](#getKey--) | Ermittelt den Schichtressourcen-Schlüssel. |
| [getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | Ermittelt, ob die Resource komprimiert ist. |
| [getLength()](#getLength--) | Ermittelt die Länge der Schichtressource in Bytes. |
| [getParsedTxt2Model_internalized()](#getParsedTxt2Model-internalized--) | Parst die txt2-Daten in eine Txt2DataRoot Klasseninstanz. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ermittelt die Präfixlänge. |
| [getPsdVersion()](#getPsdVersion--) | Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. |
| [getSignature()](#getSignature--) | Ermittelt die Signatur der Schichtressource. |
| [getTextData()](#getTextData--) | Liest den Textdatensatz aus den Resource-Daten. |
| [getText_internalized()](#getText-internalized--) | Liest oder setzt den Namen. |
| [getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | Liest das TXT2 aus dem geparsten Baum. |
| [getTxt2ParsedTree_internalized()](#getTxt2ParsedTree-internalized--) | Liest den geparsten TXT2-Baum. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestimmt, ob die Ressource PSB-spezifisch ist. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTextRecord_internalized(int textIndex)](#removeTextRecord-internalized-int-) | Entfernt den Textdatensatz aus Resource. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Speichert den angegebenen Stream-Container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Speichert den benutzerdefinierten Ressourcen-Header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Speichert die Header-Signatur, den Bezeichner und die Länge. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt die Daten. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [setText_internalized(String value)](#setText-internalized-java.lang.String-) | Liest oder setzt den Namen. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)](#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-) | Aktualisiert den Textdatensatz anhand des Text-Index mit neuen Standard-Textdaten sowie neuem Text, Schriftgröße und Farbe. |
| [updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)](#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-) | Aktualisiert die txt2-Daten aus dem Txt2DataRoot-Modell. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Txt2Resource() {#Txt2Resource--}
```
public Txt2Resource()
```


Initialisiert eine neue Instanz der [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource) Klasse.

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

### addTextRecord(String text, RectangleF bounds) {#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-}
```
public final int addTextRecord(String text, RectangleF bounds)
```


Fügt den Textdatensatz zu Resource hinzu und gibt die ID des Textdatensatzes zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der Text des Datensatzes. |
| bounds | [RectangleF](../../com.aspose.psd/rectanglef) | Die Begrenzungen. |

**Returns:**
int - Gibt die ID des Textdatensatzes für die Resource zurück
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
### getData() {#getData--}
```
public final byte[] getData()
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Returns:**
byte[]
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
### getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public static ITextEngineKeys getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


Ermittelt, ob die Resource komprimiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Baum | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | Der Baum. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.ITextEngineKeys - Gibt ein Objekt mit Schlüsseln zurück.
### getLength() {#getLength--}
```
public int getLength()
```


Ermittelt die Länge der Schichtressource in Bytes.

**Returns:**
int
### getParsedTxt2Model_internalized() {#getParsedTxt2Model-internalized--}
```
public final Txt2DataRoot getParsedTxt2Model_internalized()
```


Parst die txt2-Daten in eine Txt2DataRoot Klasseninstanz.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot - Die txt2-Daten als Txt2DataRoot Klasseninstanz.
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
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ermittelt die Signatur der Schichtressource.

**Returns:**
int
### getTextData() {#getTextData--}
```
public final String[] getTextData()
```


Liest den Textdatensatz aus den Resource-Daten.

**Returns:**
java.lang.String[] - Array von Textdatensätzen
### getText_internalized() {#getText-internalized--}
```
public final String getText_internalized()
```


Liest oder setzt den Namen.

Wert: Der Name.

**Returns:**
java.lang.String
### getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public final String getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


Liest das TXT2 aus dem geparsten Baum.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Baum | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | Der Datenbaum. |

**Returns:**
java.lang.String - Die Txt2-Daten.
### getTxt2ParsedTree_internalized() {#getTxt2ParsedTree-internalized--}
```
public final System.Collections.Generic.Dictionary<String,Object> getTxt2ParsedTree_internalized()
```


Liest den geparsten TXT2-Baum.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> - Geparster Baum
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




### removeTextRecord_internalized(int textIndex) {#removeTextRecord-internalized-int-}
```
public final void removeTextRecord_internalized(int textIndex)
```


Entfernt den Textdatensatz aus Resource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textIndex | int | Der Index des Textdatensatzes, der entfernt werden soll. |

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

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

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

### setText_internalized(String value) {#setText-internalized-java.lang.String-}
```
public final void setText_internalized(String value)
```


Liest oder setzt den Namen.

Wert: Der Name.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
### updateTextData_internalized(int textIndex, String newText, double fontSize, Color color) {#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-}
```
public final void updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)
```


Aktualisiert den Textdatensatz anhand des Text-Index mit neuen Standard-Textdaten sowie neuem Text, Schriftgröße und Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textIndex | int | Der Index des Textdatensatzes in den txt2-Ressourcendaten. |
| newText | java.lang.String | Der neue Text. |
| fontSize | double | die neue Schriftgröße. |
| color | [Color](../../com.aspose.psd/color) | Die neue Textfarbe. |

### updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot) {#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-}
```
public final void updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)
```


Aktualisiert die txt2-Daten aus dem Txt2DataRoot-Modell.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| txt2DataRoot | com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot | Das txt2-Datenmodell. |

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

