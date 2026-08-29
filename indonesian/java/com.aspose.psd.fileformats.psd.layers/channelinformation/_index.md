---
title: "ChannelInformation"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Informasi saluran."
type: docs
weight: 13
url: /id/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

Informasi saluran.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | Id saluran masker (raster) pengguna. |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | Id saluran masker pendek (raster atau vektor). |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | Id saluran alfa |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Ini mengompresi data saluran |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Menggandakan informasi saluran yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Mendapatkan kedalaman bit saluran. |
| [getChannelID()](#getChannelID--) | Mendapatkan atau mengatur ID saluran. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Mendapatkan atau mengatur metode kompresi. |
| [getData_internalized()](#getData-internalized--) | Mendapatkan atau mengatur data saluran. |
| [getLength()](#getLength--) | Mendapatkan panjang saluran dalam byte. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Mendapatkan versi PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Mendapatkan data yang tidak terkompresi. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Mendapatkan apakah saluran adalah ShortMask atau tidak |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Menyimpan data saluran. |
| [setChannelID(short value)](#setChannelID-short-) | Mendapatkan atau mengatur ID saluran. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Mengatur data terkompresi. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Mendapatkan atau mengatur metode kompresi. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Mengatur data terkompresi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


Id saluran masker pengguna (raster). (jika sebuah lapisan memiliki vektor dan masker raster).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


Id saluran masker pendek (raster atau vektor). (jika sebuah lapisan hanya memiliki satu masker vektor atau raster tetapi tidak keduanya).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


Id saluran alfa

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Ini mengompresi data saluran

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rawData | byte[] | Data mentah untuk kompresi |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas lapisan |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas masker lapisan |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| lebar | int |  |
| tinggi | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Menggandakan informasi saluran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Informasi. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - Masker lapisan yang dikloning.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Mendapatkan kedalaman bit saluran.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Mendapatkan atau mengatur ID saluran.

Nilai: ID saluran.

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


Mendapatkan atau mengatur metode kompresi.

Nilai: Metode kompresi.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Mendapatkan atau mengatur data saluran.

Nilai: Data saluran.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Mendapatkan panjang saluran dalam byte.

Nilai: Panjang.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Mendapatkan versi PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Mendapatkan data yang tidak terkompresi.

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


Mendapatkan apakah saluran adalah ShortMask atau tidak

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Menyimpan data saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| is32BitColor | boolean | true jika warna berada dalam mode 32-bit |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Mendapatkan atau mengatur ID saluran.

Nilai: ID saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Mengatur data terkompresi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| compressedData | byte[] | Data terkompresi. |
| channelWidth | int | Lebar saluran. |
| channelHeight | int | Tinggi saluran. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Mendapatkan atau mengatur metode kompresi.

Nilai: Metode kompresi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Mengatur data terkompresi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rawData | byte[] | Data mentah. |
| imageSize | [Size](../../com.aspose.psd/size) | Ukuran gambar |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas data channelData saat ini. Jika gambar besar, akan dibagi selama proses dan currentBounds != imageBounds |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

