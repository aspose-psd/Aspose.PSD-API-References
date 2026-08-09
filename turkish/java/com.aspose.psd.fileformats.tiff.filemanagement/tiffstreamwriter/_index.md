---
title: "TiffStreamWriter"
second_title: "Java için Aspose.PSD API Referansı"
description: "TIFF akış yazıcı."
type: docs
weight: 11
url: /tr/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

TIFF akış yazıcı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | TiffStreamWriter sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | Akış konumunu alır veya ayarlar. |
| [getSyncRoot()](#getSyncRoot--) | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | Akış konumunu alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | Belirtilen veriyi yazar. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Belirtilen veriyi yazar. |
| [writeDouble(double data)](#writeDouble-double-) | Akıma tek bir double değeri yazar. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Akıma double değerlerinden oluşan bir dizi yazar. |
| [writeFloat(float data)](#writeFloat-float-) | Akıma tek bir float değeri yazar. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Akıma float değerlerinden oluşan bir dizi yazar. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | Akıma tek bir rasyonel sayı değeri yazar. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | Akıma işaretsiz rasyonel değerlerden oluşan bir dizi yazar. |
| [writeSByte(byte data)](#writeSByte-byte-) | Akıma tek bir işaretli byte değeri yazar. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Akıma işaretli byte değerlerinden oluşan bir dizi yazar. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | Akıma tam sayı değerlerinden oluşan bir dizi yazar. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | Akıma tek bir işaretli rasyonel sayı değeri yazar. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | Akıma işaretli rasyonel değerlerden oluşan bir dizi yazar. |
| [writeSShort(short data)](#writeSShort-short-) | Akıma tek bir short değeri yazar. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Akıma short değerlerinden oluşan bir dizi yazar. |
| [writeSlong(int data)](#writeSlong-int-) | Akıma tek bir tam sayı değeri yazar. |
| [writeUByte(byte data)](#writeUByte-byte-) | Akıma tek bir byte değeri yazar. |
| [writeULong(long data)](#writeULong-long-) | Akıma tek bir işaretsiz tam sayı değeri yazar. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Akıma işaretsiz tam sayı değerlerinden oluşan bir dizi yazar. |
| [writeUShort(int data)](#writeUShort-int-) | Akıma tek bir işaretsiz short değeri yazar. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Akıma işaretsiz short değerlerinden oluşan bir dizi yazar. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


TiffStreamWriter sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akım yazıcısı. |

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
### getPosition() {#getPosition--}
```
public long getPosition()
```


Akış konumunu alır veya ayarlar.

Değer: Akım konumu.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

Değer: Eşzamanlı kaynağa erişimi senkronize etmek için kullanılabilecek nesne.

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


Akış konumunu alır veya ayarlar.

Değer: Akım konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

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

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Belirtilen veriyi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Yazılacak veri. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Belirtilen veriyi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Yazılacak veri. |
| offset | int | Veri offseti. |
| dataLength | int | Yazılacak verinin uzunluğu. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Akıma tek bir double değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | double | Yazılacak değer. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Akıma double değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | double[] | Yazılacak dizi. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Akıma tek bir float değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | float | Yazılacak değer. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Akıma float değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | float[] | Yazılacak dizi. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Akıma tek bir rasyonel sayı değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Yazılacak değer. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Akıma işaretsiz rasyonel değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Yazılacak dizi. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Akıma tek bir işaretli byte değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte | Yazılacak değer. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Akıma işaretli byte değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Yazılacak dizi. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


Akıma tam sayı değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int[] | Yazılacak dizi. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Akıma tek bir işaretli rasyonel sayı değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Yazılacak değer. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Akıma işaretli rasyonel değerlerden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Yazılacak dizi. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Akıma tek bir short değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | short | Yazılacak değer. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Akıma short değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | short[] | Yazılacak dizi. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


Akıma tek bir tam sayı değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int | Yazılacak değer. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Akıma tek bir byte değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte | Yazılacak değer. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


Akıma tek bir işaretsiz tam sayı değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long | Yazılacak değer. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


Akıma işaretsiz tam sayı değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long[] | Yazılacak dizi. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Akıma tek bir işaretsiz short değeri yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int | Yazılacak değer. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Akıma işaretsiz short değerlerinden oluşan bir dizi yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int[] | Yazılacak dizi. |

