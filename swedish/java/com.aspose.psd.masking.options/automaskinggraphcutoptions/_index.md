---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "GraphCut automatiska maskningsalternativ."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

GraphCut automatiska maskningsalternativ.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Initierar en ny instans av klassen [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Bakgrundsobjektets nummer |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Lägg till auto maskeringsargument. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Fyll i standardstreck. |
| [getArgs()](#getArgs--) | Hämtar argumenten för segmenteringsalgoritmen. |
| [getAssumedObjects()](#getAssumedObjects--) | Hämtar de antagna objekten. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Hämtar bakgrundens ersättningsfärg. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Hämtar ett värde som indikerar om standardstrokar ska beräknas. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Hämtar den kombinerade objektrektangeln. |
| [getDecompose()](#getDecompose--) | Hämtar ett värde som indikerar om det är onödigt att separera varje form från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Hämtar standardbakgrundsstrokarna. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Hämtar de förberäknade standardförgrundsstrokarna. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Hämtar standardobjektens rektanglar. |
| [getExportOptions()](#getExportOptions--) | Hämtar bildexportalternativen. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Hämtar fjädringsradien. |
| [getMaskingArea()](#getMaskingArea--) | Hämtar maskningsområdet. |
| [getMethod()](#getMethod--) | Hämtar segmenteringsmetoden. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Hämtar standardpunkternas förberäkningsprocessens framstegshändelsehanterare. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Hämtar ett värde som indikerar om samlingen av antagna objekt innehåller mänskliga objekt. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Ställer in argumenten för segmenteringsalgoritmen. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Ställer in de antagna objekten. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Ställer in bakgrundsersättningsfärgen. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Ställer in ett värde som indikerar om standardstrokar ska beräknas. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | Den kombinerade objektrektangeln. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Ställer in ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | Standardbakgrundsstrokarna. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | De förberäknade standardförgrundsstrokarna. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | Standardobjektens rektanglar. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Ställer in bildexportalternativen. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Ställer in fjädringsradien. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Ett värde som indikerar om samlingen av antagna objekt innehåller mänskliga objekt. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Ställer in maskeringsområdet. |
| [setMethod(int value)](#setMethod-int-) | Ställer in segmenteringsmetoden. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ställer in standardpunkternas förberäkningsprocessens framstegshändelsehanterare. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Initierar en ny instans av klassen [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions).

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Bakgrundsobjektets nummer

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Lägg till auto maskeringsargument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Bilden. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Fyll i standardstreck.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Bilden. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Hämtar argumenten för segmenteringsalgoritmen.

Värde: Argumenten för segmenteringsalgoritmen.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Hämtar de antagna objekten.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - de antagna objekten.
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


Hämtar bakgrundens ersättningsfärg.

Värde: Bakgrundsersättningsfärgen. Denna färg kommer att användas som bakgrundsfärg i de resulterande bilderna.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Hämtar ett värde som indikerar om standardstrokar ska beräknas.

**Returns:**
boolean - ett värde som indikerar om standardstrokar ska beräknas.
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


Hämtar den kombinerade objektrektangeln.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Hämtar ett värde som indikerar om det är onödigt att separera varje form från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden.

Värde:  true  om dekomponera; annars,  false .

**Returns:**
boolean - ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Hämtar standardbakgrundsstrokarna.

**Returns:**
com.aspose.psd.Point[] - standardbakgrundsstrokarna.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Hämtar de förberäknade standardförgrundsstrokarna.

**Returns:**
com.aspose.psd.Point[] - de förberäknade standardförgrundsstrokarna.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Hämtar standardobjektens rektanglar.

**Returns:**
com.aspose.psd.Rectangle[] - standardobjektens rektanglar.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Hämtar bildexportalternativen.

Värde: Bildexportalternativen som kommer att användas för att skapa de resulterande bilderna.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Hämtar fjädringsradien.

**Returns:**
int - fjädringsradien.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Hämtar maskningsområdet.

Värde: Maskeringsområdet som är ett delområde av källbilden. Rectangle.Empty-värdet betyder hela källbildens område.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Hämtar segmenteringsmetoden.

Värde: Segmenteringsmetoden.

**Returns:**
int - segmenteringsmetoden.
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Hämtar standardpunkternas förberäkningsprocessens framstegshändelsehanterare.

Värde: hanteraren för progress‑händelsen.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Hämtar ett värde som indikerar om samlingen av antagna objekt innehåller mänskliga objekt.

**Returns:**
boolean - ett värde som indikerar om antagen objektkollektion innehåller mänskliga objekt.
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


Ställer in argumenten för segmenteringsalgoritmen.

Värde: Argumenten för segmenteringsalgoritmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | argumenten för segmenteringsalgoritmen. |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Ställer in de antagna objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | de antagna objekten. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Ställer in bakgrundsersättningsfärgen.

Värde: Bakgrundsersättningsfärgen. Denna färg kommer att användas som bakgrundsfärg i de resulterande bilderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | bakgrundsersättningsfärgen. |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Ställer in ett värde som indikerar om standardstrokar ska beräknas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om standardstrokar ska beräknas. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


Den kombinerade objektrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | den kombinerade objektrektangeln. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Ställer in ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden.

Värde:  true  om dekomponera; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


Standardbakgrundsstrokarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | standardbakgrundsstrokarna. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


De förberäknade standardförgrundsstrokarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | de förberäknade standardförgrundsstrokarna. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


Standardobjektens rektanglar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | standardobjektrektanglarna. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Ställer in bildexportalternativen.

Värde: Bildexportalternativen som kommer att användas för att skapa de resulterande bilderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | bildexportalternativen. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Ställer in fjädringsradien.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | featheringradien. |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Ett värde som indikerar om samlingen av antagna objekt innehåller mänskliga objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om antagen objektkollektion innehåller mänskliga objekt. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Ställer in maskeringsområdet.

Värde: Maskeringsområdet som är ett delområde av källbilden. Rectangle.Empty-värdet betyder hela källbildens område.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | maskeringsområdet. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Ställer in segmenteringsmetoden.

Värde: Segmenteringsmetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | segmenteringsmetoden. |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Ställer in standardpunkternas förberäkningsprocessens framstegshändelsehanterare.

Värde: hanteraren för progress‑händelsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | standardpunkternas förberäkningsprocessens framstegshändelsehanterare. |

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

