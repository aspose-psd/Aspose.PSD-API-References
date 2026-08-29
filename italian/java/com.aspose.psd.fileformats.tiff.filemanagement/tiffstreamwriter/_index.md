---
title: "TiffStreamWriter"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Scrittore di flusso TIFF."
type: docs
weight: 11
url: /it/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

Scrittore di flusso TIFF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | Inizializza una nuova istanza della classe TiffStreamWriter. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | Ottiene o imposta la posizione del flusso. |
| [getSyncRoot()](#getSyncRoot--) | Ottiene un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | Ottiene o imposta la posizione del flusso. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | Scrive i dati specificati. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Scrive i dati specificati. |
| [writeDouble(double data)](#writeDouble-double-) | Scrive un singolo valore double nel flusso. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Scrive un array di valori double nel flusso. |
| [writeFloat(float data)](#writeFloat-float-) | Scrive un singolo valore float nel flusso. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Scrive un array di valori float nel flusso. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | Scrive un singolo valore di numero razionale nel flusso. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | Scrive un array di valori razionali non firmati nel flusso. |
| [writeSByte(byte data)](#writeSByte-byte-) | Scrive un singolo valore byte con segno nel flusso. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Scrive un array di valori byte con segno nel flusso. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | Scrive un array di valori interi nel flusso. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | Scrive un singolo valore razionale con segno nello stream. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | Scrive un array di valori razionali con segno nello stream. |
| [writeSShort(short data)](#writeSShort-short-) | Scrive un singolo valore short nello stream. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Scrive un array di valori short nello stream. |
| [writeSlong(int data)](#writeSlong-int-) | Scrive un singolo valore integer nello stream. |
| [writeUByte(byte data)](#writeUByte-byte-) | Scrive un singolo valore byte nello stream. |
| [writeULong(long data)](#writeULong-long-) | Scrive un singolo valore unsigned integer nello stream. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Scrive un array di valori unsigned integer nello stream. |
| [writeUShort(int data)](#writeUShort-int-) | Scrive un singolo valore unsigned short nello stream. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Scrive un array di valori unsigned short nello stream. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Inizializza una nuova istanza della classe TiffStreamWriter.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il writer dello stream. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene o imposta la posizione del flusso.

Valore: La posizione dello stream.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Ottiene un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

Valore: L'oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata.

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


Ottiene o imposta la posizione del flusso.

Valore: La posizione dello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Scrive i dati specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati da scrivere. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Scrive i dati specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati da scrivere. |
| offset | int | L'offset dei dati. |
| dataLength | int | Lunghezza dei dati da scrivere. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Scrive un singolo valore double nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | double | Il valore da scrivere. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Scrive un array di valori double nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | double[] | L'array da scrivere. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Scrive un singolo valore float nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | float | Il valore da scrivere. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Scrive un array di valori float nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | float[] | L'array da scrivere. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Scrive un singolo valore di numero razionale nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Il valore da scrivere. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Scrive un array di valori razionali non firmati nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | L'array da scrivere. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Scrive un singolo valore byte con segno nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte | Il valore da scrivere. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Scrive un array di valori byte con segno nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | L'array da scrivere. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


Scrive un array di valori interi nel flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int[] | L'array da scrivere. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Scrive un singolo valore razionale con segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Il valore da scrivere. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Scrive un array di valori razionali con segno nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | L'array da scrivere. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Scrive un singolo valore short nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | short | Il valore da scrivere. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Scrive un array di valori short nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | short[] | L'array da scrivere. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


Scrive un singolo valore integer nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int | Il valore da scrivere. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Scrive un singolo valore byte nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte | Il valore da scrivere. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


Scrive un singolo valore unsigned integer nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long | Il valore da scrivere. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


Scrive un array di valori unsigned integer nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long[] | L'array da scrivere. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Scrive un singolo valore unsigned short nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int | Il valore da scrivere. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Scrive un array di valori unsigned short nello stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int[] | L'array da scrivere. |

