---
title: "Jpeg2000LoadOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "JPEG2000-Ladeoptionen"
type: docs
weight: 10
url: /de/java/com.aspose.psd.imageloadoptions/jpeg2000loadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

JPEG2000-Ladeoptionen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | Initialisiert eine neue Instanz der Klasse  Jpeg2000LoadOptions  . |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Die benutzerdefinierten Schriftquellen |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Liest die  Image  Hintergrundfarbe . |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Liest den Datenwiederherstellungsmodus. |
| [getDefaultMaximumDecodingTime_internalized()](#getDefaultMaximumDecodingTime-internalized--) | Liest die standardmäßige maximale Dekodierzeit. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Liest einen Wert, der angibt, ob [ignore after load]. |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | Liest die maximale Dekodierzeit in Sekunden (diese Option kann auf sehr langsamen, speicherarmen Maschinen verwendet werden, um ein Hängenbleiben beim Verarbeiten sehr großer Bilder zu verhindern – Auflösung mehr als 5500x6500 Pixel). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | Liest die maximale Dekodierzeit für Kacheln. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Liest den Fortschritts-Event-Handler. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Liest einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Dies ist Teil des Venture-Lizenzierungsmusters. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Setzt die  Image  Hintergrundfarbe . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Legt den Datenwiederherstellungsmodus fest. |
| [setDefaultMaximumDecodingTime_internalized(int value)](#setDefaultMaximumDecodingTime-internalized-int-) | Legt die standardmäßige maximale Dekodierzeit fest. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Legt einen Wert fest, der angibt, ob [ignore after load]. |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | Legt die maximale Dekodierzeit in Sekunden fest (diese Option kann auf sehr langsamen, speicherarmen Maschinen verwendet werden, um ein Hängenbleiben beim Verarbeiten sehr großer Bilder zu verhindern – Auflösung von mehr als 5500x6500 Pixeln). |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | Legt die maximale Dekodierzeit für Kacheln fest. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Liest oder legt den Speicher MGR fest. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Legt den Fortschritts‑Ereignis‑Handler fest. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Legt einen Wert fest, der angibt, ob die ICC‑Profilkonvertierung angewendet werden soll. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Dies ist Teil des Venture-Lizenzierungsmusters. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


Initialisiert eine neue Instanz der Klasse  Jpeg2000LoadOptions  .

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


Die benutzerdefinierten Schriftquellen

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Liest den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Returns:**
int - der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Liest die  Image  Hintergrundfarbe .

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Typischerweise wird die Hintergrundfarbe gesetzt, wenn ein Pixelwert aufgrund von Datenbeschädigung nicht wiederhergestellt werden kann.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Liest den Datenwiederherstellungsmodus.

**Returns:**
int - Der Datenwiederherstellungsmodus.
### getDefaultMaximumDecodingTime_internalized() {#getDefaultMaximumDecodingTime-internalized--}
```
public static int getDefaultMaximumDecodingTime_internalized()
```


Liest die standardmäßige maximale Dekodierzeit.

**Returns:**
int - Die standardmäßige maximale Dekodierzeit.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Liest einen Wert, der angibt, ob [ignore after load].

**Returns:**
boolean -  true  wenn [ignore after load]; andernfalls  false .
### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


Liest die maximale Dekodierzeit in Sekunden (diese Option kann auf sehr langsamen, speicherarmen Maschinen verwendet werden, um ein Hängenbleiben beim Verarbeiten sehr großer Bilder zu verhindern – Auflösung mehr als 5500x6500 Pixel).

**Returns:**
int - Die maximale Dekodierzeit.
### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


Liest die maximale Dekodierzeit für Kacheln.

Wert: Die maximale Dekodierzeit für Kacheln.

**Returns:**
int - die maximale Dekodierzeit für Kacheln.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Liest den Fortschritts-Event-Handler.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Liest einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Dies ist Teil des Venture‑Lizenzierungs‑Musters. Dieser Wert wird von VentureLicenser gesetzt, wenn das Unternehmen uns ein LoadOptions‑Objekt übergibt.

**Returns:**
java.lang.Object
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Setzt die  Image  Hintergrundfarbe .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | Die Hintergrundfarbe. |

Typischerweise wird die Hintergrundfarbe gesetzt, wenn ein Pixelwert aufgrund von Datenbeschädigung nicht wiederhergestellt werden kann. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Legt den Datenwiederherstellungsmodus fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Datenwiederherstellungsmodus. |

### setDefaultMaximumDecodingTime_internalized(int value) {#setDefaultMaximumDecodingTime-internalized-int-}
```
public static void setDefaultMaximumDecodingTime_internalized(int value)
```


Legt die standardmäßige maximale Dekodierzeit fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die standardmäßige maximale Dekodierzeit. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Legt einen Wert fest, der angibt, ob [ignore after load].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn [ignore after load]; andernfalls  false . |

### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


Legt die maximale Dekodierzeit in Sekunden fest (diese Option kann auf sehr langsamen, speicherarmen Maschinen verwendet werden, um ein Hängenbleiben beim Verarbeiten sehr großer Bilder zu verhindern – Auflösung von mehr als 5500x6500 Pixeln).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die maximale Dekodierzeit. |

### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


Legt die maximale Dekodierzeit für Kacheln fest.

Wert: Die maximale Dekodierzeit für Kacheln.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die maximale Dekodierzeit für Kacheln. |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Liest oder legt den Speicher MGR fest.

Wert: Der Speicher MGR.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Legt den Fortschritts‑Ereignis‑Handler fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | der Fortschritts‑Ereignis‑Handler. |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Legt einen Wert fest, der angibt, ob die ICC‑Profilkonvertierung angewendet werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Dies ist Teil des Venture‑Lizenzierungs‑Musters. Dieser Wert wird von VentureLicenser gesetzt, wenn das Unternehmen uns ein LoadOptions‑Objekt übergibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

