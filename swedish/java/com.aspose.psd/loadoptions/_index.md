---
title: "LoadOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar laddningsalternativen."
type: docs
weight: 68
url: /sv/java/com.aspose.psd/loadoptions/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Representerar laddningsalternativen.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | De anpassade teckensnittskällorna |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar en ledtråd för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Hämtar bildens bakgrundsfärg. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Hämtar dataräddningsläget. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Hämtar ett värde som indikerar om [ignore after load]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar progress‑händelsehanteraren. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Hämtar ett värde som indikerar om ICC-profilkonvertering ska tillämpas. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Detta är en del av venture-licensmönstret. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Ställer in bildens bakgrundsfärg. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Ställer in dataräddningsläget. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Ställer in ett värde som indikerar om [ignore after load]. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Hämtar eller ställer in minneshanteraren MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ställer in hanteraren för progress‑händelsen. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Ställer in ett värde som indikerar om ICC-profilkonvertering ska tillämpas. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Detta är en del av venture-licensmönstret. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


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
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Hämtar progress‑händelsehanteraren.

Värde: hanteraren för progress‑händelsen.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
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

