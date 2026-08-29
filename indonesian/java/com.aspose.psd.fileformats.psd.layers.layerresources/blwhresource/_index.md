---
title: "BlwhResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas BlwhResource adalah sumber daya dari Lapisan Penyesuaian Hitam Putih."
type: docs
weight: 15
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

Kelas BlwhResource adalah sumber daya dari Lapisan Penyesuaian Hitam Putih.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Menginisialisasi instance baru dari kelas [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource). |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Mendapatkan atau mengatur nama file preset hitam putih. |
| [getBlues()](#getBlues--) | Mendapatkan atau mengatur nilai biru. |
| [getBwPresetKind()](#getBwPresetKind--) | Mendapatkan atau mengatur nilai jenis preset hitam putih. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Mendapatkan atau mengatur nilai sian. |
| [getData()](#getData--) | Mendapatkan atau mengatur data. |
| [getGreens()](#getGreens--) | Mendapatkan atau mengatur nilai hijau. |
| [getHeader_internalized()](#getHeader-internalized--) | Mendapatkan atau mengatur header. |
| [getKey()](#getKey--) | Mendapatkan kunci sumber daya lapisan. |
| [getLength()](#getLength--) | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [getMagentas()](#getMagentas--) | Mendapatkan atau mengatur nilai magenta. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Mendapatkan panjang prefiks. |
| [getPsdVersion()](#getPsdVersion--) | Mendapatkan versi PSD minimal yang diperlukan untuk sumber daya lapisan. |
| [getReds()](#getReds--) | Mendapatkan atau mengatur nilai merah. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya lapisan. |
| [getTintColor()](#getTintColor--) | Mendapatkan warna tint ARGB. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Mendapatkan atau mengatur nilai ganda Warna Tint Biru. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Mendapatkan atau mengatur nilai ganda Warna Tint Hijau. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Mendapatkan atau mengatur nilai ganda Warna Tint Merah. |
| [getUseTint()](#getUseTint--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [tint color] digunakan. |
| [getYellows()](#getYellows--) | Mendapatkan atau mengatur nilai kuning. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Menentukan apakah sumber daya khusus PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Mendapatkan nilai yang menunjukkan apakah instansi ini adalah sumber daya khusus PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Menyimpan header sumber daya khusus. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Menyimpan tanda tangan header, pengidentifikasi, dan panjang. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Mendapatkan atau mengatur nama file preset hitam putih. |
| [setBlues(int value)](#setBlues-int-) | Mendapatkan atau mengatur nilai biru. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Mendapatkan atau mengatur nilai jenis preset hitam putih. |
| [setCyans(int value)](#setCyans-int-) | Mendapatkan atau mengatur nilai sian. |
| [setGreens(int value)](#setGreens-int-) | Mendapatkan atau mengatur nilai hijau. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Mendapatkan atau mengatur header. |
| [setMagentas(int value)](#setMagentas-int-) | Mendapatkan atau mengatur nilai magenta. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Mengatur nilai properti berdasarkan struktur tipe. |
| [setReds(int value)](#setReds-int-) | Mendapatkan atau mengatur nilai merah. |
| [setTintColor(int value)](#setTintColor-int-) | Mengatur warna tint. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Mendapatkan atau mengatur nilai ganda Warna Tint Biru. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Mendapatkan atau mengatur nilai ganda Warna Tint Hijau. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Mendapatkan atau mengatur nilai ganda Warna Tint Merah. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [tint color] digunakan. |
| [setYellows(int value)](#setYellows-int-) | Mendapatkan atau mengatur nilai kuning. |
| [toString()](#toString--) | Mengembalikan String yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Menginisialisasi instance baru dari kelas [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource).

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Mendapatkan atau mengatur nama file preset hitam putih.

Nilai: Nama file preset hitam putih.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Mendapatkan atau mengatur nilai biru.

Nilai: Nilai biru.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Mendapatkan atau mengatur nilai jenis preset hitam putih.

Nilai: Nilai jenis preset hitam putih.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


Mendapatkan atau mengatur nilai sian.

Nilai: Nilai sian.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Mendapatkan atau mengatur data.

Nilai: Data.

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Mendapatkan atau mengatur nilai hijau.

Nilai: Nilai hijau.

**Returns:**
int
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
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Mendapatkan atau mengatur nilai magenta.

Nilai: Nilai magenta.

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
### getReds() {#getReds--}
```
public final int getReds()
```


Mendapatkan atau mengatur nilai merah.

Nilai: Nilai merah.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Mendapatkan tanda tangan sumber daya lapisan.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


Mendapatkan warna tint ARGB.

**Returns:**
int - Warna tint ARGB.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Mendapatkan atau mengatur nilai ganda Warna Tint Biru.

Nilai: Nilai ganda Warna Tint Biru.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Mendapatkan atau mengatur nilai ganda Warna Tint Hijau.

Nilai: Nilai double Warna Hijau Tint.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Mendapatkan atau mengatur nilai ganda Warna Tint Merah.

Nilai: Nilai double Warna Merah Tint.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [tint color] digunakan.

Nilai: true jika digunakan [tint color]; sebaliknya, false.

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Mendapatkan atau mengatur nilai kuning.

Nilai: nilai kuning.

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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Mendapatkan atau mengatur nama file preset hitam putih.

Nilai: Nama file preset hitam putih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Mendapatkan atau mengatur nilai biru.

Nilai: Nilai biru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Mendapatkan atau mengatur nilai jenis preset hitam putih.

Nilai: Nilai jenis preset hitam putih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Mendapatkan atau mengatur nilai sian.

Nilai: Nilai sian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Mendapatkan atau mengatur nilai hijau.

Nilai: Nilai hijau.

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Mendapatkan atau mengatur nilai magenta.

Nilai: Nilai magenta.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Mengatur nilai properti berdasarkan struktur tipe.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Struktur. |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Mendapatkan atau mengatur nilai merah.

Nilai: Nilai merah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Mengatur warna tint.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Mendapatkan atau mengatur nilai ganda Warna Tint Biru.

Nilai: Nilai ganda Warna Tint Biru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Mendapatkan atau mengatur nilai ganda Warna Tint Hijau.

Nilai: Nilai double Warna Hijau Tint.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Mendapatkan atau mengatur nilai ganda Warna Tint Merah.

Nilai: Nilai double Warna Merah Tint.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [tint color] digunakan.

Nilai: true jika digunakan [tint color]; sebaliknya, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Mendapatkan atau mengatur nilai kuning.

Nilai: nilai kuning.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

