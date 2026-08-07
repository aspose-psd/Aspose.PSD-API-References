---
title: "PngLoadOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die PNG-Ladeoptionen."
type: docs
weight: 11
url: /de/java/com.aspose.psd.imageloadoptions/pngloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

Die PNG-Ladeoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Initialisiert eine neue Instanz der  PngLoadOptions  Klasse. |
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
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Liest einen Wert, der angibt, ob [ignore after load]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Liest den Fortschritts-Event-Handler. |
| [getStrictMode()](#getStrictMode--) | Ruft ab oder legt einen Wert fest, der angibt, ob [strict mode]. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Liest einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Dies ist Teil des Venture-Lizenzierungsmusters. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Setzt die  Image  Hintergrundfarbe . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Legt den Datenwiederherstellungsmodus fest. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Legt einen Wert fest, der angibt, ob [ignore after load]. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Liest oder legt den Speicher MGR fest. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Legt den Fortschritts‑Ereignis‑Handler fest. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Ruft ab oder legt einen Wert fest, der angibt, ob [strict mode]. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Legt einen Wert fest, der angibt, ob die ICC‑Profilkonvertierung angewendet werden soll. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Dies ist Teil des Venture-Lizenzierungsmusters. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Initialisiert eine neue Instanz der  PngLoadOptions  Klasse.

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
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Liest einen Wert, der angibt, ob [ignore after load].

**Returns:**
boolean -  true  wenn [ignore after load]; andernfalls  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Liest den Fortschritts-Event-Handler.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Ruft ab oder legt einen Wert fest, der angibt, ob [strict mode].

**Returns:**
boolean - ein Wert, der angibt, ob [strict mode].
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

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Legt einen Wert fest, der angibt, ob [ignore after load].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn [ignore after load]; andernfalls  false . |

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

### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Ruft ab oder legt einen Wert fest, der angibt, ob [strict mode].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [strict mode]. |

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

