---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi masking otomatis GraphCut."
type: docs
weight: 12
url: /id/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Opsi masking otomatis GraphCut.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Menginisialisasi sebuah instance baru dari kelas [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Nomor objek latar belakang |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Tambahkan argumen auto masking. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Isi default stroke. |
| [getArgs()](#getArgs--) | Mendapatkan argumen untuk algoritma segmentasi. |
| [getAssumedObjects()](#getAssumedObjects--) | Mendapatkan objek yang diasumsikan. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Mendapatkan warna pengganti latar belakang. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Mendapatkan nilai yang menunjukkan apakah default stroke harus dihitung. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Mendapatkan persegi panjang objek gabungan. |
| [getDecompose()](#getDecompose--) | Mendapatkan nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Mendapatkan default background stroke. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Mendapatkan default foreground stroke yang telah dihitung sebelumnya. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Mendapatkan persegi panjang objek default. |
| [getExportOptions()](#getExportOptions--) | Mendapatkan opsi ekspor gambar. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Mendapatkan radius feathering. |
| [getMaskingArea()](#getMaskingArea--) | Mendapatkan area pemaskeran. |
| [getMethod()](#getMethod--) | Mendapatkan metode segmentasi. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Mendapatkan penangan acara kemajuan proses pra-perhitungan titik default. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Mendapatkan nilai yang menunjukkan apakah koleksi objek yang diasumsikan memiliki objek manusia di dalamnya. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Menetapkan argumen untuk algoritma segmentasi. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Mengatur objek yang diasumsikan. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Menetapkan warna pengganti latar belakang. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Mengatur nilai yang menunjukkan apakah default stroke harus dihitung. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | Persegi panjang objek gabungan. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Menetapkan nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | Garis latar belakang default. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | Garis latar depan default yang telah dihitung sebelumnya. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | Persegi panjang objek default. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Menetapkan opsi ekspor gambar. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Mengatur radius feathering. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Nilai yang menunjukkan apakah koleksi objek yang diasumsikan memiliki objek manusia di dalamnya. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Menetapkan area pemaskeran. |
| [setMethod(int value)](#setMethod-int-) | Menetapkan metode segmentasi. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mengatur penangan acara kemajuan proses pra-perhitungan titik default. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Menginisialisasi sebuah instance baru dari kelas [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions).

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Nomor objek latar belakang

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Tambahkan argumen auto masking.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Isi default stroke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Mendapatkan argumen untuk algoritma segmentasi.

Nilai: Argumen untuk algoritma segmentasi.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Mendapatkan objek yang diasumsikan.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - objek yang diasumsikan.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Mendapatkan warna pengganti latar belakang.

Nilai: Warna pengganti latar belakang. Warna ini akan digunakan sebagai warna latar belakang pada gambar hasil.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Mendapatkan nilai yang menunjukkan apakah default stroke harus dihitung.

**Returns:**
boolean - nilai yang menunjukkan apakah garis default harus dihitung.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Mendapatkan persegi panjang objek gabungan.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Mendapatkan nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang.

Nilai:  true  jika decompose; jika tidak,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah tidak perlu memisahkan setiap Shape dari masker sebagai objek terpisah atau sebagai objek gabungan dari masker yang dipisahkan dari latar belakang.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Mendapatkan default background stroke.

**Returns:**
com.aspose.psd.Point[] - garis latar belakang default.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Mendapatkan default foreground stroke yang telah dihitung sebelumnya.

**Returns:**
com.aspose.psd.Point[] - garis latar depan default yang telah dihitung sebelumnya.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Mendapatkan persegi panjang objek default.

**Returns:**
com.aspose.psd.Rectangle[] - persegi panjang objek default.
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
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Mendapatkan penangan acara kemajuan proses pra-perhitungan titik default.

Nilai: Penangan peristiwa kemajuan.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Mendapatkan nilai yang menunjukkan apakah koleksi objek yang diasumsikan memiliki objek manusia di dalamnya.

**Returns:**
boolean - nilai yang menunjukkan apakah koleksi objek yang diasumsikan memiliki objek manusia di dalamnya.
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

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Mengatur objek yang diasumsikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | objek yang diasumsikan. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

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

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Mengatur nilai yang menunjukkan apakah default stroke harus dihitung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | nilai yang menunjukkan apakah garis default harus dihitung. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


Persegi panjang objek gabungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | persegi panjang objek gabungan. |

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

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


Garis latar belakang default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | garis latar belakang default. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


Garis latar depan default yang telah dihitung sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | garis latar depan default yang telah dihitung sebelumnya. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


Persegi panjang objek default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | persegi panjang objek default. |

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

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Nilai yang menunjukkan apakah koleksi objek yang diasumsikan memiliki objek manusia di dalamnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | nilai yang menunjukkan apakah koleksi objek yang diasumsikan memiliki objek manusia di dalamnya. |

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

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Mengatur penangan acara kemajuan proses pra-perhitungan titik default.

Nilai: Penangan peristiwa kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | penangan acara kemajuan proses pra-perhitungan titik default. |

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

