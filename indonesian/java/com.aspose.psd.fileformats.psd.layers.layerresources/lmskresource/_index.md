---
title: "LmskResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Sumber daya LMsk."
type: docs
weight: 50
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LmskResource extends LayerResource
```

Sumber daya LMsk.

--------------------

Sumber daya ini berisi ID ruang warna, yang mengacu pada jenis ruang warna tertentu, dan 4 komponen warna. Bergantung pada ID, komponen warna memiliki arti yang berbeda. Jika jenis ruang warna tidak memerlukan empat nilai, komponen tambahan tidak terdefinisi dan selalu ditulis sebagai nol. Komponen warna berdasarkan jenis ruang warna: RGB - tiga komponen pertama adalah merah, hijau, dan biru. HSB - tiga komponen pertama adalah hue, saturasi, dan kecerahan. CMYK - empat komponen adalah cyan, magenta, kuning, dan hitam. Lab - tiga komponen pertama adalah kecerahan, a krominansi, dan b krominansi. Grayscale - komponen pertama adalah nilai abu-abu, dari 0...10000.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LmskResource()](#LmskResource--) | Menginisialisasi instance baru dari kelas [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource). |
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
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorComponent1()](#getColorComponent1--) | Mendapatkan komponen warna 1. |
| [getColorComponent2()](#getColorComponent2--) | Mendapatkan komponen warna 2. |
| [getColorComponent3()](#getColorComponent3--) | Mendapatkan komponen warna 3. |
| [getColorComponent4()](#getColorComponent4--) | Mendapatkan komponen warna 4. |
| [getColorSpace()](#getColorSpace--) | Mendapatkan ruang warna. |
| [getFlag()](#getFlag--) | Mendapatkan flag. |
| [getHeader_internalized()](#getHeader-internalized--) | Mendapatkan atau mengatur header. |
| [getKey()](#getKey--) | Mendapatkan kunci sumber daya lapisan. |
| [getLength()](#getLength--) | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [getOpacity()](#getOpacity--) | Mendapatkan opasitas. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Mendapatkan panjang prefiks. |
| [getPsdVersion()](#getPsdVersion--) | Mendapatkan versi PSD minimal yang diperlukan untuk sumber daya lapisan. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya lapisan. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Menentukan apakah sumber daya khusus PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Mendapatkan nilai yang menunjukkan apakah instansi ini adalah sumber daya khusus PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Menyimpan header sumber daya khusus. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Menyimpan tanda tangan header, pengidentifikasi, dan panjang. |
| [setColorComponent1(int value)](#setColorComponent1-int-) | Mendapatkan komponen warna 1. |
| [setColorComponent2(int value)](#setColorComponent2-int-) | Mendapatkan komponen warna 2. |
| [setColorComponent3(int value)](#setColorComponent3-int-) | Mendapatkan komponen warna 3. |
| [setColorComponent4(int value)](#setColorComponent4-int-) | Mendapatkan komponen warna 4. |
| [setColorSpace(int value)](#setColorSpace-int-) | Mendapatkan ruang warna. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Mendapatkan atau mengatur header. |
| [setOpacity(short value)](#setOpacity-short-) | Mendapatkan opasitas. |
| [toString()](#toString--) | Mengembalikan String yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LmskResource() {#LmskResource--}
```
public LmskResource()
```


Menginisialisasi instance baru dari kelas [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource).

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static LmskResource create_internalized(byte[] data)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] |  |

**Returns:**
[LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponent1() {#getColorComponent1--}
```
public final int getColorComponent1()
```


Mendapatkan komponen warna 1.

Nilai: komponen warna 1.

**Returns:**
int
### getColorComponent2() {#getColorComponent2--}
```
public final int getColorComponent2()
```


Mendapatkan komponen warna 2.

Nilai: komponen warna 2.

**Returns:**
int
### getColorComponent3() {#getColorComponent3--}
```
public final int getColorComponent3()
```


Mendapatkan komponen warna 3.

Nilai: komponen warna 3.

**Returns:**
int
### getColorComponent4() {#getColorComponent4--}
```
public final int getColorComponent4()
```


Mendapatkan komponen warna 4.

Nilai: komponen warna 4.

**Returns:**
int
### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


Mendapatkan ruang warna.

Nilai: Ruang warna.

**Returns:**
int
### getFlag() {#getFlag--}
```
public final byte getFlag()
```


Mendapatkan flag.

Nilai: flag.

**Returns:**
byte
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
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


Mendapatkan opasitas.

Nilai: Opacity.

**Returns:**
short
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

### setColorComponent1(int value) {#setColorComponent1-int-}
```
public final void setColorComponent1(int value)
```


Mendapatkan komponen warna 1.

Nilai: komponen warna 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColorComponent2(int value) {#setColorComponent2-int-}
```
public final void setColorComponent2(int value)
```


Mendapatkan komponen warna 2.

Nilai: komponen warna 2.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColorComponent3(int value) {#setColorComponent3-int-}
```
public final void setColorComponent3(int value)
```


Mendapatkan komponen warna 3.

Nilai: komponen warna 3.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColorComponent4(int value) {#setColorComponent4-int-}
```
public final void setColorComponent4(int value)
```


Mendapatkan komponen warna 4.

Nilai: komponen warna 4.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```


Mendapatkan ruang warna.

Nilai: Ruang warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


Mendapatkan opasitas.

Nilai: Opacity.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

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

