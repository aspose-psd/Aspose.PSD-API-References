---
title: "TiffDataType"
second_title: "Aspose.PSD för Java API-referens"
description: "Tiff-datatypen."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Tiff-datatypen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller ligger på samma position i sorteringsordningen som det andra objektet. |
| [deepClone()](#deepClone--) | Utför en djup kloning av den här instansen. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Hämtar den extra datastorleken i byte (om de 12 byte inte räcker för att rymma taggdata). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Hämtar antalet element. |
| [getDataSize()](#getDataSize--) | Hämtar den extra datastorleken i byte (om de 12 byte inte räcker för att rymma taggdata). |
| [getId()](#getId--) | Hämtar tagg‑id:s heltalsrepresentation. |
| [getTagId()](#getTagId--) | Hämtar tagg‑id. |
| [getTagType()](#getTagType--) | Hämtar tagg‑typen. |
| [getValue()](#getValue--) | Hämtar värdet som den här datatypen innehåller. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Hämtar ett värde som indikerar om taggen är privat. |
| [isValid()](#isValid--) | Hämtar ett värde som indikerar om taggdata är giltig. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Läser taggdata. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ställer in värdet som den här datatypen innehåller. |
| [toString()](#toString--) | Returnerar en  System.String  som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Skriver den extra taggdata. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Skriver taggdata. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller ligger på samma position i sorteringsordningen som det andra objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Ett objekt att jämföra med den här instansen. |

**Returns:**
int - En 32-bitars signerat heltal som indikerar den relativa ordningen för de objekt som jämförs. Returvärdet har följande betydelser: Värde Betydelse Mindre än noll Den här instansen är mindre än  obj . Noll Den här instansen är lika med  obj . Större än noll Den här instansen är större än  obj .
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Utför en djup kloning av den här instansen.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Hämtar den extra datastorleken i byte (om de 12 byte inte räcker för att rymma taggdata).

**Returns:**
long - Den extra datastorleken i byte.

Detta är antalet databitar justerat till ordgränsen.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


Hämtar antalet element.

**Returns:**
long - Antalet element.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Hämtar den extra datastorleken i byte (om de 12 byte inte räcker för att rymma taggdata).

**Returns:**
long - Den extra datastorleken i byte.

Detta är exakt byteantal.
### getId() {#getId--}
```
public int getId()
```


Hämtar tagg‑id:s heltalsrepresentation.

**Returns:**
int - Tagg‑id:s heltalsrepresentation
### getTagId() {#getTagId--}
```
public int getTagId()
```


Hämtar tagg‑id.

**Returns:**
int - Tagg‑id.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Hämtar tagg‑typen.

**Returns:**
int - Tagg‑typen.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Hämtar värdet som den här datatypen innehåller.

**Returns:**
java.lang.Object - Värdet.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


Hämtar ett värde som indikerar om taggen är privat. Privata tiff‑taggar är taggar med tagg‑id över 32768.

**Returns:**
boolean -  true  om taggdata är giltig; annars,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Hämtar ett värde som indikerar om taggdata är giltig. Den giltiga taggen innehåller data som kan bevaras. Den ogiltiga taggen kan inte lagras.

**Returns:**
boolean -  true  om taggdata är giltig; annars,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Läser taggdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | Datastreamen. |
| position | long | Taggpositionen. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Ställer in värdet som den här datatypen innehåller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object | Värdet. |

### toString() {#toString--}
```
public String toString()
```


Returnerar en  System.String  som representerar detta objekt.

**Returns:**
java.lang.String - En  System.String  som representerar detta objekt.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Skriver den extra taggdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Datastreamen. |

**Returns:**
long - De faktiska skrivna byten.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Skriver taggdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Datastreamen. |
| additionalDataOffset | long | Förskjutningen att skriva ytterligare data till. |

