---
title: "TiffStreamReader"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le flux TIFF pour gérer le format de fichier TIFF little endian."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

Le flux TIFF pour gérer le format de fichier TIFF little endian.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Initialise une nouvelle instance de la classe TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Initialise une nouvelle instance de la classe TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Initialise une nouvelle instance de la classe TiffStreamReader. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Initialise une nouvelle instance de la classe TiffStreamReader. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtient la longueur du lecteur. |
| [getThrowExceptions()](#getThrowExceptions--) | Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement incorrect des données (lecture ou écriture du flux). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Lit un tableau de valeurs byte depuis le flux. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Lit un tableau de valeurs byte non signées depuis le flux. |
| [readDouble(long position)](#readDouble-long-) | Lit une seule valeur double depuis le flux. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Lit un tableau de valeurs double depuis le flux. |
| [readFloat(long position)](#readFloat-long-) | Lit une seule valeur float depuis le flux. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Lit un tableau de valeurs flottantes depuis le flux. |
| [readRational(long position)](#readRational-long-) | Lit une seule valeur de nombre rationnel depuis le flux. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Lit un tableau de valeurs rationnelles depuis le flux. |
| [readSByte(long position)](#readSByte-long-) | Lit des données d'octet signé depuis le flux. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Lit un tableau de valeurs d'octet signé depuis le flux. |
| [readSLong(long position)](#readSLong-long-) | Lit une valeur d'entier signé depuis le flux. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Lit un tableau de valeurs d'entier signé depuis le flux. |
| [readSRational(long position)](#readSRational-long-) | Lit une seule valeur de nombre rationnel signé depuis le flux. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Lit un tableau de valeurs rationnelles signées depuis le flux. |
| [readSShort(long position)](#readSShort-long-) | Lit une valeur de court signé depuis le flux. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Lit un tableau de valeurs de court signé depuis le flux. |
| [readString_internalized(long position)](#readString-internalized-long-) | Lit la chaîne depuis le flux. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Lit la chaîne depuis le flux. |
| [readULong(long position)](#readULong-long-) | Lit une valeur d'entier non signé depuis le flux. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Lit un tableau de valeurs d'entier non signé depuis le flux. |
| [readUShort(long position)](#readUShort-long-) | Lit une valeur de court non signé depuis le flux. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Lit un tableau de valeurs d'entier non signé depuis le flux. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement incorrect des données (lecture ou écriture du flux). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Convertit les données sous-jacentes en conteneur de flux. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Initialise une nouvelle instance de la classe TiffStreamReader.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Initialise une nouvelle instance de la classe TiffStreamReader.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |
| startIndex | int | L'index de départ dans les données. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Initialise une nouvelle instance de la classe TiffStreamReader.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données du tableau d'octets. |
| startIndex | int | L'index de départ dans les données. |
| dataLength | int | Longueur des données. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Initialise une nouvelle instance de la classe TiffStreamReader.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient la longueur du lecteur.

Valeur : la longueur du lecteur.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement incorrect des données (lecture ou écriture du flux).

Valeur :  vrai  si des exceptions sont levées lors d'un traitement de données incorrect ; sinon, les conditions d'erreur sont silencieusement ignorées.

**Returns:**
booléen
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


Lit un tableau de valeurs byte depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tableau | byte[] | Le tableau à remplir. |
| arrayIndex | int | L'index du tableau où commencer à placer les valeurs. |
| position | long | La position du flux à lire. |
| count | long | Le nombre d'éléments à lire. |

**Returns:**
long - Le tableau de valeurs d'octets.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Lit un tableau de valeurs byte non signées depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
byte[] - Le tableau de valeurs d'octets non signés.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Lit une seule valeur double depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
double - La valeur double unique.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Lit un tableau de valeurs double depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
double[] - Le tableau de valeurs doubles.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Lit une seule valeur float depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
float - La valeur float unique.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Lit un tableau de valeurs flottantes depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
float[] - Le tableau de valeurs float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Lit une seule valeur de nombre rationnel depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Lit un tableau de valeurs rationnelles depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Le tableau de valeurs rationnelles.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Lit des données d'octet signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
byte - La valeur d'octet signé.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Lit un tableau de valeurs d'octet signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
byte[] - Le tableau de valeurs d'octets signés.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Lit une valeur d'entier signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
int - Une valeur entière signée.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Lit un tableau de valeurs d'entier signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
int[] - Le tableau de valeurs entières signées.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Lit une seule valeur de nombre rationnel signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Lit un tableau de valeurs rationnelles signées depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - Le tableau de valeurs rationnelles signées.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Lit une valeur de court signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
short - Une valeur short signée.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Lit un tableau de valeurs de court signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
short[] - Le tableau de valeurs short signées.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Lit la chaîne depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position. |

**Returns:**
java.lang.String - La chaîne.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Lit la chaîne depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position. |
| length | long | La longueur. |

**Returns:**
java.lang.String - La chaîne.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Lit une valeur d'entier non signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
long - Une valeur entière non signée.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Lit un tableau de valeurs d'entier non signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
long[] - Le tableau de valeurs entières non signées.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Lit une valeur de court non signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |

**Returns:**
int - Une valeur courte non signée.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Lit un tableau de valeurs d'entier non signé depuis le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns:**
int[] - Le tableau de valeurs entières non signées.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement incorrect des données (lecture ou écriture du flux).

Valeur :  vrai  si des exceptions sont levées lors d'un traitement de données incorrect ; sinon, les conditions d'erreur sont silencieusement ignorées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Convertit les données sous-jacentes en conteneur de flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startPosition | long | La position de départ à partir de laquelle commencer la conversion. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

