---
title: "NoiseGradientFillSettings"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas definisi gradien noise."
type: docs
weight: 18
url: /id/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Kelas definisi gradien noise.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Menginisialisasi instance baru dari kelas [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [align with layer]. |
| [getAngle()](#getAngle--) | Mendapatkan atau mengatur sudut. |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Mendapatkan atau mengatur Model Warna - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither. |
| [getExpansionCount()](#getExpansionCount--) | Mendapatkan atau mengatur jumlah Ekspansi ( = 2 untuk Photoshop 6.0). |
| [getFillType()](#getFillType--) | Tipe pengisian. |
| [getGradientMode()](#getGradientMode--) | Mendapatkan mode untuk gradien ini. |
| [getGradientName()](#getGradientName--) | Mendapatkan atau mengatur nama gradien. |
| [getGradientType()](#getGradientType--) | Mendapatkan atau mengatur tipe gradien. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Mendapatkan atau mengatur offset horizontal dalam persentase. |
| [getMaximumColor()](#getMaximumColor--) | Mendapatkan atau mengatur warna Maksimum dari PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Mendapatkan atau mengatur warna Minimum dari PixelDataFormat. |
| [getReverse()](#getReverse--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) terbalik. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Mendapatkan atau mengatur benih angka acak yang digunakan untuk menghasilkan warna untuk gradien Noise |
| [getRoughness()](#getRoughness--) | Mendapatkan atau mengatur faktor Kekasaran. |
| [getScale()](#getScale--) | Mendapatkan atau mengatur skala. |
| [getShowTransparency()](#getShowTransparency--) | Mendapatkan atau mengatur flag untuk menampilkan transparansi. |
| [getUseVectorColor()](#getUseVectorColor--) | Mendapatkan atau mengatur flag untuk menggunakan warna vektor. |
| [getVerticalOffset()](#getVerticalOffset--) | Mendapatkan atau mengatur offset vertikal dalam persentase. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Menaikkan nilai yang berubah. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Mendapatkan atau mengatur sudut. |
| [setColorModel(short value)](#setColorModel-short-) | Mendapatkan atau mengatur Model Warna - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Mendapatkan atau mengatur jumlah Ekspansi ( = 2 untuk Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Mendapatkan mode untuk gradien ini. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Mendapatkan atau mengatur nama gradien. |
| [setGradientType(int value)](#setGradientType-int-) | Mendapatkan atau mengatur tipe gradien. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Mendapatkan atau mengatur offset horizontal dalam persentase. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Mendapatkan atau mengatur warna Maksimum dari PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Mendapatkan atau mengatur warna Minimum dari PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) terbalik. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Mendapatkan atau mengatur benih angka acak yang digunakan untuk menghasilkan warna untuk gradien Noise |
| [setRoughness(int value)](#setRoughness-int-) | Mendapatkan atau mengatur faktor Kekasaran. |
| [setScale(int value)](#setScale-int-) | Mendapatkan atau mengatur skala. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Mendapatkan atau mengatur flag untuk menampilkan transparansi. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Mendapatkan atau mengatur flag untuk menggunakan warna vektor. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Mendapatkan atau mengatur offset vertikal dalam persentase. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Menginisialisasi instance baru dari kelas [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings).

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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [align with layer].

Nilai:  true  jika [align with layer]; sebaliknya,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Mendapatkan atau mengatur sudut.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Mendapatkan atau mengatur Model Warna - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither.

Nilai:  true  jika dither; lainnya,  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Mendapatkan atau mengatur jumlah Ekspansi ( = 2 untuk Photoshop 6.0).

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


Tipe pengisian.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Mendapatkan mode untuk gradien ini. Menentukan 'Tipe Gradien' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Mendapatkan atau mengatur nama gradien.

Nilai: Nama gradien.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Mendapatkan atau mengatur tipe gradien.

Nilai: Tipe gradien.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Mendapatkan atau mengatur offset horizontal dalam persentase.

Nilai: Offset horizontal.

**Returns:**
double
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Mendapatkan atau mengatur warna Maksimum dari PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Mendapatkan atau mengatur warna Minimum dari PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) terbalik.

Nilai:  true  jika reverse; lainnya,  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Mendapatkan atau mengatur benih angka acak yang digunakan untuk menghasilkan warna untuk gradien Noise

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Mendapatkan atau mengatur faktor Kekasaran.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Mendapatkan atau mengatur skala.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Mendapatkan atau mengatur flag untuk menampilkan transparansi.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Mendapatkan atau mengatur flag untuk menggunakan warna vektor.

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Mendapatkan atau mengatur offset vertikal dalam persentase.

Nilai: Offset vertikal.

**Returns:**
double
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


Mendapatkan atau mengatur nilai yang menunjukkan apakah [align with layer].

Nilai:  true  jika [align with layer]; sebaliknya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Mendapatkan atau mengatur sudut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Mendapatkan atau mengatur Model Warna - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither.

Nilai:  true  jika dither; lainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Mendapatkan atau mengatur jumlah Ekspansi ( = 2 untuk Photoshop 6.0).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Mendapatkan mode untuk gradien ini. Menentukan 'Tipe Gradien' = 'Solid/Noise' (0/1).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Mendapatkan atau mengatur nama gradien.

Nilai: Nama gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Mendapatkan atau mengatur tipe gradien.

Nilai: Tipe gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Mendapatkan atau mengatur offset horizontal dalam persentase.

Nilai: Offset horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Mendapatkan atau mengatur warna Maksimum dari PixelDataFormat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Mendapatkan atau mengatur warna Minimum dari PixelDataFormat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) terbalik.

Nilai:  true  jika reverse; lainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Mendapatkan atau mengatur benih angka acak yang digunakan untuk menghasilkan warna untuk gradien Noise

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Mendapatkan atau mengatur faktor Kekasaran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Mendapatkan atau mengatur skala.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Mendapatkan atau mengatur flag untuk menampilkan transparansi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Mendapatkan atau mengatur flag untuk menggunakan warna vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Mendapatkan atau mengatur offset vertikal dalam persentase.

Nilai: Offset vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

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

