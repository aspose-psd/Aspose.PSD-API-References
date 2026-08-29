---
title: "VersionInfoResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Resurs för versionsinformation"
type: docs
weight: 41
url: /sv/java/com.aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class VersionInfoResource extends ResourceBlock
```

Resurs för versionsinformation
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [VersionInfoResource()](#VersionInfoResource--) | Initierar en ny instans av klassen [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Resurssignaturen för ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Den vanliga Photoshop-resurssignaturen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar resursens datastorlek i byte. |
| [getFileVersion()](#getFileVersion--) | Hämtar eller anger filversionen. |
| [getID()](#getID--) | Hämtar eller anger den unika identifieraren för resursen. |
| [getMinimalVersion()](#getMinimalVersion--) | Hämtar den minsta erforderliga PSD-versionen. |
| [getName()](#getName--) | Hämtar eller anger resursnamnet. |
| [getReaderName()](#getReaderName--) | Hämtar eller anger läsarens namn. |
| [getSignature()](#getSignature--) | Hämtar resurssignaturen. |
| [getSize()](#getSize--) | Hämtar resursblockets storlek i byte inklusive dess data. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen. |
| [getWriterName()](#getWriterName--) | Hämtar eller anger skrivarens namn. |
| [hasRealMergedData()](#hasRealMergedData--) | Hämtar eller anger ett värde som indikerar om den här instansen har verklig sammanslagen data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Sparar resursblocket till den angivna strömmen. |
| [setFileVersion(long value)](#setFileVersion-long-) | Hämtar eller anger filversionen. |
| [setID(short value)](#setID-short-) | Hämtar eller anger den unika identifieraren för resursen. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Hämtar eller anger lager- och maskinformation. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger resursnamnet. |
| [setReaderName(String value)](#setReaderName-java.lang.String-) | Hämtar eller anger läsarens namn. |
| [setRealMergedData(boolean value)](#setRealMergedData-boolean-) | Hämtar eller anger ett värde som indikerar om den här instansen har verklig sammanslagen data. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Hämtar eller anger resursblockets tillstånd. |
| [setVersion(long value)](#setVersion-long-) | Hämtar eller anger versionen. |
| [setWriterName(String value)](#setWriterName-java.lang.String-) | Hämtar eller anger skrivarens namn. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validerar resursvärdena. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VersionInfoResource() {#VersionInfoResource--}
```
public VersionInfoResource()
```


Initierar en ny instans av klassen [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource).

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
### getFileVersion() {#getFileVersion--}
```
public final long getFileVersion()
```


Hämtar eller anger filversionen.

Värde: Filversionen.

**Returns:**
long
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
### getReaderName() {#getReaderName--}
```
public final String getReaderName()
```


Hämtar eller anger läsarens namn.

Värde: Läsarens namn.

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
public final long getVersion()
```


Hämtar eller anger versionen.

Värde: Versionen.

**Returns:**
long
### getWriterName() {#getWriterName--}
```
public final String getWriterName()
```


Hämtar eller anger skrivarens namn.

Värde: Namnet på författaren.

**Returns:**
java.lang.String
### hasRealMergedData() {#hasRealMergedData--}
```
public final boolean hasRealMergedData()
```


Hämtar eller anger ett värde som indikerar om den här instansen har verklig sammanslagen data.

Värde:  true  om detta objekt har verklig sammanslagen data; annars,  false .

**Returns:**
boolean
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

### setFileVersion(long value) {#setFileVersion-long-}
```
public final void setFileVersion(long value)
```


Hämtar eller anger filversionen.

Värde: Filversionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

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

### setReaderName(String value) {#setReaderName-java.lang.String-}
```
public final void setReaderName(String value)
```


Hämtar eller anger läsarens namn.

Värde: Läsarens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setRealMergedData(boolean value) {#setRealMergedData-boolean-}
```
public final void setRealMergedData(boolean value)
```


Hämtar eller anger ett värde som indikerar om den här instansen har verklig sammanslagen data.

Värde:  true  om detta objekt har verklig sammanslagen data; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### setVersion(long value) {#setVersion-long-}
```
public final void setVersion(long value)
```


Hämtar eller anger versionen.

Värde: Versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setWriterName(String value) {#setWriterName-java.lang.String-}
```
public final void setWriterName(String value)
```


Hämtar eller anger skrivarens namn.

Värde: Namnet på författaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

