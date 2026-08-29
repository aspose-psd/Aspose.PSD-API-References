---
title: "TiffStreamReader"
second_title: "Aspose.PSD för Java API-referens"
description: "Tiff‑strömmen för hantering av little endian‑tiff‑filformat."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

Tiff‑strömmen för hantering av little endian‑tiff‑filformat.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Initierar en ny instans av  TiffStreamReader  klassen. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Initierar en ny instans av  TiffStreamReader  klassen. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Initierar en ny instans av  TiffStreamReader  klassen. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Initierar en ny instans av  TiffStreamReader  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Hämtar läsarens längd. |
| [getThrowExceptions()](#getThrowExceptions--) | Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till strömmen). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Läser en array av byte‑värden från strömmen. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Läser en array av osignerade byte‑värden från strömmen. |
| [readDouble(long position)](#readDouble-long-) | Läs ett enda double‑värde från strömmen. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Läser en array av double‑värden från strömmen. |
| [readFloat(long position)](#readFloat-long-) | Läs ett enda float‑värde från strömmen. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Läser en array av float‑värden från strömmen. |
| [readRational(long position)](#readRational-long-) | Läs ett enda rational‑värde från strömmen. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Läser en array av rational‑värden från strömmen. |
| [readSByte(long position)](#readSByte-long-) | Läser signerad byte‑data från strömmen. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Läser en array av signerade byte‑värden från strömmen. |
| [readSLong(long position)](#readSLong-long-) | Läs signerad integer‑värde från strömmen. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Läser en array av signerade integer‑värden från strömmen. |
| [readSRational(long position)](#readSRational-long-) | Läs ett enda signerat rational‑värde från strömmen. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Läser en array av signerade rational‑värden från strömmen. |
| [readSShort(long position)](#readSShort-long-) | Läs signerat short‑värde från strömmen. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Läser en array av signerade short‑värden från strömmen. |
| [readString_internalized(long position)](#readString-internalized-long-) | Läser strängen från strömmen. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Läser strängen från strömmen. |
| [readULong(long position)](#readULong-long-) | Läs ett osignerat heltalsvärde från strömmen. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Läser en array av osignerade heltalsvärden från strömmen. |
| [readUShort(long position)](#readUShort-long-) | Läs ett osignerat short‑värde från strömmen. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Läser en array av osignerade heltalsvärden från strömmen. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till strömmen). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Konverterar den underliggande datan till strömbehållaren. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Initierar en ny instans av  TiffStreamReader  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Byte‑array‑data. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Initierar en ny instans av  TiffStreamReader  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Byte‑array‑data. |
| startIndex | int | Startindexet i data. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Initierar en ny instans av  TiffStreamReader  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Byte‑array‑data. |
| startIndex | int | Startindexet i data. |
| dataLength | int | Längden på datan. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Initierar en ny instans av  TiffStreamReader  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |

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
### getLength() {#getLength--}
```
public long getLength()
```


Hämtar läsarens längd.

Värde: Läsarlängden.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till strömmen).

Värde:  true  om undantag kastas vid felaktig databehandling; annars ignoreras felvillkoren tyst.

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




### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Läser en array av byte‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | byte[] | Arrayen att fylla. |
| arrayIndex | int | Arrayindexet att börja lägga in värden i. |
| position | long | Strömpositionen att läsa från. |
| count | long | Antalet element att läsa. |

**Returns:**
long - Arrayen av byte‑värden.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Läser en array av osignerade byte‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
byte[] - Arrayen av osignerade byte‑värden.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Läs ett enda double‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
double - Det enkla dubbelvärdet.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Läser en array av double‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
double[] - Arrayen av dubbelvärden.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Läs ett enda float‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
float - Det enkla flyttalsvärdet.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Läser en array av float‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
float[] - Arrayen av flyttalsvärden.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Läs ett enda rational‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Läser en array av rational‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Arrayen av rationella värden.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Läser signerad byte‑data från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
byte - Det signerade bytevärdet.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Läser en array av signerade byte‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
byte[] - Arrayen av signerade bytevärden.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Läs signerad integer‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
int - Ett signerat heltalsvärde.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Läser en array av signerade integer‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
int[] - Arrayen av signerade heltalsvärden.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Läs ett enda signerat rational‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Läser en array av signerade rational‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - Arrayen av signerade rationella värden.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Läs signerat short‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
short - Ett signerat shortvärde.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Läser en array av signerade short‑värden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
short[] - Arrayen av signerade shortvärden.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Läser strängen från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen. |

**Returns:**
java.lang.String - Strängen.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Läser strängen från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen. |
| längd | long | Längden. |

**Returns:**
java.lang.String - Strängen.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Läs ett osignerat heltalsvärde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
long - Ett osignerat heltalsvärde.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Läser en array av osignerade heltalsvärden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
long[] - Arrayen av osignerade heltalsvärden.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Läs ett osignerat short‑värde från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |

**Returns:**
int - Ett osignerat shortvärde.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Läser en array av osignerade heltalsvärden från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns:**
int[] - Arrayen av osignerade heltalsvärden.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig databehandling (läsa eller skriva till strömmen).

Värde:  true  om undantag kastas vid felaktig databehandling; annars ignoreras felvillkoren tyst.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Konverterar den underliggande datan till strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startPosition | long | Startpositionen att börja konverteringen från. |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  with converted data.
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

