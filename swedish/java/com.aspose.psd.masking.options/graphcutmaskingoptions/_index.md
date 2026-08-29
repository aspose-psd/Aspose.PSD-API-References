---
title: "GraphCutMaskingOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "GraphCut automatiska maskningsalternativ."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

GraphCut automatiska maskningsalternativ.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Bakgrundsobjektets nummer |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Hämtar argumenten för segmenteringsalgoritmen. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Hämtar bakgrundens ersättningsfärg. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Hämtar ett värde som indikerar om det är onödigt att separera varje form från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |
| [getExportOptions()](#getExportOptions--) | Hämtar bildexportalternativen. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Hämtar fjädringsradien. |
| [getMaskingArea()](#getMaskingArea--) | Hämtar maskningsområdet. |
| [getMethod()](#getMethod--) | Hämtar segmenteringsmetoden. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Ställer in argumenten för segmenteringsalgoritmen. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Ställer in bakgrundsersättningsfärgen. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Ställer in ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Ställer in bildexportalternativen. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Ställer in fjädringsradien. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Ställer in maskeringsområdet. |
| [setMethod(int value)](#setMethod-int-) | Ställer in segmenteringsmetoden. |
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


Bakgrundsobjektets nummer

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Hämtar argumenten för segmenteringsalgoritmen.

Värde: Argumenten för segmenteringsalgoritmen.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Hämtar bakgrundens ersättningsfärg.

Värde: Bakgrundsersättningsfärgen. Denna färg kommer att användas som bakgrundsfärg i de resulterande bilderna.

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


Hämtar ett värde som indikerar om det är onödigt att separera varje form från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden.

Värde:  true  om dekomponera; annars,  false .

**Returns:**
boolean - ett värde som indikerar om det är onödigt att separera varje Shape från masken som ett enskilt objekt eller som ett förenat objekt från masken separerat från bakgrunden.
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

