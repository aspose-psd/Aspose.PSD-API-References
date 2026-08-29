---
title: "LspfResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pengaturan lapisan yang dilindungi"
type: docs
weight: 57
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LspfResource extends LayerResource
```

Pengaturan lapisan yang dilindungi
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LspfResource(byte[] data)](#LspfResource-byte---) | Menginisialisasi sebuah instance baru dari kelas [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
| [LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)](#LspfResource-boolean-boolean-boolean-) | Menginisialisasi sebuah instance baru dari kelas [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
| [LspfResource()](#LspfResource--) | Menginisialisasi sebuah instance baru dari kelas [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Versi header PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Tanda tangan sumber daya khusus PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Versi header PSD |
| [ResourceSignature](#ResourceSignature) | Tanda tangan sumber daya umum. |
| [TypeToolKey](#TypeToolKey) | Kunci info alat tipe 1819504742 |
| [ventureLicense_internalized](#ventureLicense-internalized) | Lisensi usaha. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Memeriksa dan mengatur apakah sumber daya khusus PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Mendapatkan atau mengatur header. |
| [getKey()](#getKey--) | Mendapatkan kunci sumber daya lapisan. |
| [getLength()](#getLength--) | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [getLockType()](#getLockType--) | Mendapatkan atau mengatur tipe kunci. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Mendapatkan panjang prefiks. |
| [getPsdVersion()](#getPsdVersion--) | Mendapatkan versi PSD minimal yang diperlukan untuk sumber daya lapisan. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya lapisan. |
| [hashCode()](#hashCode--) |  |
| [isCompositeProtected()](#isCompositeProtected--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi secara komposit. |
| [isPositionProtected()](#isPositionProtected--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi posisi. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Menentukan apakah sumber daya khusus PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Mendapatkan nilai yang menunjukkan apakah instansi ini adalah sumber daya khusus PSB. |
| [isTransparencyProtected()](#isTransparencyProtected--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi transparansi. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Menyimpan header sumber daya khusus. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Menyimpan tanda tangan header, pengidentifikasi, dan panjang. |
| [setCompositeProtected(boolean value)](#setCompositeProtected-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi secara komposit. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Mendapatkan atau mengatur header. |
| [setLockType(int value)](#setLockType-int-) | Mendapatkan atau mengatur tipe kunci. |
| [setPositionProtected(boolean value)](#setPositionProtected-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi posisi. |
| [setTransparencyProtected(boolean value)](#setTransparencyProtected-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi transparansi. |
| [toString()](#toString--) | Mengembalikan String yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LspfResource(byte[] data) {#LspfResource-byte---}
```
public LspfResource(byte[] data)
```


Menginisialisasi sebuah instance baru dari kelas [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). Dengan nilai khusus atau tidak diketahui.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data resource. |

### LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected) {#LspfResource-boolean-boolean-boolean-}
```
public LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)
```


Menginisialisasi sebuah instance baru dari kelas [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isTransparencyProtected | boolean | jika diatur ke  true  [is transparency protected]. |
| isCompositeProtected | boolean | jika diatur ke  true  [is composite protected]. |
| isPositionProtected | boolean | jika diatur ke  true  [is position protected]. |

### LspfResource() {#LspfResource--}
```
public LspfResource()
```


Menginisialisasi sebuah instance baru dari kelas [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource).

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


Kunci info alat tipe 1819504742

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getLockType() {#getLockType--}
```
public final int getLockType()
```


Mendapatkan atau mengatur tipe kunci.

Nilai: Tipe kunci.

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
### isCompositeProtected() {#isCompositeProtected--}
```
public final boolean isCompositeProtected()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi secara komposit.

Nilai:  true  jika instance ini dilindungi secara komposit; jika tidak,  false .

**Returns:**
boolean
### isPositionProtected() {#isPositionProtected--}
```
public final boolean isPositionProtected()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi posisi.

Nilai:  true  jika instance ini dilindungi posisi; jika tidak,  false .

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
### isTransparencyProtected() {#isTransparencyProtected--}
```
public final boolean isTransparencyProtected()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi transparansi.

Nilai:  true  jika instance ini dilindungi transparansi; jika tidak,  false .

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

### setCompositeProtected(boolean value) {#setCompositeProtected-boolean-}
```
public final void setCompositeProtected(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi secara komposit.

Nilai:  true  jika instance ini dilindungi secara komposit; jika tidak,  false .

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

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Mendapatkan atau mengatur tipe kunci.

Nilai: Tipe kunci.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPositionProtected(boolean value) {#setPositionProtected-boolean-}
```
public final void setPositionProtected(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi posisi.

Nilai:  true  jika instance ini dilindungi posisi; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setTransparencyProtected(boolean value) {#setTransparencyProtected-boolean-}
```
public final void setTransparencyProtected(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi transparansi.

Nilai:  true  jika instance ini dilindungi transparansi; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

