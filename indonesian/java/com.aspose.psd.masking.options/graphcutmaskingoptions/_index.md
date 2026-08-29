---
title: "GraphCutMaskingOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi masking otomatis GraphCut."
type: docs
weight: 14
url: /id/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

Opsi masking otomatis GraphCut.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Nomor objek latar belakang |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Mendapatkan argumen untuk algoritma segmentasi. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Mendapatkan warna pengganti latar belakang. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Mendapatkan nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang. |
| [getExportOptions()](#getExportOptions--) | Mendapatkan opsi ekspor gambar. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Mendapatkan radius feathering. |
| [getMaskingArea()](#getMaskingArea--) | Mendapatkan area pemaskeran. |
| [getMethod()](#getMethod--) | Mendapatkan metode segmentasi. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Menetapkan argumen untuk algoritma segmentasi. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Menetapkan warna pengganti latar belakang. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Menetapkan nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Menetapkan opsi ekspor gambar. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Mengatur radius feathering. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Menetapkan area pemaskeran. |
| [setMethod(int value)](#setMethod-int-) | Menetapkan metode segmentasi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Nomor objek latar belakang

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Mendapatkan argumen untuk algoritma segmentasi.

Nilai: Argumen untuk algoritma segmentasi.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Mendapatkan warna pengganti latar belakang.

Nilai: Warna pengganti latar belakang. Warna ini akan digunakan sebagai warna latar belakang pada gambar hasil.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Mendapatkan nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang.

Nilai:  true  jika decompose; jika tidak,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Mendapatkan opsi ekspor gambar.

Nilai: Opsi ekspor gambar yang akan digunakan untuk membuat gambar hasil.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Mendapatkan radius feathering.

**Returns:**
int - radius feathering.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Mendapatkan area pemaskeran.

Nilai: Area pemaskeran yang merupakan area parsial dari gambar sumber. Nilai Rectangle.Empty berarti area gambar sumber penuh.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Mendapatkan metode segmentasi.

Nilai: Metode segmentasi.

**Returns:**
int - metode segmentasi.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Menetapkan argumen untuk algoritma segmentasi.

Nilai: Argumen untuk algoritma segmentasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | argumen untuk algoritma segmentasi. |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Menetapkan warna pengganti latar belakang.

Nilai: Warna pengganti latar belakang. Warna ini akan digunakan sebagai warna latar belakang pada gambar hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | warna pengganti latar belakang. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Menetapkan nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang.

Nilai:  true  jika decompose; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari mask sebagai objek individual atau sebagai objek gabungan dari mask yang dipisahkan dari latar belakang. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Menetapkan opsi ekspor gambar.

Nilai: Opsi ekspor gambar yang akan digunakan untuk membuat gambar hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | opsi ekspor gambar. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Mengatur radius feathering.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | radius feathering. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Menetapkan area pemaskeran.

Nilai: Area pemaskeran yang merupakan area parsial dari gambar sumber. Nilai Rectangle.Empty berarti area gambar sumber penuh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | area masking. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Menetapkan metode segmentasi.

Nilai: Metode segmentasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | metode segmentasi. |

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

