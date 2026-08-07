---
title: "GridAndGuidesResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili sumber daya kisi dan panduan."
type: docs
weight: 20
url: /id/java/com.aspose.psd.fileformats.psd.resources/gridandguidesresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class GridAndGuidesResource extends ResourceBlock
```

Mewakili sumber daya kisi dan panduan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GridAndGuidesResource()](#GridAndGuidesResource--) | Menginisialisasi sebuah instance baru dari kelas [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Tanda tangan sumber daya ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Tanda tangan sumber daya Photoshop standar. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Mendapatkan ukuran data sumber daya dalam byte. |
| [getGridCycleX()](#getGridCycleX--) | Mendapatkan atau mengatur siklus grid horizontal. |
| [getGridCycleY()](#getGridCycleY--) | Mendapatkan atau mengatur siklus grid vertikal. |
| [getGuideCount()](#getGuideCount--) | Mendapatkan jumlah blok sumber daya panduan. |
| [getGuides()](#getGuides--) | Mendapatkan atau mengatur panduan. |
| [getHeaderVersion()](#getHeaderVersion--) | Mendapatkan atau mengatur versi header. |
| [getID()](#getID--) | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| [getMinimalVersion()](#getMinimalVersion--) | Mendapatkan versi PSD minimal yang diperlukan. |
| [getName()](#getName--) | Mendapatkan atau mengatur nama sumber daya. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya. |
| [getSize()](#getSize--) | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| [setGridCycleX(int value)](#setGridCycleX-int-) | Mendapatkan atau mengatur siklus grid horizontal. |
| [setGridCycleY(int value)](#setGridCycleY-int-) | Mendapatkan atau mengatur siklus grid vertikal. |
| [setGuides(GuideResource[] value)](#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---) | Mendapatkan atau mengatur panduan. |
| [setHeaderVersion(int value)](#setHeaderVersion-int-) | Mendapatkan atau mengatur versi header. |
| [setID(short value)](#setID-short-) | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Mendapatkan atau mengatur informasi layer dan mask. |
| [setName(String value)](#setName-java.lang.String-) | Mendapatkan atau mengatur nama sumber daya. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Mendapatkan atau mengatur status blok sumber daya. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Memvalidasi nilai sumber daya. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GridAndGuidesResource() {#GridAndGuidesResource--}
```
public GridAndGuidesResource()
```


Menginisialisasi sebuah instance baru dari kelas [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Tanda tangan sumber daya ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Tanda tangan sumber daya Photoshop standar.

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Mendapatkan ukuran data sumber daya dalam byte.

Nilai: Ukuran data sumber daya.

**Returns:**
int
### getGridCycleX() {#getGridCycleX--}
```
public final int getGridCycleX()
```


Mendapatkan atau mengatur siklus grid horizontal. Nilai default adalah 576.

Nilai: Siklus grid horizontal.

**Returns:**
int
### getGridCycleY() {#getGridCycleY--}
```
public final int getGridCycleY()
```


Mendapatkan atau mengatur siklus grid vertikal. Nilai default adalah 576.

Nilai: Siklus grid vertikal.

**Returns:**
int
### getGuideCount() {#getGuideCount--}
```
public final int getGuideCount()
```


Mendapatkan jumlah blok sumber daya panduan.

Nilai: Jumlah blok sumber daya panduan.

**Returns:**
int
### getGuides() {#getGuides--}
```
public final GuideResource[] getGuides()
```


Mendapatkan atau mengatur panduan.

Nilai: Panduan.

**Returns:**
com.aspose.psd.fileformats.psd.resources.GuideResource[]
### getHeaderVersion() {#getHeaderVersion--}
```
public final int getHeaderVersion()
```


Mendapatkan atau mengatur versi header. Nilai ini harus selalu 1.

Nilai: Versi header.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya.

Nilai: Pengidentifikasi unik untuk sumber daya.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Mendapatkan versi PSD minimal yang diperlukan.

Nilai: Versi psd minimal.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0).

Nilai: Nama sumber daya.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Mendapatkan tanda tangan sumber daya. Harus selalu '8BIM'.

Nilai: Tanda tangan sumber daya.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya.

Nilai: Ukuran blok sumber daya.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Menyimpan blok sumber daya ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Aliran untuk menyimpan blok sumber daya. |

### setGridCycleX(int value) {#setGridCycleX-int-}
```
public final void setGridCycleX(int value)
```


Mendapatkan atau mengatur siklus grid horizontal. Nilai default adalah 576.

Nilai: Siklus grid horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGridCycleY(int value) {#setGridCycleY-int-}
```
public final void setGridCycleY(int value)
```


Mendapatkan atau mengatur siklus grid vertikal. Nilai default adalah 576.

Nilai: Siklus grid vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGuides(GuideResource[] value) {#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---}
```
public final void setGuides(GuideResource[] value)
```


Mendapatkan atau mengatur panduan.

Nilai: Panduan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [GuideResource\[\]](../../com.aspose.psd.fileformats.psd.resources/guideresource) |  |

### setHeaderVersion(int value) {#setHeaderVersion-int-}
```
public final void setHeaderVersion(int value)
```


Mendapatkan atau mengatur versi header. Nilai ini harus selalu 1.

Nilai: Versi header.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya.

Nilai: Pengidentifikasi unik untuk sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Mendapatkan atau mengatur informasi layer dan mask.

Nilai: Informasi lapisan dan masker.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0).

Nilai: Nama sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tanda tangan | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Mendapatkan atau mengatur status blok sumber daya.

Nilai: Status blok sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Memvalidasi nilai sumber daya.

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

