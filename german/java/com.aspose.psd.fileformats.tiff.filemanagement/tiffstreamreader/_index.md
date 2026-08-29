---
title: "TiffStreamReader"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der TIFF-Stream zur Handhabung des Little-Endian-TIFF-Dateiformats."
type: docs
weight: 10
url: /de/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

Der TIFF-Stream zur Handhabung des Little-Endian-TIFF-Dateiformats.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Initialisiert eine neue Instanz der Klasse TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Initialisiert eine neue Instanz der Klasse TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Initialisiert eine neue Instanz der Klasse TiffStreamReader. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Initialisiert eine neue Instanz der Klasse TiffStreamReader. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Ruft die Länge des Lesers ab. |
| [getThrowExceptions()](#getThrowExceptions--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Liest ein Array von Byte-Werten aus dem Stream. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Liest ein Array von vorzeichenlosen Byte-Werten aus dem Stream. |
| [readDouble(long position)](#readDouble-long-) | Liest einen einzelnen double-Wert aus dem Stream. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Liest ein Array von double-Werten aus dem Stream. |
| [readFloat(long position)](#readFloat-long-) | Liest einen einzelnen float-Wert aus dem Stream. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Liest ein Array von Float-Werten aus dem Stream. |
| [readRational(long position)](#readRational-long-) | Liest einen einzelnen rationalen Zahlenwert aus dem Stream. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Liest ein Array von rationalen Werten aus dem Stream. |
| [readSByte(long position)](#readSByte-long-) | Liest signierte Byte-Daten aus dem Stream. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Liest ein Array von signierten Byte-Werten aus dem Stream. |
| [readSLong(long position)](#readSLong-long-) | Liest einen signierten Ganzzahlwert aus dem Stream. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Liest ein Array von signierten Ganzzahlwerten aus dem Stream. |
| [readSRational(long position)](#readSRational-long-) | Liest einen einzelnen signierten rationalen Zahlenwert aus dem Stream. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Liest ein Array von signierten rationalen Werten aus dem Stream. |
| [readSShort(long position)](#readSShort-long-) | Liest einen signierten Short-Wert aus dem Stream. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Liest ein Array von signierten Short-Werten aus dem Stream. |
| [readString_internalized(long position)](#readString-internalized-long-) | Liest die Zeichenkette aus dem Stream. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Liest die Zeichenkette aus dem Stream. |
| [readULong(long position)](#readULong-long-) | Liest einen unsignierten Ganzzahlwert aus dem Stream. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Liest ein Array von unsignierten Ganzzahlwerten aus dem Stream. |
| [readUShort(long position)](#readUShort-long-) | Liest einen unsignierten Short-Wert aus dem Stream. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Liest ein Array von unsignierten Ganzzahlwerten aus dem Stream. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Konvertiert die zugrunde liegenden Daten in den Stream-Container. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Initialisiert eine neue Instanz der Klasse TiffStreamReader.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte-Array-Daten. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Initialisiert eine neue Instanz der Klasse TiffStreamReader.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte-Array-Daten. |
| startIndex | int | Der Startindex in die Daten. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Initialisiert eine neue Instanz der Klasse TiffStreamReader.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Byte-Array-Daten. |
| startIndex | int | Der Startindex in die Daten. |
| dataLength | int | Länge der Daten. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Initialisiert eine neue Instanz der Klasse TiffStreamReader.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Ruft die Länge des Lesers ab.

Wert: Die Reader-Länge.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden.

Wert:  true  wenn Ausnahmen bei falscher Datenverarbeitung ausgelöst werden; andernfalls werden Fehlbedingungen stillschweigend ignoriert.

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


Liest ein Array von Byte-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Array | byte[] | Das zu füllende Array. |
| arrayIndex | int | Der Array-Index, an dem Werte eingefügt werden sollen. |
| position | long | Die Stream-Position, von der gelesen wird. |
| count | long | Die Anzahl der zu lesenden Elemente. |

**Returns:**
long - Das Array von Byte-Werten.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Liest ein Array von vorzeichenlosen Byte-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
byte[] - Das Array von vorzeichenlosen Byte-Werten.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Liest einen einzelnen double-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
double - Der einzelne Double-Wert.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Liest ein Array von double-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
double[] - Das Array von Double-Werten.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Liest einen einzelnen float-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
float - Der einzelne Float-Wert.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Liest ein Array von Float-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
float[] - Das Array von Float-Werten.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Liest einen einzelnen rationalen Zahlenwert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Liest ein Array von rationalen Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Das Array von rationalen Werten.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Liest signierte Byte-Daten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
byte - Der vorzeichenbehaftete Byte-Wert.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Liest ein Array von signierten Byte-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
byte[] - Das Array von vorzeichenbehafteten Byte-Werten.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Liest einen signierten Ganzzahlwert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
int - Ein vorzeichenbehafteter Ganzzahlwert.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Liest ein Array von signierten Ganzzahlwerten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
int[] - Das Array von vorzeichenbehafteten Ganzzahlwerten.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Liest einen einzelnen signierten rationalen Zahlenwert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Liest ein Array von signierten rationalen Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - Das Array von vorzeichenbehafteten rationalen Werten.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Liest einen signierten Short-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
short - Ein vorzeichenbehafteter Short-Wert.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Liest ein Array von signierten Short-Werten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
short[] - Das Array von vorzeichenbehafteten Short-Werten.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Liest die Zeichenkette aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position. |

**Returns:**
java.lang.String - Die Zeichenkette.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Liest die Zeichenkette aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position. |
| length | long | Die Länge. |

**Returns:**
java.lang.String - Die Zeichenkette.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Liest einen unsignierten Ganzzahlwert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
long - Ein vorzeichenloser Ganzzahlwert.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Liest ein Array von unsignierten Ganzzahlwerten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
long[] - Das Array von vorzeichenlosen Ganzzahlwerten.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Liest einen unsignierten Short-Wert aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |

**Returns:**
int - Ein vorzeichenloser Kurzwert.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Liest ein Array von unsignierten Ganzzahlwerten aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, von der gelesen wird. |
| count | long | Die Elementanzahl. |

**Returns:**
int[] - Das Array von vorzeichenlosen Ganzzahlwerten.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden.

Wert:  true  wenn Ausnahmen bei falscher Datenverarbeitung ausgelöst werden; andernfalls werden Fehlbedingungen stillschweigend ignoriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Konvertiert die zugrunde liegenden Daten in den Stream-Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startPosition | long | Die Startposition, ab der die Konvertierung beginnt. |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

