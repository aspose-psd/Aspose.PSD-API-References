---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die GraphCut-Auto-Maskierungsoptionen."
type: docs
weight: 12
url: /de/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Die GraphCut-Auto-Maskierungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Initialisiert eine neue Instanz der [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions)-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Die Hintergrundobjektnummer |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Fügt Auto-Maskierungsargumente hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Füllt Standardstriche aus. |
| [getArgs()](#getArgs--) | Liest die Argumente für den Segmentierungsalgorithmus. |
| [getAssumedObjects()](#getAssumedObjects--) | Gibt die angenommenen Objekte zurück. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Liest die Hintergrund-Ersatzfarbe. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Gibt einen Wert zurück, der angibt, ob Standardstriche berechnet werden sollen. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Gibt das kombinierte Rechteck der Objekte zurück. |
| [getDecompose()](#getDecompose--) | Liest einen Wert, der angibt, ob es unnötig ist, jede Form von der Maske als einzelnes Objekt zu trennen oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Gibt die Standard‑Hintergrundstriche zurück. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Gibt die vorab berechneten Standard‑Vordergrundstriche zurück. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Gibt die Standard‑Objekt‑Rechtecke zurück. |
| [getExportOptions()](#getExportOptions--) | Ruft die Bildexportoptionen ab. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Gibt den Federungsradius zurück. |
| [getMaskingArea()](#getMaskingArea--) | Ruft den Maskierungsbereich ab. |
| [getMethod()](#getMethod--) | Ruft die Segmentierungsmethode ab. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Gibt den Ereignishandler für den Fortschritt des Vorab‑Berechnungsprozesses der Standardpunkte zurück. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Gibt einen Wert zurück, der angibt, ob die Sammlung angenommener Objekte menschliche Objekte enthält. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Legt die Argumente für den Segmentierungsalgorithmus fest. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Setzt die angenommenen Objekte. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Legt die Hintergrundersatzfarbe fest. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Setzt einen Wert, der angibt, ob Standardstriche berechnet werden sollen. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | Das kombinierte Rechteck der Objekte. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Legt einen Wert fest, der angibt, ob es unnötig ist, jede Shape von der Maske als einzelnes Objekt oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund, zu trennen. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | Die Standard‑Hintergrundstriche. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | Die vorab berechneten Standard‑Vordergrundstriche. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | Die Standard‑Objekt‑Rechtecke. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Legt die Bildexportoptionen fest. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Setzt den Federungsradius. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Ein Wert, der angibt, ob die Sammlung angenommener Objekte menschliche Objekte enthält. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Legt den Maskierungsbereich fest. |
| [setMethod(int value)](#setMethod-int-) | Legt die Segmentierungsmethode fest. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Setzt den Ereignishandler für den Fortschritt des Vorab‑Berechnungsprozesses der Standardpunkte. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Initialisiert eine neue Instanz der [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions)-Klasse.

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Die Hintergrundobjektnummer

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Fügt Auto-Maskierungsargumente hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Das Bild. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Füllt Standardstriche aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Das Bild. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Liest die Argumente für den Segmentierungsalgorithmus.

Wert: Die Argumente für den Segmentierungsalgorithmus.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Gibt die angenommenen Objekte zurück.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - die angenommenen Objekte.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Liest die Hintergrund-Ersatzfarbe.

Wert: Die Hintergrundersatzfarbe. Diese Farbe wird als Hintergrundfarbe in den resultierenden Bildern verwendet.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Gibt einen Wert zurück, der angibt, ob Standardstriche berechnet werden sollen.

**Returns:**
boolean - ein Wert, der angibt, ob Standardstriche berechnet werden sollen.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Gibt das kombinierte Rechteck der Objekte zurück.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Liest einen Wert, der angibt, ob es unnötig ist, jede Form von der Maske als einzelnes Objekt zu trennen oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund.

Wert:  true  wenn dekomponiert; andernfalls  false .

**Returns:**
boolean - ein Wert, der angibt, ob es unnötig ist, jede Shape von der Maske als einzelnes Objekt oder als ein vereinigtes Objekt von der Maske, getrennt vom Hintergrund, zu trennen.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Gibt die Standard‑Hintergrundstriche zurück.

**Returns:**
com.aspose.psd.Point[] - die Standard‑Hintergrundstriche.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Gibt die vorab berechneten Standard‑Vordergrundstriche zurück.

**Returns:**
com.aspose.psd.Point[] - die vorab berechneten Standard-Vordergrundstriche.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Gibt die Standard‑Objekt‑Rechtecke zurück.

**Returns:**
com.aspose.psd.Rectangle[] - die Standard-Objekt-Rechtecke.
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
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Gibt den Ereignishandler für den Fortschritt des Vorab‑Berechnungsprozesses der Standardpunkte zurück.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Gibt einen Wert zurück, der angibt, ob die Sammlung angenommener Objekte menschliche Objekte enthält.

**Returns:**
boolean - ein Wert, der angibt, ob die angenommene Objektsammlung menschliche Objekte enthält.
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

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Setzt die angenommenen Objekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | die angenommenen Objekte. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

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

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Setzt einen Wert, der angibt, ob Standardstriche berechnet werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob Standardstriche berechnet werden sollen. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


Das kombinierte Rechteck der Objekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | das kombinierte Objekt-Rechteck. |

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

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


Die Standard‑Hintergrundstriche.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | die Standard-Hintergrundstriche. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


Die vorab berechneten Standard‑Vordergrundstriche.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | die vorab berechneten Standard-Vordergrundstriche. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


Die Standard‑Objekt‑Rechtecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | die Standard-Objekt-Rechtecke. |

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

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Ein Wert, der angibt, ob die Sammlung angenommener Objekte menschliche Objekte enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob die angenommene Objektsammlung menschliche Objekte enthält. |

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

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Setzt den Ereignishandler für den Fortschritt des Vorab‑Berechnungsprozesses der Standardpunkte.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | der Standard-Event-Handler für den Fortschritt des Punkte-Vorberechnungsprozesses. |

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

