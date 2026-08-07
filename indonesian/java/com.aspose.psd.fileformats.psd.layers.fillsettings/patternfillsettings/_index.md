---
title: "PatternFillSettings"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pengaturan efek isi pola"
type: docs
weight: 20
url: /id/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Pengaturan efek isi pola
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Menginisialisasi instance baru dari kelas [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) class. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Menghasilkan node sumber daya LFX2. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [link with layer]. |
| [getAngle()](#getAngle--) | Mendapatkan atau mengatur sudut. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Mendapatkan atau mengatur warna. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Tipe pengisian |
| [getHorizontalOffset()](#getHorizontalOffset--) | Mendapatkan atau mengatur offset horizontal. |
| [getLinked()](#getLinked--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) ini linked. |
| [getPatternData()](#getPatternData--) | Mendapatkan atau mengatur data pola. |
| [getPatternHeight()](#getPatternHeight--) | Mendapatkan atau mengatur tinggi pola. |
| [getPatternId()](#getPatternId--) | Mendapatkan atau mengatur pengidentifikasi pola. |
| [getPatternName()](#getPatternName--) | Mendapatkan atau mengatur nama pola. |
| [getPatternWidth()](#getPatternWidth--) | Mendapatkan atau mengatur lebar pola. |
| [getPhase_internalized()](#getPhase-internalized--) | Mendapatkan atau mengatur fase. |
| [getPointType()](#getPointType--) | Mendapatkan atau mengatur tipe titik. |
| [getScale()](#getScale--) | Mendapatkan atau mengatur skala. |
| [getVerticalOffset()](#getVerticalOffset--) | Mendapatkan atau mengatur offset vertikal. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Menaikkan nilai yang berubah. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Mendapatkan atau mengatur sudut. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Mendapatkan atau mengatur warna. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Mendapatkan atau mengatur offset horizontal. |
| [setLinked(boolean value)](#setLinked-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) ini linked. |
| [setPatternData(int[] value)](#setPatternData-int---) | Mendapatkan atau mengatur data pola. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Mengatur buffer piksel pola\\u2019s dan mode kompresi yang digunakan saat menyimpan. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Mendapatkan atau mengatur tinggi pola. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Mendapatkan atau mengatur pengidentifikasi pola. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Mendapatkan atau mengatur nama pola. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Mendapatkan atau mengatur lebar pola. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Mendapatkan atau mengatur fase. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Mendapatkan atau mengatur tipe titik. |
| [setScale(double value)](#setScale-double-) | Mendapatkan atau mengatur skala. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Mendapatkan atau mengatur offset vertikal. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Menyiapkan data default pola ke instance [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) instance. |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Memperbarui properti pola dari instance [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Menginisialisasi instance baru dari kelas [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) class.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Menghasilkan node sumber daya LFX2.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pointType | java.lang.String | Tipe titik. |
| color | [Color](../../com.aspose.psd/color) | Warna. |
| patternName | java.lang.String | Nama pola. |
| identifier | java.lang.String | Pengidentifikasi. |
| skala | double | Skala. |
| terhubung | boolean | jika diatur ke  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | Offset. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Daftar [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [link with layer].

Nilai:  true  jika [tautan dengan lapisan]; selainnya,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Mendapatkan atau mengatur sudut.

Nilai: Sudut.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Mendapatkan atau mengatur warna.

Nilai: Warna.

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


Tipe pengisian

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Mendapatkan atau mengatur offset horizontal.

Nilai: Offset horizontal.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) ini linked.

Nilai:  true  jika terhubung; selainnya,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Mendapatkan atau mengatur data pola.

Nilai: Data pola.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Mendapatkan atau mengatur tinggi pola.

Nilai: Tinggi pola.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Mendapatkan atau mengatur pengidentifikasi pola.

Nilai: Pengidentifikasi pola.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Mendapatkan atau mengatur nama pola.

Nilai: Nama pola.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Mendapatkan atau mengatur lebar pola.

Nilai: Lebar pola.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Mendapatkan atau mengatur fase.

Nilai: Fase.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Mendapatkan atau mengatur tipe titik.

Nilai: Tipe titik.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Mendapatkan atau mengatur skala.

Nilai: Skala.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Mendapatkan atau mengatur offset vertikal.

Nilai: Offset vertikal.

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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Menaikkan nilai yang berubah.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [link with layer].

Nilai:  true  jika [tautan dengan lapisan]; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Mendapatkan atau mengatur sudut.

Nilai: Sudut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Mendapatkan atau mengatur warna.

Nilai: Warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Mendapatkan atau mengatur offset horizontal.

Nilai: Offset horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) ini linked.

Nilai:  true  jika terhubung; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Mendapatkan atau mengatur data pola.

Nilai: Data pola.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Mengatur buffer piksel pola\\u2019s dan mode kompresi yang digunakan saat menyimpan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| patternData | int[] | Piksel 32-bit dalam  0xAARRGGBB . |
| compressionModeOnSave | byte | Mode kompresi yang digunakan untuk menentukan kompresi data pola saat menyimpan file psd. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Mendapatkan atau mengatur tinggi pola.

Nilai: Tinggi pola.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Mendapatkan atau mengatur pengidentifikasi pola.

Nilai: Pengidentifikasi pola.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Mendapatkan atau mengatur nama pola.

Nilai: Nama pola.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Mendapatkan atau mengatur lebar pola.

Nilai: Lebar pola.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Mendapatkan atau mengatur fase.

Nilai: Fase.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Mendapatkan atau mengatur tipe titik.

Nilai: Tipe titik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Mendapatkan atau mengatur skala.

Nilai: Skala.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Mendapatkan atau mengatur offset vertikal.

Nilai: Offset vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Menyiapkan data default pola ke instance [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) instance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Pengaturan isian pola. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


Memperbarui properti pola dari instance [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) instance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Instansi [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) dengan data pola. |

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

