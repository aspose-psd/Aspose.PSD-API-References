---
title: "MaskingOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Geeft de algemene afbeeldingsmaskeringsopties weer."
type: docs
weight: 16
url: /nl/java/com.aspose.psd.masking.options/maskingoptions/
---

**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Geeft de algemene afbeeldingsmaskeringsopties weer.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Het achtergrondobjectnummer |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Haalt de argumenten voor het segmentatie-algoritme op. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Haalt de vervangingskleur voor de achtergrond op. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Haalt een waarde op die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond. |
| [getExportOptions()](#getExportOptions--) | Haalt de afbeeldings-exportopties op. |
| [getMaskingArea()](#getMaskingArea--) | Haalt het maskergebied op. |
| [getMethod()](#getMethod--) | Haalt de segmentatiemethode op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Stelt de argumenten voor het segmentatie-algoritme in. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Stelt de vervangingskleur voor de achtergrond in. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Stelt een waarde in die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Stelt de afbeeldings-exportopties in. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Stelt het maskergebied in. |
| [setMethod(int value)](#setMethod-int-) | Stelt de segmentatiemethode in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Het achtergrondobjectnummer

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Haalt de argumenten voor het segmentatie-algoritme op.

Waarde: De argumenten voor het segmentatie-algoritme.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Haalt de vervangingskleur voor de achtergrond op.

Waarde: De vervangingskleur voor de achtergrond. Deze kleur wordt gebruikt als achtergrondkleur in de resulterende afbeeldingen.

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


Haalt een waarde op die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond.

Waarde:  true  als decomponeren; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of het overbodig is om elke Shape van het masker te scheiden als individueel object of als één object van het masker gescheiden van de achtergrond.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Haalt de afbeeldings-exportopties op.

Waarde: De afbeeldings-exportopties die gebruikt zullen worden om de resulterende afbeeldingen te maken.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
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

