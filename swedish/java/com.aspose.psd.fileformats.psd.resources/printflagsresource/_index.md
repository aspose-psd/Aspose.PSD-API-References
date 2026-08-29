---
title: "PrintFlagsResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Resurs för utskriftsflaggor"
type: docs
weight: 30
url: /sv/java/com.aspose.psd.fileformats.psd.resources/printflagsresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class PrintFlagsResource extends ResourceBlock
```

Resurs för utskriftsflaggor
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PrintFlagsResource()](#PrintFlagsResource--) | Initierar en ny instans av klassen [PrintFlagsResource](../../com.aspose.psd.fileformats.psd.resources/printflagsresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Resurssignaturen för ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Den vanliga Photoshop-resurssignaturen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBleedScale()](#getBleedScale--) | Hämtar eller anger blödskalan. |
| [getBleedWidth()](#getBleedWidth--) | Hämtar eller anger blödningsbredden. |
| [getCenterCropMark()](#getCenterCropMark--) | Hämtar eller anger den centrala beskärningsmarkeringen. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar resursens datastorlek i byte. |
| [getID()](#getID--) | Hämtar eller anger den unika identifieraren för resursen. |
| [getMinimalVersion()](#getMinimalVersion--) | Hämtar den minsta erforderliga PSD-versionen. |
| [getName()](#getName--) | Hämtar eller anger resursnamnet. |
| [getSignature()](#getSignature--) | Hämtar resurssignaturen. |
| [getSize()](#getSize--) | Hämtar resursblockets storlek i byte inklusive dess data. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Sparar resursblocket till den angivna strömmen. |
| [setBleedScale(short value)](#setBleedScale-short-) | Hämtar eller anger blödskalan. |
| [setBleedWidth(int value)](#setBleedWidth-int-) | Hämtar eller anger blödningsbredden. |
| [setCenterCropMark(byte value)](#setCenterCropMark-byte-) | Hämtar eller anger den centrala beskärningsmarkeringen. |
| [setID(short value)](#setID-short-) | Hämtar eller anger den unika identifieraren för resursen. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Hämtar eller anger lager- och maskinformation. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger resursnamnet. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Hämtar eller anger resursblockets tillstånd. |
| [setVersion(short value)](#setVersion-short-) | Hämtar eller anger versionen. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validerar resursvärdena. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintFlagsResource() {#PrintFlagsResource--}
```
public PrintFlagsResource()
```


Initierar en ny instans av klassen [PrintFlagsResource](../../com.aspose.psd.fileformats.psd.resources/printflagsresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Resurssignaturen för ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Den vanliga Photoshop-resurssignaturen.

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
### getBleedScale() {#getBleedScale--}
```
public final short getBleedScale()
```


Hämtar eller anger blödskalan.

Värde: Blödningens skala.

**Returns:**
short
### getBleedWidth() {#getBleedWidth--}
```
public final int getBleedWidth()
```


Hämtar eller anger blödningsbredden.

Värde: Blödningens bredd.

**Returns:**
int
### getCenterCropMark() {#getCenterCropMark--}
```
public final byte getCenterCropMark()
```


Hämtar eller anger den centrala beskärningsmarkeringen.

Värde: Den centrala beskärningsmarkeringen.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Hämtar resursens datastorlek i byte.

Värde: Resursens datastorlek.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Hämtar eller anger den unika identifieraren för resursen.

Värde: Den unika identifieraren för resursen.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Hämtar den minsta erforderliga PSD-versionen.

Värde: Den minsta PSD-versionen.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0).

Värde: Resursnamnet.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Hämtar resursens signatur. Ska alltid vara '8BIM'.

Värde: Resursens signatur.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar resursblockets storlek i byte inklusive dess data.

Värde: Storleken på resursblocket.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Hämtar eller anger versionen.

Värde: Versionen.

**Returns:**
short
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Sparar resursblocket till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

### setBleedScale(short value) {#setBleedScale-short-}
```
public final void setBleedScale(short value)
```


Hämtar eller anger blödskalan.

Värde: Blödningens skala.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setBleedWidth(int value) {#setBleedWidth-int-}
```
public final void setBleedWidth(int value)
```


Hämtar eller anger blödningsbredden.

Värde: Blödningens bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCenterCropMark(byte value) {#setCenterCropMark-byte-}
```
public final void setCenterCropMark(byte value)
```


Hämtar eller anger den centrala beskärningsmarkeringen.

Värde: Den centrala beskärningsmarkeringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Hämtar eller anger den unika identifieraren för resursen.

Värde: Den unika identifieraren för resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Hämtar eller anger lager- och maskinformation.

Värde: Lager- och maskinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0).

Värde: Resursnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatur | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Hämtar eller anger resursblockets tillstånd.

Värde: Resursblockets tillstånd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Hämtar eller anger versionen.

Värde: Versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Validerar resursvärdena.

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

