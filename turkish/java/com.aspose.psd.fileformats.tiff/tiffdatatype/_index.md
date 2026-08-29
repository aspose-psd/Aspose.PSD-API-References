---
title: "TiffDataType"
second_title: "Java için Aspose.PSD API Referansı"
description: "tiff veri türü."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

tiff veri türü.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Mevcut örneği aynı türdeki başka bir nesneyle karşılaştırır ve mevcut örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu gösteren bir tamsayı döndürür. |
| [deepClone()](#deepClone--) | Bu örneğin derin bir kopyasını oluşturur. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Ek veri boyutunu bayt olarak alır (12 bayt etiket verisini sığdırmak için yeterli değilse). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Eleman sayısını alır. |
| [getDataSize()](#getDataSize--) | Ek veri boyutunu bayt olarak alır (12 bayt etiket verisini sığdırmak için yeterli değilse). |
| [getId()](#getId--) | Etiket kimliğinin tam sayı temsilini alır. |
| [getTagId()](#getTagId--) | Etiket kimliğini alır. |
| [getTagType()](#getTagType--) | Etiket tipini alır. |
| [getValue()](#getValue--) | Bu veri tipinin içerdiği değeri alır. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Etiketin özel olup olmadığını gösteren bir değeri alır. |
| [isValid()](#isValid--) | Etiket verisinin geçerli olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Etiket verisini okur. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Bu veri tipinin içerdiği değeri ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir  System.String  döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Ek etiket verisini yazar. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Etiket verisini yazar. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Mevcut örneği aynı türdeki başka bir nesneyle karşılaştırır ve mevcut örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu gösteren bir tamsayı döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Bu örnek ile karşılaştırılacak bir nesne. |

**Returns:**
int - Karşılaştırılan nesnelerin göreli sırasını gösteren 32-bit işaretli bir tam sayı. Dönüş değeri şu anlamlara sahiptir: Değer Anlamı Sıfırdan küçük Bu örnek obj'den küçüktür. Sıfır Bu örnek obj'e eşittir. Sıfırdan büyük Bu örnek obj'den büyüktür.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Bu örneğin derin bir kopyasını oluşturur.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Ek veri boyutunu bayt olarak alır (12 bayt etiket verisini sığdırmak için yeterli değilse).

**Returns:**
long - Ek veri boyutunu bayt olarak.

Bu, veri bayt sayısının kelime sınırına hizalanmış halidir.
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


Eleman sayısını alır.

**Returns:**
long - Eleman sayısı.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Ek veri boyutunu bayt olarak alır (12 bayt etiket verisini sığdırmak için yeterli değilse).

**Returns:**
long - Ek veri boyutunu bayt olarak.

Bu kesin bayt sayısıdır.
### getId() {#getId--}
```
public int getId()
```


Etiket kimliğinin tam sayı temsilini alır.

**Returns:**
int - Etiket kimliğinin tam sayı temsili
### getTagId() {#getTagId--}
```
public int getTagId()
```


Etiket kimliğini alır.

**Returns:**
int - Etiket kimliği.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Etiket tipini alır.

**Returns:**
int - Etiket tipi.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Bu veri tipinin içerdiği değeri alır.

**Returns:**
java.lang.Object - Değer.
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


Etiketin özel olup olmadığını gösteren bir değeri alır. Özel tiff etiketleri, 32768'in üzerindeki etiket kimliğine sahip etiketlerdir.

**Returns:**
boolean -  true  etiket verisi geçerli ise; aksi takdirde,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Etiket verisinin geçerli olup olmadığını gösteren bir değer alır. Geçerli etiket, korunabilecek verileri içerir. Geçersiz etiket saklanamaz.

**Returns:**
boolean -  true  etiket verisi geçerli ise; aksi takdirde,  false .
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


Etiket verisini okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | Veri akışı. |
| position | long | Etiket konumu. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Bu veri tipinin içerdiği değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | Değer. |

### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir  System.String  döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir System.String.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Ek etiket verisini yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Veri akışı. |

**Returns:**
long - Gerçek yazılan bayt sayısı.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Etiket verisini yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Veri akışı. |
| additionalDataOffset | long | Ek verinin yazılacağı ofset. |

