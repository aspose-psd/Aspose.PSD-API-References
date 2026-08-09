---
title: "ChannelInformation"
second_title: "Java için Aspose.PSD API Referansı"
description: "Kanal bilgisi."
type: docs
weight: 13
url: /tr/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

Kanal bilgisi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | Kullanıcı (raster) maske kanal kimliği. |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | Kısa (raster veya vektör) maske kanal kimliği. |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | Alfa kanal kimliği. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Kanal verilerini sıkıştırır. |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Belirtilen kanal bilgisini kopyalar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Kanal bit derinliğini alır. |
| [getChannelID()](#getChannelID--) | Kanal kimliğini alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Sıkıştırma yöntemini alır veya ayarlar. |
| [getData_internalized()](#getData-internalized--) | Kanal verisini alır veya ayarlar. |
| [getLength()](#getLength--) | Kanal uzunluğunu bayt cinsinden alır. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | PSD sürümünü alır. |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Sıkıştırılmamış veriyi alır. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Kanalın ShortMask olup olmadığını alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Kanal verisini kaydeder. |
| [setChannelID(short value)](#setChannelID-short-) | Kanal kimliğini alır veya ayarlar. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Sıkıştırılmış veriyi ayarlar. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Sıkıştırma yöntemini alır veya ayarlar. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Sıkıştırılmış veriyi ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


Kullanıcı (raster) maske kanal kimliği. (bir katmanın hem vektör hem raster maskesi varsa).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


Kısa (raster veya vektör) maske kanal kimliği. (bir katmanın yalnızca bir vektör veya raster maskesi varsa, ikisi birden değil).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


Alfa kanal kimliği.

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Kanal verilerini sıkıştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rawData | byte[] | Sıkıştırma için ham veri |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Katmanın sınırları. |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | Katman maskesinin sınırları. |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| width | int |  |
| height | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Belirtilen kanal bilgisini kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Bilgi. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - Kopyalanmış katman maskesi.
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
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Kanal bit derinliğini alır.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Kanal kimliğini alır veya ayarlar.

Değer: Kanal kimliği.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Sıkıştırma yöntemini alır veya ayarlar.

Değer: Sıkıştırma yöntemi.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Kanal verisini alır veya ayarlar.

Değer: Kanal verisi.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Kanal uzunluğunu bayt cinsinden alır.

Değer: Uzunluk.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


PSD sürümünü alır.

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Sıkıştırılmamış veriyi alır.

**Returns:**
byte[] -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


Kanalın ShortMask olup olmadığını alır.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Kanal verisini kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| is32BitColor | boolean | renk 32-bit modundaysa true |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Kanal kimliğini alır veya ayarlar.

Değer: Kanal kimliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Sıkıştırılmış veriyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| compressedData | byte[] | Sıkıştırılmış veri. |
| channelWidth | int | Kanalın genişliği. |
| channelHeight | int | Kanalın yüksekliği. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Sıkıştırma yöntemini alır veya ayarlar.

Değer: Sıkıştırma yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Sıkıştırılmış veriyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rawData | byte[] | Ham veri. |
| imageSize | [Size](../../com.aspose.psd/size) | Görselin boyutu |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | Mevcut channelData sınırları. Görsel büyükse işlem sırasında bölünecek ve currentBounds != imageBounds |

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

