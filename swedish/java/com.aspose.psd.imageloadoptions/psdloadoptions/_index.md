---
title: "PsdLoadOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "PSD‑inläsningsalternativ"
type: docs
weight: 12
url: /sv/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

PSD‑inläsningsalternativ
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Initierar en ny instans av klassen [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | De anpassade teckensnittskällorna |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Hämtar eller anger om originala lagerpixel ska bevaras under rendering om lagret inte har ändrats. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Hämtar eller anger om man ska spara med den renderade bilden, med eller utan en warp‑transformering. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar en ledtråd för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Hämtar bildens bakgrundsfärg. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Hämtar dataräddningsläget. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Hämtar ett värde som indikerar om [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Hämtar eller anger ett värde som indikerar om [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Hämtar eller anger ett värde som indikerar om fast bredd för PSD‑textlager ska ignoreras vid körning av UpdateText‑operationen. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Hämtar eller anger ett värde som indikerar om [load effects resource] (standard är att resursen inte laddas). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar progress‑händelsehanteraren. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Hämtar eller anger ett värde som indikerar om [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | Hämtar eller anger det skrivskyddade läget som används när en PSD‑bild laddas. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Hämtar eller anger ett värde som indikerar om [use disk for load effects resource] (standard är att använda disk för att ladda effektresurser, men minne kan användas om det är tillräckligt genom att sätta detta värde till false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Hämtar ett värde som indikerar om ICC-profilkonvertering ska tillämpas. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Detta är en del av venture-licensmönstret. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Hämtar eller anger om originala lagerpixel ska bevaras under rendering om lagret inte har ändrats. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Hämtar eller anger om man ska spara med den renderade bilden, med eller utan en warp‑transformering. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Ställer in bildens bakgrundsfärg. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Ställer in dataräddningsläget. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Ställer in ett värde som indikerar om [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Hämtar eller anger ett värde som indikerar om [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Hämtar eller anger ett värde som indikerar om fast bredd för PSD‑textlager ska ignoreras vid körning av UpdateText‑operationen. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Hämtar eller anger ett värde som indikerar om [load effects resource] (standard är att resursen inte laddas). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Hämtar eller ställer in minneshanteraren MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ställer in hanteraren för progress‑händelsen. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Hämtar eller anger ett värde som indikerar om [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Hämtar eller anger det skrivskyddade läget som används när en PSD‑bild laddas. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Hämtar eller anger ett värde som indikerar om [use disk for load effects resource] (standard är att använda disk för att ladda effektresurser, men minne kan användas om det är tillräckligt genom att sätta detta värde till false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Ställer in ett värde som indikerar om ICC-profilkonvertering ska tillämpas. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Detta är en del av venture-licensmönstret. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Initierar en ny instans av klassen [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


De anpassade teckensnittskällorna

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Hämtar eller anger om originala lagerpixel ska bevaras under rendering om lagret inte har ändrats.

Värde:  true  för att behålla originalpixlarna i oförändrade lager; annars  false .

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Hämtar eller anger om man ska spara med den renderade bilden, med eller utan en warp‑transformering.

Värde:  true  rendera bilden med warp‑transformering  false .

**Returns:**
boolean
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Hämtar en ledtråd för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Returns:**
int - tips om buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.
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


Hämtar bildens bakgrundsfärg.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Vanligtvis sätts bakgrundsfärgen när pixelvärdet inte kan återställas på grund av datakorruption.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Hämtar dataräddningsläget.

**Returns:**
int – dataräddningsläget.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Hämtar ett värde som indikerar om [ignore after load].

**Returns:**
boolean – true om [ignore after load]; annars false.
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Hämtar eller anger ett värde som indikerar om [ignore alpha channel].

Värde:  true  om [ignore alpha channel]; annars  false .

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Hämtar eller anger ett värde som indikerar om fast bredd för PSD‑textlager ska ignoreras vid körning av UpdateText‑operationen.

Värde:  true  om [ignore text layer width]; annars  false .

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Hämtar eller anger ett värde som indikerar om [load effects resource] (standard är att resursen inte laddas). När detta alternativ är satt kommer endast stödjade effekter att renderas till den slutliga sammanslagna bilden.

Värde:  true  om [load effects resource]; annars  false .

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Hämtar progress‑händelsehanteraren.

Värde: hanteraren för progress‑händelsen.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Hämtar eller anger ett värde som indikerar om [use read only mode]. Detta är skrivskyddat läge, stödjt för exakt kompatibilitet med Adobe Photoshop. När detta alternativ är satt kommer alla ändringar som gjorts på lager inte att sparas till den slutliga bilden. All data hämtas från ImageData‑sektionen, så den är identisk med Photoshop. Som standard är alla laddade bilder inte exakt kompatibla med Adobe Photoshop.

Värde:  true  om [use photoshop compatibility mode]; annars  false .

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Hämtar eller anger det skrivskyddade läget som används när en PSD‑bild laddas.

Värde: Ett av ReadOnlyMode‑värdena ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Hämtar eller anger ett värde som indikerar om [use disk for load effects resource] (standard är att använda disk för att ladda effektresurser, men minne kan användas om det är tillräckligt genom att sätta detta värde till false).

Värde:  true  om [use disk for load effects resource]; annars  false .

**Returns:**
boolean
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Hämtar ett värde som indikerar om ICC-profilkonvertering ska tillämpas.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Detta är en del av venture-licensmönstret. Detta värde kommer att sättas av VentureLicenser om venture skickar ett LoadOptions‑objekt till oss.

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


Hämtar eller anger om originala lagerpixel ska bevaras under rendering om lagret inte har ändrats.

Värde:  true  för att behålla originalpixlarna i oförändrade lager; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Hämtar eller anger om man ska spara med den renderade bilden, med eller utan en warp‑transformering.

Värde:  true  rendera bilden med warp‑transformering  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ställer in en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Ställer in bildens bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | Bakgrundsfärgen. |

Vanligtvis sätts bakgrundsfärgen när pixelvärdet inte kan återställas på grund av datakorruption. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Ställer in dataräddningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Datåterställningsläget. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Ställer in ett värde som indikerar om [ignore after load].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om [ignore after load]; annars false. |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Hämtar eller anger ett värde som indikerar om [ignore alpha channel].

Värde:  true  om [ignore alpha channel]; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Hämtar eller anger ett värde som indikerar om fast bredd för PSD‑textlager ska ignoreras vid körning av UpdateText‑operationen.

Värde:  true  om [ignore text layer width]; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Hämtar eller anger ett värde som indikerar om [load effects resource] (standard är att resursen inte laddas). När detta alternativ är satt kommer endast stödjade effekter att renderas till den slutliga sammanslagna bilden.

Värde:  true  om [load effects resource]; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Hämtar eller ställer in minneshanteraren MGR.

Värde: Minneshanteraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Ställer in hanteraren för progress‑händelsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | händelsehanteraren för framsteg. |

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Hämtar eller anger ett värde som indikerar om [use read only mode]. Detta är skrivskyddat läge, stödjt för exakt kompatibilitet med Adobe Photoshop. När detta alternativ är satt kommer alla ändringar som gjorts på lager inte att sparas till den slutliga bilden. All data hämtas från ImageData‑sektionen, så den är identisk med Photoshop. Som standard är alla laddade bilder inte exakt kompatibla med Adobe Photoshop.

Värde:  true  om [use photoshop compatibility mode]; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Hämtar eller anger det skrivskyddade läget som används när en PSD‑bild laddas.

Värde: Ett av ReadOnlyMode‑värdena ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Hämtar eller anger ett värde som indikerar om [use disk for load effects resource] (standard är att använda disk för att ladda effektresurser, men minne kan användas om det är tillräckligt genom att sätta detta värde till false).

Värde:  true  om [use disk for load effects resource]; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Ställer in ett värde som indikerar om ICC-profilkonvertering ska tillämpas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Detta är en del av venture-licensmönstret. Detta värde kommer att sättas av VentureLicenser om venture skickar ett LoadOptions‑objekt till oss.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

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

