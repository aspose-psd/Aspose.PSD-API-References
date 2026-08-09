---
title: "TiffStreamReader"
second_title: "Java için Aspose.PSD API Referansı"
description: "Little endian TIFF dosya formatını işlemek için TIFF akışı."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

Little endian TIFF dosya formatını işlemek için TIFF akışı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | TiffStreamReader sınıfının yeni bir örneğini başlatır. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | TiffStreamReader sınıfının yeni bir örneğini başlatır. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | TiffStreamReader sınıfının yeni bir örneğini başlatır. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | TiffStreamReader sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Okuyucu uzunluğunu alır. |
| [getThrowExceptions()](#getThrowExceptions--) | Yanlış veri işleme (akışa okuma veya yazma) sırasında istisnaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Akıştan bir dizi byte değeri okur. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Akıştan işaretsiz byte değerlerinden oluşan bir dizi okur. |
| [readDouble(long position)](#readDouble-long-) | Akıştan tek bir double değer okur. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Akıştan double değerlerinden oluşan bir dizi okur. |
| [readFloat(long position)](#readFloat-long-) | Akıştan tek bir float değer okur. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Akıştan float değerlerinden oluşan bir dizi okur. |
| [readRational(long position)](#readRational-long-) | Akıştan tek bir rasyonel sayı değeri okur. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Akıştan rasyonel değerlerden oluşan bir dizi okur. |
| [readSByte(long position)](#readSByte-long-) | Akıştan işaretli bayt verilerini okur. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Akıştan işaretli bayt değerlerinden oluşan bir dizi okur. |
| [readSLong(long position)](#readSLong-long-) | Akıştan işaretli tam sayı değerini okur. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Akıştan işaretli tam sayı değerlerinden oluşan bir dizi okur. |
| [readSRational(long position)](#readSRational-long-) | Akıştan tek bir işaretli rasyonel sayı değeri okur. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Akıştan işaretli rasyonel değerlerden oluşan bir dizi okur. |
| [readSShort(long position)](#readSShort-long-) | Akıştan işaretli kısa değerini okur. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Akıştan işaretli kısa değerlerden oluşan bir dizi okur. |
| [readString_internalized(long position)](#readString-internalized-long-) | Akıştan dizeyi okur. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Akıştan dizeyi okur. |
| [readULong(long position)](#readULong-long-) | Akıştan işaretsiz tam sayı değerini okur. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Akıştan işaretsiz tam sayı değerlerinden oluşan bir dizi okur. |
| [readUShort(long position)](#readUShort-long-) | Akıştan işaretsiz kısa değerini okur. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Akıştan işaretsiz tam sayı değerlerinden oluşan bir dizi okur. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Yanlış veri işleme (akışa okuma veya yazma) sırasında istisnaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Temel verileri akış konteynerine dönüştürür. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


TiffStreamReader sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Bayt dizi verisi. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


TiffStreamReader sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Bayt dizi verisi. |
| startIndex | int | Veriye giriş için başlangıç indeksi. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


TiffStreamReader sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Bayt dizi verisi. |
| startIndex | int | Veriye giriş için başlangıç indeksi. |
| dataLength | int | Verinin uzunluğu. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


TiffStreamReader sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Okuyucu uzunluğunu alır.

Değer: Okuyucu uzunluğu.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Yanlış veri işleme (akışa okuma veya yazma) sırasında istisnaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar.

Değer:  true  eğer hatalı veri işleme sırasında istisnalar atılırsa; aksi takdirde, hata koşulları sessizce yok sayılır.

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


Akıştan bir dizi byte değeri okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizi | byte[] | Doldurulacak dizi. |
| arrayIndex | int | Değerleri koymaya başlanacak dizi indeksi. |
| position | long | Okunacak akış konumu. |
| count | long | Okunacak öğe sayısı. |

**Returns:**
long - Bayt değerlerinin dizisi.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Akıştan işaretsiz byte değerlerinden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
byte[] - İşaretsiz bayt değerlerinin dizisi.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Akıştan tek bir double değer okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
double - Tek double değeri.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Akıştan double değerlerinden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
double[] - Double değerlerinin dizisi.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Akıştan tek bir float değer okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
float - Tek float değeri.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Akıştan float değerlerinden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
float[] - Float değerlerinin dizisi.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Akıştan tek bir rasyonel sayı değeri okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Akıştan rasyonel değerlerden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Rasyonel değerlerin dizisi.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Akıştan işaretli bayt verilerini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
byte - İşaretli bayt değeri.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Akıştan işaretli bayt değerlerinden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
byte[] - İşaretli bayt değerlerinin dizisi.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Akıştan işaretli tam sayı değerini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
int - İşaretli tam sayı değeri.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Akıştan işaretli tam sayı değerlerinden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
int[] - İşaretli tam sayı değerlerinin dizisi.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Akıştan tek bir işaretli rasyonel sayı değeri okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Akıştan işaretli rasyonel değerlerden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - İşaretli rasyonel değerlerin dizisi.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Akıştan işaretli kısa değerini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
short - İşaretli kısa değer.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Akıştan işaretli kısa değerlerden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
short[] - İşaretli kısa değerlerin dizisi.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Akıştan dizeyi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Konum. |

**Returns:**
java.lang.String - Dize.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Akıştan dizeyi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Konum. |
| length | long | Uzunluk. |

**Returns:**
java.lang.String - Dize.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Akıştan işaretsiz tam sayı değerini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
long - İşaretsiz tamsayı değeri.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Akıştan işaretsiz tam sayı değerlerinden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
long[] - İşaretsiz tamsayı değerlerinin dizisi.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Akıştan işaretsiz kısa değerini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |

**Returns:**
int - İşaretsiz kısa değer.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Akıştan işaretsiz tam sayı değerlerinden oluşan bir dizi okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Okunacak konum. |
| count | long | Öğe sayısı. |

**Returns:**
int[] - İşaretsiz tamsayı değerlerinin dizisi.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Yanlış veri işleme (akışa okuma veya yazma) sırasında istisnaların atılıp atılmayacağını belirten bir değeri alır veya ayarlar.

Değer:  true  eğer hatalı veri işleme sırasında istisnalar atılırsa; aksi takdirde, hata koşulları sessizce yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Temel verileri akış konteynerine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startPosition | long | Dönüşümün başlayacağı başlangıç konumu. |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

