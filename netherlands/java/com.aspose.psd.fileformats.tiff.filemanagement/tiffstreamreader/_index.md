---
title: "TiffStreamReader"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De TIFF-stream voor het verwerken van het little-endian TIFF-bestandsformaat."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

De TIFF-stream voor het verwerken van het little-endian TIFF-bestandsformaat.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Initialiseert een nieuw exemplaar van de TiffStreamReader-klasse. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Initialiseert een nieuw exemplaar van de TiffStreamReader-klasse. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Initialiseert een nieuw exemplaar van de TiffStreamReader-klasse. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Initialiseert een nieuw exemplaar van de TiffStreamReader-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Haalt de lengte van de lezer op. |
| [getThrowExceptions()](#getThrowExceptions--) | Haalt een waarde op of stelt deze in die aangeeft of er uitzonderingen worden gegooid bij onjuiste gegevensverwerking (lezen of schrijven naar de stream). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Leest een array van byte-waarden van de stream. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Leest een array van onondertekende byte-waarden van de stream. |
| [readDouble(long position)](#readDouble-long-) | Leest een enkele double-waarde van de stream. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Leest een array van double-waarden van de stream. |
| [readFloat(long position)](#readFloat-long-) | Leest een enkele float-waarde van de stream. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Leest een array van float-waarden van de stream. |
| [readRational(long position)](#readRational-long-) | Leest een enkele rationele getalwaarde van de stream. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Leest een array van rationele waarden van de stream. |
| [readSByte(long position)](#readSByte-long-) | Leest ondertekende byte-gegevens van de stream. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Leest een array van ondertekende byte-waarden van de stream. |
| [readSLong(long position)](#readSLong-long-) | Leest ondertekende integer-waarde van de stream. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Leest een array van ondertekende integer-waarden van de stream. |
| [readSRational(long position)](#readSRational-long-) | Leest een enkele ondertekende rationele getalwaarde van de stream. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Leest een array van ondertekende rationele waarden van de stream. |
| [readSShort(long position)](#readSShort-long-) | Leest ondertekende short-waarde van de stream. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Leest een array van ondertekende short-waarden van de stream. |
| [readString_internalized(long position)](#readString-internalized-long-) | Leest de string van de strea. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Leest de string van de strea. |
| [readULong(long position)](#readULong-long-) | Lees unsigned integer-waarde van de stream. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Leest een array van unsigned integer-waarden van de stream. |
| [readUShort(long position)](#readUShort-long-) | Lees unsigned short-waarde van de stream. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Leest een array van unsigned integer-waarden van de stream. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of er uitzonderingen worden gegooid bij onjuiste gegevensverwerking (lezen of schrijven naar de stream). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Converteert de onderliggende gegevens naar de stream container. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Initialiseert een nieuw exemplaar van de TiffStreamReader-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] | De byte array-gegevens. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Initialiseert een nieuw exemplaar van de TiffStreamReader-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] | De byte array-gegevens. |
| startIndex | int | De startindex in  data . |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Initialiseert een nieuw exemplaar van de TiffStreamReader-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] | De byte array-gegevens. |
| startIndex | int | De startindex in  data . |
| dataLength | int | Lengte van de gegevens. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Initialiseert een nieuw exemplaar van de TiffStreamReader-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |

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


Haalt de lengte van de lezer op.

Waarde: De lezerlengte.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Haalt een waarde op of stelt deze in die aangeeft of er uitzonderingen worden gegooid bij onjuiste gegevensverwerking (lezen of schrijven naar de stream).

Waarde:  true  als er uitzonderingen worden gegooid bij onjuiste gegevensverwerking; anders worden de foutcondities stilletjes genegeerd.

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


Leest een array van byte-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | byte[] | De array om te vullen. |
| arrayIndex | int | De array-index om waarden te beginnen plaatsen. |
| position | long | De streampositie om van te lezen. |
| count | long | Het aantal elementen om te lezen. |

**Returns:**
long - De array van byte-waarden.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Leest een array van onondertekende byte-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
byte[] - De array van unsigned byte-waarden.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Leest een enkele double-waarde van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
double - De enkele double-waarde.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Leest een array van double-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
double[] - De array van double-waarden.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Leest een enkele float-waarde van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
float - De enkele float-waarde.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Leest een array van float-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
float[] - De array van float-waarden.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Leest een enkele rationele getalwaarde van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Leest een array van rationele waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - De array van rationele waarden.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Leest ondertekende byte-gegevens van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
byte - De ondertekende byte-waarde.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Leest een array van ondertekende byte-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
byte[] - De array van ondertekende byte-waarden.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Leest ondertekende integer-waarde van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
int - Een ondertekende integer-waarde.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Leest een array van ondertekende integer-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
int[] - De array van ondertekende integer-waarden.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Leest een enkele ondertekende rationele getalwaarde van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Leest een array van ondertekende rationele waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - De array van ondertekende rationele waarden.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Leest ondertekende short-waarde van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
short - Een ondertekende short-waarde.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Leest een array van ondertekende short-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
short[] - De array van ondertekende short-waarden.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Leest de string van de strea.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie. |

**Returns:**
java.lang.String - De string.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Leest de string van de strea.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie. |
| lengte | long | De lengte. |

**Returns:**
java.lang.String - De string.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Lees unsigned integer-waarde van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
long - Een niet-ondertekende integer-waarde.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Leest een array van unsigned integer-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
long[] - De array van niet-ondertekende integer-waarden.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Lees unsigned short-waarde van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |

**Returns:**
int - Een niet-ondertekende short-waarde.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Leest een array van unsigned integer-waarden van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns:**
int[] - De array van niet-ondertekende integer-waarden.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of er uitzonderingen worden gegooid bij onjuiste gegevensverwerking (lezen of schrijven naar de stream).

Waarde:  true  als er uitzonderingen worden gegooid bij onjuiste gegevensverwerking; anders worden de foutcondities stilletjes genegeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Converteert de onderliggende gegevens naar de stream container.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startPosition | long | De startpositie om vanaf te converteren. |

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

