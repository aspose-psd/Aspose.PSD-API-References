---
title: "PattResourceData"
second_title: "Java için Aspose.PSD API Referansı"
description: "Kaynak için desen verilerini depolayan sınıf."
type: docs
weight: 67
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

Kaynak için [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) desen verilerini depolayan sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Yeni bir [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Desenin kanallarından elde edilen sıkıştırma yöntemi kodunu döndürür. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Varsayılan desen verisini oluşturur. |
| [getHeight()](#getHeight--) | Yüksekliği alır. |
| [getImageMode()](#getImageMode--) | Görüntü modunu alır. |
| [getLength()](#getLength--) | Desenin uzunluğunu alır. |
| [getName()](#getName--) | Adı alır veya ayarlar. |
| [getPatternData()](#getPatternData--) | Desen verisini alır. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | Bellek dizi listesi. |
| [getPatternId()](#getPatternId--) | Desen tanımlayıcısını alır veya ayarlar. |
| [getVersion()](#getVersion--) | Sürümü alır. |
| [getWidth()](#getWidth--) | Genişliği alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Desen verilerini kaydeder. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Yüksekliği alır. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Görüntü modunu alır. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Dizin renk tablosunu alır veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı alır veya ayarlar. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Desen piksel tamponunu ve hedef boyutunu ayarlar, Genişlik ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Yükseklik ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) günceller ve verileri varsayılan sıkıştırma modu (0) kullanarak kaydetmek için depolar. |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | Bellek dizi listesi. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Desen tanımlayıcısını alır veya ayarlar. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Desen piksel tamponunu ve hedef boyutunu ayarlar, Genişlik ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Yükseklik ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) günceller ve verileri belirtilen sıkıştırma modu kullanarak kaydetmek için depolar. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Sürümü alır. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Genişliği alır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Yeni bir [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) sınıfının örneğini başlatır.

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Desenin kanallarından elde edilen sıkıştırma yöntemi kodunu döndürür.

**Returns:**
byte - Sıkıştırma kodu: 0 \\u2014 ham/sıkıştırılmamış; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


Varsayılan desen verisini oluşturur.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Yüksekliği alır.

Değer: Yükseklik.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Görüntü modunu alır.

Değer: Görüntü modu.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Desenin uzunluğunu alır.

Değer: Desenin uzunluğu.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Adı alır veya ayarlar.

Değer: Ad.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Desen verisini alır.

Değer: Desen verisi.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


Bellek dizi listesi.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Desen tanımlayıcısını alır veya ayarlar.

Değer: Desen tanımlayıcısı.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Sürümü alır.

Değer: Sürüm.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Genişliği alır.

Değer: Genişlik.

**Returns:**
short
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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Desen verilerini kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Yüksekliği alır.

Değer: Yükseklik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Görüntü modunu alır.

Değer: Görüntü modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Dizin renk tablosunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Adı alır veya ayarlar.

Değer: Ad.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Desen piksel tamponunu ve hedef boyutunu ayarlar, Genişlik ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Yükseklik ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) günceller ve verileri varsayılan sıkıştırma modu (0) kullanarak kaydetmek için depolar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| piksel | int[] | 0xAARRGGBB formatında 32-bit pikseller. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Desenin piksel sınırları. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


Bellek dizi listesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Desen tanımlayıcısını alır veya ayarlar.

Değer: Desen tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Desen piksel tamponunu ve hedef boyutunu ayarlar, Genişlik ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Yükseklik ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) günceller ve verileri belirtilen sıkıştırma modu kullanarak kaydetmek için depolar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| piksel | int[] | 0xAARRGGBB formatında 32-bit pikseller. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Desenin piksel sınırları. |
| compressionMode | byte | Desen verisinin sıkıştırmasını tanımlamak için PSD dosyası kaydedilirken kullanılan sıkıştırma modu. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Sürümü alır.

Değer: Sürüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Genişliği alır.

Değer: Genişlik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

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

