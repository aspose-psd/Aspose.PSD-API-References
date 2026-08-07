---
title: "GraphCutMaskingOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die GraphCut-Auto-Maskierungsoptionen."
type: docs
weight: 14
url: /de/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

Die GraphCut-Auto-Maskierungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Die Hintergrundobjektnummer |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Liest die Argumente für den Segmentierungsalgorithmus. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Liest die Hintergrund-Ersatzfarbe. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Liest einen Wert, der angibt, ob es unnötig ist, jede Form von der Maske als einzelnes Objekt zu trennen oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund. |
| [getExportOptions()](#getExportOptions--) | Ruft die Bildexportoptionen ab. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Gibt den Federungsradius zurück. |
| [getMaskingArea()](#getMaskingArea--) | Ruft den Maskierungsbereich ab. |
| [getMethod()](#getMethod--) | Ruft die Segmentierungsmethode ab. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Legt die Argumente für den Segmentierungsalgorithmus fest. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Legt die Hintergrundersatzfarbe fest. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Legt einen Wert fest, der angibt, ob es unnötig ist, jede Shape von der Maske als einzelnes Objekt oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund, zu trennen. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Legt die Bildexportoptionen fest. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Setzt den Federungsradius. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Legt den Maskierungsbereich fest. |
| [setMethod(int value)](#setMethod-int-) | Legt die Segmentierungsmethode fest. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Die Hintergrundobjektnummer

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Liest die Argumente für den Segmentierungsalgorithmus.

Wert: Die Argumente für den Segmentierungsalgorithmus.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Liest die Hintergrund-Ersatzfarbe.

Wert: Die Hintergrundersatzfarbe. Diese Farbe wird als Hintergrundfarbe in den resultierenden Bildern verwendet.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Liest einen Wert, der angibt, ob es unnötig ist, jede Form von der Maske als einzelnes Objekt zu trennen oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund.

Wert:  true  wenn dekomponiert; andernfalls  false .

**Returns:**
boolean - ein Wert, der angibt, ob es unnötig ist, jede Shape von der Maske als einzelnes Objekt oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund, zu trennen.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Ruft die Bildexportoptionen ab.

Wert: Die Bildexportoptionen, die zum Erstellen der resultierenden Bilder verwendet werden.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Gibt den Federungsradius zurück.

**Returns:**
int - der Weichzeichnungsradius.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Ruft den Maskierungsbereich ab.

Wert: Der Maskierungsbereich, der ein Teilbereich des Quellbildes ist. Der Wert Rectangle.Empty bedeutet den gesamten Quellbildbereich.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Ruft die Segmentierungsmethode ab.

Wert: Die Segmentierungsmethode.

**Returns:**
int - die Segmentierungsmethode.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Legt die Argumente für den Segmentierungsalgorithmus fest.

Wert: Die Argumente für den Segmentierungsalgorithmus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | die Argumente für den Segmentierungsalgorithmus. |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Legt die Hintergrundersatzfarbe fest.

Wert: Die Hintergrundersatzfarbe. Diese Farbe wird als Hintergrundfarbe in den resultierenden Bildern verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | die Hintergrundersatzfarbe. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Legt einen Wert fest, der angibt, ob es unnötig ist, jede Shape von der Maske als einzelnes Objekt oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund, zu trennen.

Wert:  true  wenn dekomponiert; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob es unnötig ist, jede Shape von der Maske als einzelnes Objekt oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund, zu trennen. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Legt die Bildexportoptionen fest.

Wert: Die Bildexportoptionen, die zum Erstellen der resultierenden Bilder verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | die Bildexportoptionen. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Setzt den Federungsradius.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Weichzeichnungsradius. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Legt den Maskierungsbereich fest.

Wert: Der Maskierungsbereich, der ein Teilbereich des Quellbildes ist. Der Wert Rectangle.Empty bedeutet den gesamten Quellbildbereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | den Maskierungsbereich. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Legt die Segmentierungsmethode fest.

Wert: Die Segmentierungsmethode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Segmentierungsmethode. |

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

