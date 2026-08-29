---
title: "VstkResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas sumber VstkResource."
type: docs
weight: 14
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

Kelas sumber daya VstkResource. Berisi informasi tentang Data Stroke Vektor. Sumber daya harus diinisialisasi baik melalui metode AssignItems dari resourcedata, atau dengan menetapkan nilai ke properti kelas.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VstkResource()](#VstkResource--) | Menginisialisasi sebuah instance baru dari kelas [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource). |
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
| [assignItems_internalized(OSTypeStructure[] items)](#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Menetapkan struktur item dari sumber daya Vstk. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Memeriksa dan mengatur apakah sumber daya khusus PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Mendapatkan atau mengatur instance ClassID. |
| [getClassName_internalized()](#getClassName-internalized--) | Mendapatkan atau mengatur nama kelas. |
| [getFillEnabled()](#getFillEnabled--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah isi Stroke diaktifkan. |
| [getFillSettings()](#getFillSettings--) | Mendapatkan atau mengatur pengaturan Isi dari Stroke. |
| [getHeader_internalized()](#getHeader-internalized--) | Mendapatkan atau mengatur header. |
| [getKey()](#getKey--) | Mendapatkan kunci sumber daya lapisan. |
| [getLength()](#getLength--) | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Mendapatkan panjang prefiks. |
| [getPsdVersion()](#getPsdVersion--) | Mendapatkan versi PSD minimal yang diperlukan untuk sumber daya lapisan. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya lapisan. |
| [getStrokeEnabled()](#getStrokeEnabled--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah efek stroke diaktifkan. |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | Mendapatkan atau mengatur mode Stroke Blend. |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | Mendapatkan atau mengatur entitas Stroke. |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | Mendapatkan atau mengatur perataan garis gaya Stroke. |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | Mendapatkan atau mengatur tipe stroke style line cap. |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | Mendapatkan atau mengatur lebar penutup garis Stroke. |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | Mendapatkan atau mengatur offset dash garis gaya stroke. |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | Mendapatkan atau mengatur array garis putus-putus. |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | Mendapatkan atau mengatur tipe sambungan garis gaya Stroke. |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | Mendapatkan atau mengatur lebar garis Stroke. |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | Mendapatkan atau mengatur batas miter gaya stroke. |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | Mendapatkan atau mengatur opasitas gaya Stroke (0-100%). |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | Mendapatkan atau mengatur resolusi gaya Stroke. |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | Mendapatkan atau mengatur kunci skala gaya Stroke. |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | Mendapatkan atau mengatur penyesuaian Stroke. |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | Mendapatkan atau mengatur versi gaya stroke. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Menentukan apakah sumber daya khusus PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Mendapatkan nilai yang menunjukkan apakah instansi ini adalah sumber daya khusus PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Menyimpan header sumber daya khusus. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Menyimpan tanda tangan header, pengidentifikasi, dan panjang. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Mendapatkan atau mengatur instance ClassID. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Mendapatkan atau mengatur nama kelas. |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah isi Stroke diaktifkan. |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Mendapatkan atau mengatur pengaturan Isi dari Stroke. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Mendapatkan atau mengatur header. |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah efek stroke diaktifkan. |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | Mendapatkan atau mengatur mode Stroke Blend. |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | Mendapatkan atau mengatur entitas Stroke. |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | Mendapatkan atau mengatur perataan garis gaya Stroke. |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | Mendapatkan atau mengatur tipe stroke style line cap. |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | Mendapatkan atau mengatur lebar penutup garis Stroke. |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | Mendapatkan atau mengatur offset dash garis gaya stroke. |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | Mendapatkan atau mengatur array garis putus-putus. |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | Mendapatkan atau mengatur tipe sambungan garis gaya Stroke. |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | Mendapatkan atau mengatur lebar garis Stroke. |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | Mendapatkan atau mengatur batas miter gaya stroke. |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | Mendapatkan atau mengatur opasitas Stroke stryle (0-100%). |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | Mendapatkan atau mengatur resolusi gaya Stroke. |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | Mendapatkan atau mengatur kunci skala gaya Stroke. |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | Mendapatkan atau mengatur penyesuaian Stroke. |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | Mendapatkan atau mengatur versi gaya stroke. |
| [toString()](#toString--) | Mengembalikan String yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


Menginisialisasi sebuah instance baru dari kelas [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource).

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

### assignItems_internalized(OSTypeStructure[] items) {#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void assignItems_internalized(OSTypeStructure[] items)
```


Menetapkan struktur item dari sumber daya Vstk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| items | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Daftar instance OSTypeStructure. |

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
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Mendapatkan atau mengatur instance ClassID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Mendapatkan atau mengatur nama kelas.

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah isi Stroke diaktifkan.

**Returns:**
boolean
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


Mendapatkan atau mengatur pengaturan Isi dari Stroke.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
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
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah efek stroke diaktifkan.

**Returns:**
boolean
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


Mendapatkan atau mengatur mode Stroke Blend.

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


Mendapatkan atau mengatur entitas Stroke. Properti menentukan pengaturan isi dari stroke.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


Mendapatkan atau mengatur perataan garis gaya Stroke.

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


Mendapatkan atau mengatur tipe stroke style line cap.

Nilai: Tipe stroke style line cap.

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


Mendapatkan atau mengatur lebar penutup garis Stroke.

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


Mendapatkan atau mengatur offset dash garis gaya stroke.

Nilai: Offset dash garis gaya stroke.

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


Mendapatkan atau mengatur array garis putus-putus.

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


Mendapatkan atau mengatur tipe sambungan garis gaya Stroke.

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


Mendapatkan atau mengatur lebar garis Stroke.

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


Mendapatkan atau mengatur batas miter gaya stroke.

Nilai: Batas miter gaya stroke.

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


Mendapatkan atau mengatur opasitas gaya Stroke (0-100%).

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


Mendapatkan atau mengatur resolusi gaya Stroke.

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


Mendapatkan atau mengatur kunci skala gaya Stroke.

**Returns:**
boolean
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


Mendapatkan atau mengatur penyesuaian Stroke.

**Returns:**
boolean
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


Mendapatkan atau mengatur versi gaya stroke.

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Mendapatkan atau mengatur instance ClassID.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Mendapatkan atau mengatur nama kelas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah isi Stroke diaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


Mendapatkan atau mengatur pengaturan Isi dari Stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah efek stroke diaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


Mendapatkan atau mengatur mode Stroke Blend.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


Mendapatkan atau mengatur entitas Stroke. Properti menentukan pengaturan isi dari stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


Mendapatkan atau mengatur perataan garis gaya Stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


Mendapatkan atau mengatur tipe stroke style line cap.

Nilai: Tipe stroke style line cap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


Mendapatkan atau mengatur lebar penutup garis Stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


Mendapatkan atau mengatur offset dash garis gaya stroke.

Nilai: Offset dash garis gaya stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


Mendapatkan atau mengatur array garis putus-putus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


Mendapatkan atau mengatur tipe sambungan garis gaya Stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


Mendapatkan atau mengatur lebar garis Stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


Mendapatkan atau mengatur batas miter gaya stroke.

Nilai: Batas miter gaya stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


Mendapatkan atau mengatur opasitas Stroke stryle (0-100%).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


Mendapatkan atau mengatur resolusi gaya Stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


Mendapatkan atau mengatur kunci skala gaya Stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


Mendapatkan atau mengatur penyesuaian Stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


Mendapatkan atau mengatur versi gaya stroke.

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

