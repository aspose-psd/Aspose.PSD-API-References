---
title: "QuickMaskInformationResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Resurs för snabbmaskininformation"
type: docs
weight: 32
url: /sv/java/com.aspose.psd.fileformats.psd.resources/quickmaskinformationresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class QuickMaskInformationResource extends ResourceBlock
```

Resurs för snabbmaskininformation
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [QuickMaskInformationResource()](#QuickMaskInformationResource--) | Initierar en ny instans av klassen [QuickMaskInformationResource](../../com.aspose.psd.fileformats.psd.resources/quickmaskinformationresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Resurssignaturen för ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Den vanliga Photoshop-resurssignaturen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelId()](#getChannelId--) | Hämtar eller anger kanalidentifieraren. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar resursens datastorlek i byte. |
| [getID()](#getID--) | Hämtar eller anger den unika identifieraren för resursen. |
| [getMinimalVersion()](#getMinimalVersion--) | Hämtar den minsta erforderliga PSD-versionen. |
| [getName()](#getName--) | Hämtar eller anger resursnamnet. |
| [getSignature()](#getSignature--) | Hämtar resurssignaturen. |
| [getSize()](#getSize--) | Hämtar resursblockets storlek i byte inklusive dess data. |
| [hashCode()](#hashCode--) |  |
| [isMaskEmpty()](#isMaskEmpty--) | Hämtar eller anger ett värde som indikerar om den här instansen är masktom. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Sparar resursblocket till den angivna strömmen. |
| [setChannelId(short value)](#setChannelId-short-) | Hämtar eller anger kanalidentifieraren. |
| [setID(short value)](#setID-short-) | Hämtar eller anger den unika identifieraren för resursen. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Hämtar eller anger lager- och maskinformation. |
| [setMaskEmpty(boolean value)](#setMaskEmpty-boolean-) | Hämtar eller anger ett värde som indikerar om den här instansen är masktom. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger resursnamnet. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Hämtar eller anger resursblockets tillstånd. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validerar resursvärdena. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QuickMaskInformationResource() {#QuickMaskInformationResource--}
```
public QuickMaskInformationResource()
```


Initierar en ny instans av klassen [QuickMaskInformationResource](../../com.aspose.psd.fileformats.psd.resources/quickmaskinformationresource).

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
### getChannelId() {#getChannelId--}
```
public final short getChannelId()
```


Hämtar eller anger kanalidentifieraren.

Värde: Kanalidentifieraren.

**Returns:**
short
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isMaskEmpty() {#isMaskEmpty--}
```
public final boolean isMaskEmpty()
```


Hämtar eller anger ett värde som indikerar om den här instansen är masktom.

Värde:  true  om den här instansen är masktom; annars  false .

**Returns:**
boolean
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

### setChannelId(short value) {#setChannelId-short-}
```
public final void setChannelId(short value)
```


Hämtar eller anger kanalidentifieraren.

Värde: Kanalidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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

### setMaskEmpty(boolean value) {#setMaskEmpty-boolean-}
```
public final void setMaskEmpty(boolean value)
```


Hämtar eller anger ett värde som indikerar om den här instansen är masktom.

Värde:  true  om den här instansen är masktom; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

