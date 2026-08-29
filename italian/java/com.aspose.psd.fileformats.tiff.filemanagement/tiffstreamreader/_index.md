---
title: "TiffStreamReader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il flusso TIFF per la gestione del formato file TIFF little endian."
type: docs
weight: 10
url: /it/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

Il flusso TIFF per la gestione del formato file TIFF little endian.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Inizializza una nuova istanza della classe  TiffStreamReader  . |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Inizializza una nuova istanza della classe  TiffStreamReader  . |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Inizializza una nuova istanza della classe  TiffStreamReader  . |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Inizializza una nuova istanza della classe  TiffStreamReader  . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Restituisce la lunghezza del lettore. |
| [getThrowExceptions()](#getThrowExceptions--) | Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura sullo stream). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Legge un array di valori byte dallo stream. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Legge un array di valori byte senza segno dallo stream. |
| [readDouble(long position)](#readDouble-long-) | Legge un singolo valore double dallo stream. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Legge un array di valori double dallo stream. |
| [readFloat(long position)](#readFloat-long-) | Legge un singolo valore float dallo stream. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Legge un array di valori float dallo stream. |
| [readRational(long position)](#readRational-long-) | Legge un singolo valore di numero razionale dallo stream. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Legge un array di valori razionali dallo stream. |
| [readSByte(long position)](#readSByte-long-) | Legge dati byte con segno dallo stream. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Legge un array di valori byte con segno dallo stream. |
| [readSLong(long position)](#readSLong-long-) | Legge un valore intero con segno dallo stream. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Legge un array di valori interi con segno dallo stream. |
| [readSRational(long position)](#readSRational-long-) | Legge un singolo valore di numero razionale con segno dallo stream. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Legge un array di valori razionali con segno dallo stream. |
| [readSShort(long position)](#readSShort-long-) | Legge un valore short con segno dallo stream. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Legge un array di valori short con segno dallo stream. |
| [readString_internalized(long position)](#readString-internalized-long-) | Legge la stringa dallo stream. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Legge la stringa dallo stream. |
| [readULong(long position)](#readULong-long-) | Legge un valore intero senza segno dallo stream. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Legge un array di valori interi senza segno dallo stream. |
| [readUShort(long position)](#readUShort-long-) | Legge un valore short senza segno dallo stream. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Legge un array di valori interi senza segno dallo stream. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura sullo stream). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Converte i dati sottostanti nel contenitore di stream. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Inizializza una nuova istanza della classe  TiffStreamReader  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati dell'array di byte. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Inizializza una nuova istanza della classe  TiffStreamReader  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati dell'array di byte. |
| startIndex | int | L'indice di partenza nei dati. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Inizializza una nuova istanza della classe  TiffStreamReader  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati dell'array di byte. |
| startIndex | int | L'indice di partenza nei dati. |
| dataLength | int | Lunghezza dei dati. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Inizializza una nuova istanza della classe  TiffStreamReader  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |

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
### getLength() {#getLength--}
```
public long getLength()
```


Restituisce la lunghezza del lettore.

Valore: La lunghezza del lettore.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura sullo stream).

Valore:  true  se le eccezioni vengono sollevate durante l'elaborazione di dati errati; altrimenti, le condizioni di errore vengono ignorate silenziosamente.

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


Legge un array di valori byte dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | byte[] | L'array da riempire. |
| arrayIndex | int | L'indice dell'array da cui iniziare a inserire i valori. |
| position | long | La posizione dello stream da cui leggere. |
| count | long | Il conteggio degli elementi da leggere. |

**Returns:**
long - L'array di valori byte.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Legge un array di valori byte senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
byte[] - L'array di valori byte senza segno.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Legge un singolo valore double dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
double - Il valore double singolo.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Legge un array di valori double dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
double[] - L'array di valori double.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Legge un singolo valore float dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
float - Il valore float singolo.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Legge un array di valori float dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
float[] - L'array di valori float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Legge un singolo valore di numero razionale dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Legge un array di valori razionali dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - L'array di valori razionali.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Legge dati byte con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
byte - Il valore byte con segno.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Legge un array di valori byte con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
byte[] - L'array di valori byte con segno.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Legge un valore intero con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
int - Un valore intero con segno.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Legge un array di valori interi con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
int[] - L'array di valori interi con segno.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Legge un singolo valore di numero razionale con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Legge un array di valori razionali con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - L'array di valori razionali con segno.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Legge un valore short con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
short - Un valore short con segno.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Legge un array di valori short con segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
short[] - L'array di valori short con segno.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Legge la stringa dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione. |

**Returns:**
java.lang.String - La stringa.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Legge la stringa dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione. |
| lunghezza | long | La lunghezza. |

**Returns:**
java.lang.String - La stringa.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Legge un valore intero senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
long - Un valore intero senza segno.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Legge un array di valori interi senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
long[] - L'array di valori interi senza segno.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Legge un valore short senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |

**Returns:**
int - Un valore short senza segno.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Legge un array di valori interi senza segno dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | long | La posizione da cui leggere. |
| count | long | Il conteggio degli elementi. |

**Returns:**
int[] - L'array di valori interi senza segno.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura sullo stream).

Valore:  true  se le eccezioni vengono sollevate durante l'elaborazione di dati errati; altrimenti, le condizioni di errore vengono ignorate silenziosamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Converte i dati sottostanti nel contenitore di stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startPosition | long | La posizione iniziale da cui avviare la conversione. |

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

