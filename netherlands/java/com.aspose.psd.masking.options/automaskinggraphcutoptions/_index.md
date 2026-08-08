---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De GraphCut-auto-maskingopties."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

De GraphCut-auto-maskingopties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Initialiseert een nieuw exemplaar van de klasse [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions). |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Het achtergrondobjectnummer |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Voeg auto-masking argumenten toe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Vul standaardstreken in. |
| [getArgs()](#getArgs--) | Haalt de argumenten voor het segmentatie-algoritme op. |
| [getAssumedObjects()](#getAssumedObjects--) | Haalt de veronderstelde objecten op. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Haalt de vervangingskleur voor de achtergrond op. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Haalt een waarde op die aangeeft of standaardstreken berekend moeten worden. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Haalt de rechthoek van de gecombineerde objecten op. |
| [getDecompose()](#getDecompose--) | Haalt een waarde op die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Haalt de standaard achtergrondstreken op. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Haalt de vooraf berekende standaard voorgrondstreken op. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Haalt de standaard objectrechthoeken op. |
| [getExportOptions()](#getExportOptions--) | Haalt de afbeeldings-exportopties op. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Haalt de vervagingsstraal op. |
| [getMaskingArea()](#getMaskingArea--) | Haalt het maskergebied op. |
| [getMethod()](#getMethod--) | Haalt de segmentatiemethode op. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Haalt de eventhandler voor de voortgang van het vooraf berekenen van standaardpunten op. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Haalt een waarde op die aangeeft of de verzameling veronderstelde objecten menselijke objecten bevat. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Stelt de argumenten voor het segmentatie-algoritme in. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Stelt de veronderstelde objecten in. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Stelt de vervangingskleur voor de achtergrond in. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Stelt een waarde in die aangeeft of standaardstreken berekend moeten worden. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | De gecombineerde objectenrechthoek. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Stelt een waarde in die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | De standaard achtergrondstreken. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | De vooraf berekende standaard voorgrondstreken. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | De standaard objectrechthoeken. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Stelt de afbeeldings-exportopties in. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Stelt de vervagingsstraal in. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Een waarde die aangeeft of de veronderstelde objectenverzameling menselijke objecten bevat. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Stelt het maskergebied in. |
| [setMethod(int value)](#setMethod-int-) | Stelt de segmentatiemethode in. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Stelt de standaardpunten-voortrekberekeningsproces-voortgang‑eventhandler in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Initialiseert een nieuw exemplaar van de klasse [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions).

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Het achtergrondobjectnummer

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Voeg auto-masking argumenten toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De afbeelding. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Vul standaardstreken in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De afbeelding. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Haalt de argumenten voor het segmentatie-algoritme op.

Waarde: De argumenten voor het segmentatie-algoritme.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Haalt de veronderstelde objecten op.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - de veronderstelde objecten.
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


Haalt de vervangingskleur voor de achtergrond op.

Waarde: De vervangingskleur voor de achtergrond. Deze kleur wordt gebruikt als achtergrondkleur in de resulterende afbeeldingen.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Haalt een waarde op die aangeeft of standaardstreken berekend moeten worden.

**Returns:**
boolean - een waarde die aangeeft of standaardstreken moeten worden berekend.
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


Haalt de rechthoek van de gecombineerde objecten op.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Haalt een waarde op die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond.

Waarde:  true  als decomponeren; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Haalt de standaard achtergrondstreken op.

**Returns:**
com.aspose.psd.Point[] - de standaard achtergrondstreken.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Haalt de vooraf berekende standaard voorgrondstreken op.

**Returns:**
com.aspose.psd.Point[] - de vooraf berekende standaard voorgrondstreken.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Haalt de standaard objectrechthoeken op.

**Returns:**
com.aspose.psd.Rectangle[] - de standaard objectrechthoeken.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Haalt de afbeeldings-exportopties op.

Waarde: De afbeeldings-exportopties die gebruikt zullen worden om de resulterende afbeeldingen te maken.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Haalt de vervagingsstraal op.

**Returns:**
int - de vervagingsstraal.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Haalt het maskergebied op.

Waarde: Het maskergebied dat een gedeeltelijk gebied van de bronafbeelding is. Een Rectangle.Empty-waarde betekent het volledige bronafbeeldingsgebied.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Haalt de segmentatiemethode op.

Waarde: De segmentatiemethode.

**Returns:**
int - de segmentatiemethode.
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Haalt de eventhandler voor de voortgang van het vooraf berekenen van standaardpunten op.

Waarde: De voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Haalt een waarde op die aangeeft of de verzameling veronderstelde objecten menselijke objecten bevat.

**Returns:**
boolean - een waarde die aangeeft of de veronderstelde objectenverzameling menselijke objecten bevat.
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


Stelt de argumenten voor het segmentatie-algoritme in.

Waarde: De argumenten voor het segmentatie-algoritme.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | de argumenten voor het segmentatie-algoritme. |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Stelt de veronderstelde objecten in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | de veronderstelde objecten. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Stelt de vervangingskleur voor de achtergrond in.

Waarde: De vervangingskleur voor de achtergrond. Deze kleur wordt gebruikt als achtergrondkleur in de resulterende afbeeldingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | de achtergrondvervangingskleur. |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Stelt een waarde in die aangeeft of standaardstreken berekend moeten worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of standaardstreken moeten worden berekend. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


De gecombineerde objectenrechthoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | de gecombineerde objectrechthoek. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Stelt een waarde in die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond.

Waarde:  true  als decomponeren; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of het overbodig is om elke Vorm van het masker als individueel object te scheiden of als een verenigd object van het masker gescheiden van de achtergrond. |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


De standaard achtergrondstreken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | de standaard achtergrondstreken. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


De vooraf berekende standaard voorgrondstreken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | de vooraf berekende standaard voorgrondstreken. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


De standaard objectrechthoeken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | de standaard objectrechthoeken. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Stelt de afbeeldings-exportopties in.

Waarde: De afbeeldings-exportopties die gebruikt zullen worden om de resulterende afbeeldingen te maken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | de afbeeldingsexportopties. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Stelt de vervagingsstraal in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de vervagingsstraal. |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Een waarde die aangeeft of de veronderstelde objectenverzameling menselijke objecten bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of de veronderstelde objectenverzameling menselijke objecten bevat. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Stelt het maskergebied in.

Waarde: Het maskergebied dat een gedeeltelijk gebied van de bronafbeelding is. Een Rectangle.Empty-waarde betekent het volledige bronafbeeldingsgebied.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | het maskeergebied. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Stelt de segmentatiemethode in.

Waarde: De segmentatiemethode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de segmentatiemethode. |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Stelt de standaardpunten-voortrekberekeningsproces-voortgang‑eventhandler in.

Waarde: De voortgangs‑eventhandler.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | de standaardpunten-voortrekberekeningsproces-voortgang‑eventhandler. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

