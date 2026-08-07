---
title: "TiffStreamWriter"
second_title: "Aspose.PSD für Java API-Referenz"
description: "TIFF-Stream-Schreiber."
type: docs
weight: 11
url: /de/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

TIFF-Stream-Schreiber.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | Initialisiert eine neue Instanz der Klasse  TiffStreamWriter  . |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | Liest oder setzt die Stream-Position. |
| [getSyncRoot()](#getSyncRoot--) | Liest ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | Liest oder setzt die Stream-Position. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | Schreibt die angegebenen Daten. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Schreibt die angegebenen Daten. |
| [writeDouble(double data)](#writeDouble-double-) | Schreibt einen einzelnen double-Wert in den Stream. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Schreibt ein Array von double-Werten in den Stream. |
| [writeFloat(float data)](#writeFloat-float-) | Schreibt einen einzelnen float-Wert in den Stream. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Schreibt ein Array von float-Werten in den Stream. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | Schreibt einen einzelnen rationalen Zahlenwert in den Stream. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | Schreibt ein Array von unsigned rational-Werten in den Stream. |
| [writeSByte(byte data)](#writeSByte-byte-) | Schreibt einen einzelnen signed byte-Wert in den Stream. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Schreibt ein Array von signed byte-Werten in den Stream. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | Schreibt ein Array von integer-Werten in den Stream. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | Schreibt einen einzelnen signed rational Zahlenwert in den Stream. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | Schreibt ein Array von signed rational-Werten in den Stream. |
| [writeSShort(short data)](#writeSShort-short-) | Schreibt einen einzelnen short-Wert in den Stream. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Schreibt ein Array von short-Werten in den Stream. |
| [writeSlong(int data)](#writeSlong-int-) | Schreibt einen einzelnen integer-Wert in den Stream. |
| [writeUByte(byte data)](#writeUByte-byte-) | Schreibt einen einzelnen byte-Wert in den Stream. |
| [writeULong(long data)](#writeULong-long-) | Schreibt einen einzelnen unsigned integer-Wert in den Stream. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Schreibt ein Array von unsigned integer-Werten in den Stream. |
| [writeUShort(int data)](#writeUShort-int-) | Schreibt einen einzelnen unsigned short-Wert in den Stream. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Schreibt ein Array von unsigned short-Werten in den Stream. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Initialisiert eine neue Instanz der Klasse  TiffStreamWriter  .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Schreiber. |

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
### getPosition() {#getPosition--}
```
public long getPosition()
```


Liest oder setzt die Stream-Position.

Wert: Die Stream-Position.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Liest ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

Wert: Das Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

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




### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Liest oder setzt die Stream-Position.

Wert: Die Stream-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

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

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Schreibt die angegebenen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Daten zum Schreiben. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Schreibt die angegebenen Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Daten zum Schreiben. |
| Versatz | int | Der Datenversatz. |
| dataLength | int | Länge der Daten zum Schreiben. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Schreibt einen einzelnen double-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | double | Der Wert zum Schreiben. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Schreibt ein Array von double-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | double[] | Das Array zum Schreiben. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Schreibt einen einzelnen float-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | float | Der Wert zum Schreiben. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Schreibt ein Array von float-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | float[] | Das Array zum Schreiben. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Schreibt einen einzelnen rationalen Zahlenwert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Der Wert zum Schreiben. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Schreibt ein Array von unsigned rational-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Das Array zum Schreiben. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Schreibt einen einzelnen signed byte-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte | Der Wert zum Schreiben. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Schreibt ein Array von signed byte-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Das Array zum Schreiben. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


Schreibt ein Array von integer-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | int[] | Das Array zum Schreiben. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Schreibt einen einzelnen signed rational Zahlenwert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Der Wert zum Schreiben. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Schreibt ein Array von signed rational-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Das Array zum Schreiben. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Schreibt einen einzelnen short-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | short | Der Wert zum Schreiben. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Schreibt ein Array von short-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | short[] | Das Array zum Schreiben. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


Schreibt einen einzelnen integer-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | int | Der Wert zum Schreiben. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Schreibt einen einzelnen byte-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte | Der Wert zum Schreiben. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


Schreibt einen einzelnen unsigned integer-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | long | Der Wert zum Schreiben. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


Schreibt ein Array von unsigned integer-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | long[] | Das Array zum Schreiben. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Schreibt einen einzelnen unsigned short-Wert in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | int | Der Wert zum Schreiben. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Schreibt ein Array von unsigned short-Werten in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | int[] | Das Array zum Schreiben. |

