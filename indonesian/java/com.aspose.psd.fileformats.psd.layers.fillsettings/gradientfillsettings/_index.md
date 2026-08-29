---
title: "GradientFillSettings"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pengaturan efek isi gradien."
type: docs
weight: 14
url: /id/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Pengaturan efek isi gradien.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Menginisialisasi instance baru dari kelas [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
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
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Mendapatkan atau mengatur batas kontainer lapisan untuk menghitung posisi gradien dengan benar. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Menghitung dan mengembalikan skala gradien **denormalized** (Skala UI) yang sesuai dengan nilai Scale saat ini ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [getDither()](#getDither--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ini dither. |
| [getFillType()](#getFillType--) | Tipe pengisian. |
| [getGradient()](#getGradient--) | Mendapatkan atau mengatur instance definisi gradien spesifik (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Mendapatkan atau mengatur tipe gradien. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Mendapatkan atau mengatur offset horizontal dalam persentase. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Mendapatkan atau mengatur metode interpolasi untuk gradien. |
| [getReverse()](#getReverse--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ini reverse. |
| [getScale()](#getScale--) | Mendapatkan atau mengatur skala gradien **normalized** (dalam persen) |
| [getVerticalOffset()](#getVerticalOffset--) | Mendapatkan atau mengatur offset vertikal dalam persentase. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Menaikkan nilai yang berubah. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Mendapatkan atau mengatur sudut. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Mendapatkan atau mengatur batas kontainer lapisan untuk menghitung posisi gradien dengan benar. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Mengonversi nilai skala (UI) denormalized yang ditentukan ke ekivalen **normalized** dan menetapkannya ke Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ini dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Mendapatkan atau mengatur instance definisi gradien spesifik (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Mendapatkan atau mengatur tipe gradien. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Mendapatkan atau mengatur offset horizontal dalam persentase. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Mendapatkan atau mengatur metode interpolasi untuk gradien. |
| [setReverse(boolean value)](#setReverse-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ini reverse. |
| [setScale(int value)](#setScale-int-) | Mendapatkan atau mengatur skala gradien **normalized** (dalam persen) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Mendapatkan atau mengatur offset vertikal dalam persentase. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Menginisialisasi instance baru dari kelas [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

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
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Mendapatkan atau mengatur batas kontainer lapisan untuk menghitung posisi gradien dengan benar.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Menghitung dan mengembalikan skala gradien **denormalized** (Skala UI) yang sesuai dengan nilai Scale saat ini ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | Batas-batas gradien. |

**Returns:**
int - Skala denormalized (UI) dalam persen seperti yang ditampilkan di Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ini dither.

Nilai:  true  jika dither; lainnya,  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


Tipe pengisian.

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Mendapatkan atau mengatur instance definisi gradien spesifik (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
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
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Mendapatkan atau mengatur metode interpolasi untuk gradien.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ini reverse.

Nilai:  true  jika reverse; lainnya,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Mendapatkan atau mengatur skala gradien **normalized** (dalam persen)

**Returns:**
int
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

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Mendapatkan atau mengatur batas kontainer lapisan untuk menghitung posisi gradien dengan benar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Mengonversi nilai skala (UI) denormalized yang ditentukan ke ekivalen **normalized** dan menetapkannya ke Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). Konversi ini menerapkan Angle gradient\\u2019s saat ini ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) dan fillArea yang diberikan untuk menghitung faktor normalisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Skala denormalized, Skala UI dalam persen seperti yang ditampilkan oleh Photoshop; |
| fillArea | [Size](../../com.aspose.psd/size) | Batas-batas gradien. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ini dither.

Nilai:  true  jika dither; lainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Mendapatkan atau mengatur instance definisi gradien spesifik (Solid/Noise).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

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

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Mendapatkan atau mengatur metode interpolasi untuk gradien.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) ini reverse.

Nilai:  true  jika reverse; lainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Mendapatkan atau mengatur skala gradien **normalized** (dalam persen)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

