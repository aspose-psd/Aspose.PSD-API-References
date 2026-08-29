---
title: "MultiPageOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Basisklasse für Formate, die mehrere Seiten unterstützen"
type: docs
weight: 17
url: /de/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Basisklasse für Formate, die mehrere Seiten unterstützen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der MultiPageOptions Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Liest oder setzt den Exportbereich. |
| [getMergeLayers()](#getMergeLayers--) | Liest einen Wert, der angibt, ob [merege layers]. |
| [getMode()](#getMode--) | Liest oder setzt den Modus. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Liest oder setzt die Namen der Ausgabelayer (funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Liest die Rasterisierungsoptionen der Seite. |
| [getPageTitles()](#getPageTitles--) | Liest oder setzt die Seitentitel. |
| [getPages()](#getPages--) | Liest oder setzt die Seiten. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Liest das Zeitintervall. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Initialisiert die Seiten aus dem Bereichsarray |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Liest oder setzt den Exportbereich. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Setzt einen Wert, der angibt, ob [merege layers]. |
| [setMode(int value)](#setMode-int-) | Liest oder setzt den Modus. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Liest oder setzt die Namen der Ausgabelayer (funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Setzt die Rasterisierungsoptionen der Seite. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Liest oder setzt die Seitentitel. |
| [setPages(int[] value)](#setPages-int---) | Liest oder setzt die Seiten. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Setzt das Zeitintervall. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Seiten | int[] | Die Seiten. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Seiten | int[] | Das Array der Seiten. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Der Exportbereich. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Die Seitentitel. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Die Seitentitel. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Der Exportbereich. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Der IntRange. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Der IntRange. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Der Exportbereich. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Der IntRange. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Der IntRange. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Der Exportbereich. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Seite | int | Der Seitenindex. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Initialisiert eine neue Instanz der MultiPageOptions Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Seite | int | Der Seitenindex. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Der Exportbereich. |

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
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Liest oder setzt den Exportbereich.

Wert: Der Exportbereich.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Liest einen Wert, der angibt, ob [merege layers].

Wert: true wenn [merege layers]; ansonsten, false.

**Returns:**
boolean - ein Wert, der angibt, ob [merege layers].
### getMode() {#getMode--}
```
public int getMode()
```


Liest oder setzt den Modus.

Wert: Der Modus.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Liest oder setzt die Namen der Ausgabelayer (funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd)

Wert: Die Namen der Ausgabe-Layer.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Liest die Rasterisierungsoptionen der Seite.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - die Seitenrasterisierungsoptionen.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Liest oder setzt die Seitentitel.

Wert: Die Seitentitel.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Liest oder setzt die Seiten.

Wert: Die Seiten.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Liest das Zeitintervall.

Wert: Das Zeitintervall.

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Initialisiert die Seiten aus dem Bereichsarray

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Die Bereiche. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Liest oder setzt den Exportbereich.

Wert: Der Exportbereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Setzt einen Wert, der angibt, ob [merege layers].

Wert: true wenn [merege layers]; ansonsten, false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Liest oder setzt den Modus.

Wert: Der Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Liest oder setzt die Namen der Ausgabelayer (funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd)

Wert: Die Namen der Ausgabe-Layer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Setzt die Rasterisierungsoptionen der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | die Seitenrasterisierungsoptionen. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Liest oder setzt die Seitentitel.

Wert: Die Seitentitel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Liest oder setzt die Seiten.

Wert: Die Seiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Setzt das Zeitintervall.

Wert: Das Zeitintervall.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | das Zeitintervall. |

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

