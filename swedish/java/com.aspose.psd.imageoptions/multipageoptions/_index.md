---
title: "MultiPageOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "Basisklass för format som stöder flera sidor"
type: docs
weight: 17
url: /sv/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Basisklass för format som stöder flera sidor
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Initierar en ny instans av klassen  MultiPageOptions  . |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen  MultiPageOptions  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Hämtar eller anger exportområdet. |
| [getMergeLayers()](#getMergeLayers--) | Hämtar ett värde som indikerar om [merege layers]. |
| [getMode()](#getMode--) | Hämtar eller anger läget. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Hämtar eller anger namn på utdataskikt (Fungerar om exportformatet stödjer namngivning av lager, till exempel för Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Hämtar alternativ för sidrasterisering. |
| [getPageTitles()](#getPageTitles--) | Hämtar eller anger sidtitlar. |
| [getPages()](#getPages--) | Hämtar eller anger sidor. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Hämtar tidsintervallet. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Initierar sidorna från intervallarrayen |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Hämtar eller anger exportområdet. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Anger ett värde som indikerar om [merege layers]. |
| [setMode(int value)](#setMode-int-) | Hämtar eller anger läget. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Hämtar eller anger namn på utdataskikt (Fungerar om exportformatet stödjer namngivning av lager, till exempel för Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Anger alternativ för sidrasterisering. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Hämtar eller anger sidtitlar. |
| [setPages(int[] value)](#setPages-int---) | Hämtar eller anger sidor. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Anger tidsintervallet. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Initierar en ny instans av klassen  MultiPageOptions  .

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sidor | int[] | Sidorna. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sidor | int[] | Arrayen av sidor. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Exportområdet. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Sidtitlarna. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Sidtitlarna. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Exportområdet. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Den  IntRange . |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Den  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Exportområdet. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Den  IntRange . |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Den  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Exportområdet. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int | Sidindexen. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Initierar en ny instans av klassen  MultiPageOptions  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int | Sidindexen. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Exportområdet. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar eller anger exportområdet.

Värde: Exportområdet.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Hämtar ett värde som indikerar om [merege layers].

Värde:  true  om [merege layers]; annars,  false .

**Returns:**
boolean - ett värde som indikerar om [merege layers].
### getMode() {#getMode--}
```
public int getMode()
```


Hämtar eller anger läget.

Värde: Läge.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Hämtar eller anger namn på utdataskikt (Fungerar om exportformatet stödjer namngivning av lager, till exempel för Psd)

Värde: Namn på utdataskikt.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Hämtar alternativ för sidrasterisering.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - sidans rasteriseringsalternativ.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Hämtar eller anger sidtitlar.

Värde: Sidtitlar.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Hämtar eller anger sidor.

Värde: Sidorna.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Hämtar tidsintervallet.

Värde: Tidsintervallet.

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


Initierar sidorna från intervallarrayen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Intervallen. |

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


Hämtar eller anger exportområdet.

Värde: Exportområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Anger ett värde som indikerar om [merege layers].

Värde:  true  om [merege layers]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Hämtar eller anger läget.

Värde: Läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Hämtar eller anger namn på utdataskikt (Fungerar om exportformatet stödjer namngivning av lager, till exempel för Psd)

Värde: Namn på utdataskikt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Anger alternativ för sidrasterisering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | sidans rasteriseringsalternativ. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Hämtar eller anger sidtitlar.

Värde: Sidtitlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Hämtar eller anger sidor.

Värde: Sidorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Anger tidsintervallet.

Värde: Tidsintervallet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | tidsintervallet. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

