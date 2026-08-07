---
title: "PsdLoadOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "PSD-Ladeoptionen"
type: docs
weight: 12
url: /de/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

PSD-Ladeoptionen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Initialisiert eine neue Instanz der [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Die benutzerdefinierten Schriftquellen |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Ruft ab oder legt fest, ob die ursprünglichen Ebenenpixel beim Rendern erhalten bleiben sollen, wenn die Ebene nicht geändert wurde. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Ruft ab oder legt fest, ob mit dem gerenderten Bild gespeichert werden soll, mit oder ohne Verzerrungs-Transformation. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Liest die  Image  Hintergrundfarbe . |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Liest den Datenwiederherstellungsmodus. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Liest einen Wert, der angibt, ob [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Ruft ab oder legt einen Wert fest, der angibt, ob [ignore alpha channel] ignoriert wird. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Ruft ab oder legt einen Wert fest, der angibt, ob die feste Breite der PSD-Textschicht bei der Ausführung der UpdateText-Operation ignoriert wird. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Ruft ab oder legt einen Wert fest, der angibt, ob [load effects resource] (standardmäßig ist die Ressource nicht geladen). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Liest den Fortschritts-Event-Handler. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Ruft ab oder legt einen Wert fest, der angibt, ob [use read only mode] verwendet wird. |
| [getReadOnlyType()](#getReadOnlyType--) | Ruft ab oder legt den beim Laden eines PSD-Bildes verwendeten Nur-Lese-Modus fest. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Ruft ab oder legt einen Wert fest, der angibt, ob [use disk for load effects resource] (standardmäßig wird die Festplatte zum Laden der Effektressourcen verwendet, aber bei Einstellung dieses Wertes auf false kann Speicher verwendet werden, wenn er ausreicht). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Liest einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Dies ist Teil des Venture-Lizenzierungsmusters. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Ruft ab oder legt fest, ob die ursprünglichen Ebenenpixel beim Rendern erhalten bleiben sollen, wenn die Ebene nicht geändert wurde. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Ruft ab oder legt fest, ob mit dem gerenderten Bild gespeichert werden soll, mit oder ohne Verzerrungs-Transformation. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Setzt die  Image  Hintergrundfarbe . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Legt den Datenwiederherstellungsmodus fest. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Legt einen Wert fest, der angibt, ob [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Ruft ab oder legt einen Wert fest, der angibt, ob [ignore alpha channel] ignoriert wird. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Ruft ab oder legt einen Wert fest, der angibt, ob die feste Breite der PSD-Textschicht bei der Ausführung der UpdateText-Operation ignoriert wird. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Ruft ab oder legt einen Wert fest, der angibt, ob [load effects resource] (standardmäßig ist die Ressource nicht geladen). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Liest oder legt den Speicher MGR fest. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Legt den Fortschritts‑Ereignis‑Handler fest. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Ruft ab oder legt einen Wert fest, der angibt, ob [use read only mode] verwendet wird. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Ruft ab oder legt den beim Laden eines PSD-Bildes verwendeten Nur-Lese-Modus fest. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Ruft ab oder legt einen Wert fest, der angibt, ob [use disk for load effects resource] (standardmäßig wird die Festplatte zum Laden der Effektressourcen verwendet, aber bei Einstellung dieses Wertes auf false kann Speicher verwendet werden, wenn er ausreicht). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Legt einen Wert fest, der angibt, ob die ICC‑Profilkonvertierung angewendet werden soll. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Dies ist Teil des Venture-Lizenzierungsmusters. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Initialisiert eine neue Instanz der [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) Klasse.

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Ruft ab oder legt fest, ob die ursprünglichen Ebenenpixel beim Rendern erhalten bleiben sollen, wenn die Ebene nicht geändert wurde.

Wert:  true  um die Originalpixel unveränderter Ebenen beizubehalten; andernfalls  false .

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Ruft ab oder legt fest, ob mit dem gerenderten Bild gespeichert werden soll, mit oder ohne Verzerrungs-Transformation.

Wert:  true  Bild mit Verzerrungs-Transformation rendern  false .

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
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Ruft ab oder legt einen Wert fest, der angibt, ob [ignore alpha channel] ignoriert wird.

Wert:  true  wenn [ignore alpha channel]; andernfalls  false .

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Ruft ab oder legt einen Wert fest, der angibt, ob die feste Breite der PSD-Textschicht bei der Ausführung der UpdateText-Operation ignoriert wird.

Wert:  true  wenn [ignore text layer width]; andernfalls  false .

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Ruft ab oder legt einen Wert fest, der angibt, ob [load effects resource] (standardmäßig ist die Ressource nicht geladen). Wenn diese Option gesetzt ist, werden nur unterstützte Effekte in das endgültige zusammengeführte Bild gerendert.

Wert:  true  wenn [load effects resource]; andernfalls  false .

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Liest den Fortschritts-Event-Handler.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Ruft ab oder legt einen Wert fest, der angibt, ob [use read only mode]. Dies ist ein Nur-Lese-Modus, der für vollständige Kompatibilität mit Adobe Photoshop unterstützt wird. Wenn diese Option gesetzt ist, werden alle für Ebenen vorgenommenen Änderungen nicht im endgültigen Bild gespeichert. Alle Daten werden aus dem ImageData‑Abschnitt verwendet, sodass es identisch zu Photoshop ist. Standardmäßig sind alle geladenen Bilder nicht vollständig mit Adobe Photoshop kompatibel.

Wert:  true  wenn [use photoshop compatibility mode]; andernfalls  false .

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Ruft ab oder legt den beim Laden eines PSD-Bildes verwendeten Nur-Lese-Modus fest.

Wert: Einer der ReadOnlyMode‑Werte ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Ruft ab oder legt einen Wert fest, der angibt, ob [use disk for load effects resource] (standardmäßig wird die Festplatte zum Laden der Effektressourcen verwendet, aber bei Einstellung dieses Wertes auf false kann Speicher verwendet werden, wenn er ausreicht).

Wert:  true  wenn [use disk for load effects resource]; andernfalls  false .

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Ruft ab oder legt fest, ob die ursprünglichen Ebenenpixel beim Rendern erhalten bleiben sollen, wenn die Ebene nicht geändert wurde.

Wert:  true  um die Originalpixel unveränderter Ebenen beizubehalten; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Ruft ab oder legt fest, ob mit dem gerenderten Bild gespeichert werden soll, mit oder ohne Verzerrungs-Transformation.

Wert:  true  Bild mit Verzerrungs-Transformation rendern  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Ruft ab oder legt einen Wert fest, der angibt, ob [ignore alpha channel] ignoriert wird.

Wert:  true  wenn [ignore alpha channel]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Ruft ab oder legt einen Wert fest, der angibt, ob die feste Breite der PSD-Textschicht bei der Ausführung der UpdateText-Operation ignoriert wird.

Wert:  true  wenn [ignore text layer width]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Ruft ab oder legt einen Wert fest, der angibt, ob [load effects resource] (standardmäßig ist die Ressource nicht geladen). Wenn diese Option gesetzt ist, werden nur unterstützte Effekte in das endgültige zusammengeführte Bild gerendert.

Wert:  true  wenn [load effects resource]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Ruft ab oder legt einen Wert fest, der angibt, ob [use read only mode]. Dies ist ein Nur-Lese-Modus, der für vollständige Kompatibilität mit Adobe Photoshop unterstützt wird. Wenn diese Option gesetzt ist, werden alle für Ebenen vorgenommenen Änderungen nicht im endgültigen Bild gespeichert. Alle Daten werden aus dem ImageData‑Abschnitt verwendet, sodass es identisch zu Photoshop ist. Standardmäßig sind alle geladenen Bilder nicht vollständig mit Adobe Photoshop kompatibel.

Wert:  true  wenn [use photoshop compatibility mode]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Ruft ab oder legt den beim Laden eines PSD-Bildes verwendeten Nur-Lese-Modus fest.

Wert: Einer der ReadOnlyMode‑Werte ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Ruft ab oder legt einen Wert fest, der angibt, ob [use disk for load effects resource] (standardmäßig wird die Festplatte zum Laden der Effektressourcen verwendet, aber bei Einstellung dieses Wertes auf false kann Speicher verwendet werden, wenn er ausreicht).

Wert:  true  wenn [use disk for load effects resource]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

