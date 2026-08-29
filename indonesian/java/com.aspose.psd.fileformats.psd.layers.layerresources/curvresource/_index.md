---
title: "CurvResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas CurvResource."
type: docs
weight: 23
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CurvResource extends AdjustmentLayerResource
```

Kelas CurvResource. Sumber daya dari Layer Penyesuaian Kurva 1 byte - 0 jika menggunakan kurva, 1 jika menggunakan piksel pada peta jika 0 maka: 2 byte - short. Defaultnya 1 4 byte - int. Hanya byte terakhir yang digunakan per bit. Bit pertama untuk 1 saluran, bit keempat untuk 4 saluran misalnya 2 byte - short jumlah titik 4 byte \* jumlah titik - titik-titik kurva 2 short: posisi pertama, tinggi kedua 4 byte - kata \"Crv \" 2 byte - short defaultnya 4 untuk Kurva 4 byte - int. Defaultnya 1 4 byte - jumlah titik 4 byte \* jumlah titik - titik-titik kurva 2 short: posisi pertama, tinggi kedua 0-4 byte - Memimpin untuk dilipat menjadi empat jika 1 maka: 2 byte - short. Defaultnya 1 4 byte - int. Hanya byte terakhir yang digunakan. Satu saluran berada dalam satu bit. Bit pertama untuk 1 saluran, bit keempat untuk 4 saluran misalnya 256 \* jumlah saluran yang berubah - nilai terurut saluran dalam rentang 0 - 255 4 byte - kata \"Crv \" 2 byte - short. Defaultnya 3 untuk piksel pada peta 4 byte - int Jumlah saluran (2 + 256) byte - short 2 untuk indeks saluran, 256 adalah nilai terurut saluran dalam rentang 0 - 255
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CurvResource(int maxChannelCount)](#CurvResource-int-) | Menginisialisasi instance baru dari kelas [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource). |
| [CurvResource(byte[] bytes)](#CurvResource-byte---) | Menginisialisasi instance baru dari kelas [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Versi header PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Tanda tangan sumber daya khusus PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Versi header PSD |
| [ResourceSignature](#ResourceSignature) | Tanda tangan sumber daya umum. |
| [TypeToolKey](#TypeToolKey) | Kunci informasi alat tipe. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Lisensi usaha. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Memeriksa dan mengatur apakah sumber daya khusus PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveManager()](#getActiveManager--) | Mendapatkan manajer aktif. |
| [getChannelData(int channelIndex)](#getChannelData-int-) | Mendapatkan data saluran. |
| [getClass()](#getClass--) |  |
| [getCurveManager()](#getCurveManager--) | Mendapatkan manajer kurva. |
| [getData()](#getData--) | Mendapatkan atau mengatur data. |
| [getHeader_internalized()](#getHeader-internalized--) | Mendapatkan atau mengatur header. |
| [getKey()](#getKey--) | Mendapatkan kunci sumber daya lapisan. |
| [getLength()](#getLength--) | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Mendapatkan panjang prefiks. |
| [getPsdVersion()](#getPsdVersion--) | Mendapatkan versi PSD minimal yang diperlukan untuk sumber daya lapisan. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya lapisan. |
| [hashCode()](#hashCode--) |  |
| [isDataStoredDiscretely()](#isDataStoredDiscretely--) | Mendapatkan atau menetapkan nilai yang menunjukkan apakah instance ini menyimpan data secara terpisah. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Menentukan apakah sumber daya khusus PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Mendapatkan nilai yang menunjukkan apakah instansi ini adalah sumber daya khusus PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Menyimpan header sumber daya khusus. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Menyimpan tanda tangan header, pengidentifikasi, dan panjang. |
| [setDataStoredDiscretely(boolean value)](#setDataStoredDiscretely-boolean-) | Mendapatkan atau menetapkan nilai yang menunjukkan apakah instance ini menyimpan data secara terpisah. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Mendapatkan atau mengatur header. |
| [toString()](#toString--) | Mengembalikan String yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvResource(int maxChannelCount) {#CurvResource-int-}
```
public CurvResource(int maxChannelCount)
```


Menginisialisasi instance baru dari kelas [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxChannelCount | int | Jumlah saluran maksimum. |

### CurvResource(byte[] bytes) {#CurvResource-byte---}
```
public CurvResource(byte[] bytes)
```


Menginisialisasi instance baru dari kelas [CurvResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvresource).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| byte | byte[] | Byte-byte. |

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Versi header PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Tanda tangan sumber daya khusus PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Versi header PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Tanda tangan sumber daya umum.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Kunci informasi alat tipe.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Lisensi usaha.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Memeriksa dan mengatur apakah sumber daya bersifat khusus PSB. Beberapa sumber daya belum dikenali untuk saat ini, tetapi kami memiliki daftar lengkap sumber daya khusus PSB yang mengubah perilaku mereka saat disimpan. Jadi kami perlu memeriksa ini di UnknownResource setidaknya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | int | Kunci. |

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
### getActiveManager() {#getActiveManager--}
```
public final CurvesManager getActiveManager()
```


Mendapatkan manajer aktif.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - Active manager
### getChannelData(int channelIndex) {#getChannelData-int-}
```
public final byte[] getChannelData(int channelIndex)
```


Mendapatkan data saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| channelIndex | int | Indeks saluran. |

**Returns:**
byte[] - Data saluran
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurveManager() {#getCurveManager--}
```
public final CurvesManager getCurveManager()
```


Mendapatkan manajer kurva.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) or [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager)
### getData() {#getData--}
```
public final byte[] getData()
```


Mendapatkan atau mengatur data.

Nilai: Data.

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Mendapatkan atau mengatur header.

Nilai: Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Mendapatkan kunci sumber daya lapisan.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Mendapatkan panjang sumber daya lapisan dalam byte.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Mendapatkan panjang prefiks. Nilai default adalah 12 untuk sumber daya 8BIM, dan 16 untuk 8B64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| psdVersion | int | Versi PSD. |

**Returns:**
int - Panjang Prefiks.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Mendapatkan tanda tangan sumber daya lapisan.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDataStoredDiscretely() {#isDataStoredDiscretely--}
```
public final boolean isDataStoredDiscretely()
```


Mendapatkan atau menetapkan nilai yang menunjukkan apakah instance ini menyimpan data secara terpisah.

Nilai: true jika instance ini menyimpan data secara terpisah; jika tidak, false.

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Menentukan apakah sumber daya khusus PSB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | int | Kunci sumber daya. |

**Returns:**
boolean -  true  jika sumber daya bersifat khusus PSB; selainnya,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Mendapatkan nilai yang menunjukkan apakah instansi ini adalah sumber daya khusus PSB.

Nilai:  true  jika instance ini adalah sumber daya khusus PSB; selainnya,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psdVersion | int | Versi PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Menyimpan header sumber daya khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |
| tanda tangan | int | Tanda tangan. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Menyimpan tanda tangan header, pengidentifikasi, dan panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |
| tanda tangan | int | Tanda tangan. |
| isLengthLong | boolean | jika diatur ke  true  panjangnya panjang. |

### setDataStoredDiscretely(boolean value) {#setDataStoredDiscretely-boolean-}
```
public final void setDataStoredDiscretely(boolean value)
```


Mendapatkan atau menetapkan nilai yang menunjukkan apakah instance ini menyimpan data secara terpisah.

Nilai: true jika instance ini menyimpan data secara terpisah; jika tidak, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Mendapatkan atau mengatur header.

Nilai: Header.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan String yang mewakili instance ini.

**Returns:**
java.lang.String - String yang mewakili instance ini.
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

