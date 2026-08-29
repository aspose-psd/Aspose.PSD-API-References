---
title: "PngOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi pembuatan format file png."
type: docs
weight: 19
url: /id/java/com.aspose.psd.imageoptions/pngoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Opsi pembuatan format file png.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PngOptions()](#PngOptions--) | Menginisialisasi instance baru dari kelas  PngOptions . |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.psd.imageoptions.PngOptions-) | Menginisialisasi instance baru dari kelas  JpegOptions  class. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Level kompresi default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Mengkloning instance ini. |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Mendapatkan kedalaman bit. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Mendapatkan atau mengatur tipe warna. |
| [getCompressionLevel()](#getCompressionLevel--) | Level kompresi gambar png dalam rentang 0-9, di mana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getFilterType()](#getFilterType--) | Mendapatkan atau mengatur tipe filter yang digunakan selama proses penyimpanan file png. |
| [getFullFrame()](#getFullFrame--) | Mendapatkan nilai yang menunjukkan apakah [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Opsi multipage |
| [getPalette()](#getPalette--) | Mendapatkan atau mengatur palet warna. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [getProgressive()](#getProgressive--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah  PngOptions  bersifat progresif. |
| [getResolutionSettings()](#getResolutionSettings--) | Mendapatkan atau mengatur pengaturan resolusi. |
| [getSource()](#getSource--) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [getXmpData()](#getXmpData--) | Mendapatkan atau mengatur kontainer metadata XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Mengatur kedalaman bit. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setColorType(int value)](#setColorType-int-) | Mendapatkan atau mengatur tipe warna. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Level kompresi gambar png dalam rentang 0-9, di mana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [setFilterType(int value)](#setFilterType-int-) | Mendapatkan atau mengatur tipe filter yang digunakan selama proses penyimpanan file png. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Mengatur nilai yang menunjukkan apakah [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Opsi multipage |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Mendapatkan atau mengatur palet warna. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah  PngOptions  bersifat progresif. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Mendapatkan atau mengatur pengaturan resolusi. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Mendapatkan atau mengatur kontainer metadata XMP. |
| [toString()](#toString--) |  |
| [validate_internalized()](#validate-internalized--) | Rutinitas validasi opsi. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Menginisialisasi instance baru dari kelas  PngOptions .

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.psd.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Menginisialisasi instance baru dari kelas  JpegOptions  class.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.psd.imageoptions/pngoptions) | Opsi PNG. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Level kompresi default.

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. Metode ini hanya memanggil metode dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Mengkloning instance ini.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Mengkloning instance ini.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance saat ini.

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
### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Mendapatkan kedalaman bit.

**Returns:**
byte - Kedalaman bit.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal.

Nilai: Petunjuk ukuran buffer, dalam megabyte. Nilai non-positif berarti tidak ada batas memori untuk buffer internal

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Mendapatkan atau mengatur tipe warna.

**Returns:**
int - Tipe warna.
### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


Level kompresi gambar png dalam rentang 0-9, di mana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan.

**Returns:**
int - level kompresi dalam rentang 0-9, di mana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Nilai: Font pengganti default.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Mendapatkan atau mengatur tipe filter yang digunakan selama proses penyimpanan file png.

**Returns:**
int - tipe filter yang digunakan selama proses penyimpanan file png.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Mendapatkan nilai yang menunjukkan apakah [full frame].

Nilai:  true  jika [full frame]; selainnya,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan.

Nilai:  true  jika mengabaikan setelah peristiwa pembuatan; selainnya,  false .

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Opsi multipage

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Mendapatkan atau mengatur palet warna.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Mendapatkan atau mengatur penangan peristiwa kemajuan.

Nilai: Penangan peristiwa kemajuan.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah  PngOptions  bersifat progresif.

**Returns:**
boolean -  true  jika progresif; jika tidak,  false .
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Mendapatkan atau mengatur pengaturan resolusi.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


Mendapatkan atau mengatur sumber untuk membuat gambar.

Nilai: Sumber untuk membuat gambar.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Mendapatkan atau mengatur opsi rasterisasi vektor.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Mendapatkan atau mengatur kontainer metadata XMP.

Nilai: Kontainer data XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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




### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Mengatur kedalaman bit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte | Kedalaman bit |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal.

Nilai: Petunjuk ukuran buffer, dalam megabyte. Nilai non-positif berarti tidak ada batas memori untuk buffer internal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Mendapatkan atau mengatur tipe warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Tipe warna. |

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


Level kompresi gambar png dalam rentang 0-9, di mana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | tingkat kompresi dalam rentang 0-9, dimana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Nilai: Font pengganti default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Mendapatkan atau mengatur tipe filter yang digunakan selama proses penyimpanan file png.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | tipe filter yang digunakan selama proses penyimpanan file png. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Mengatur nilai yang menunjukkan apakah [full frame].

Nilai:  true  jika [full frame]; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | nilai yang menunjukkan apakah [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan.

Nilai:  true  jika mengabaikan setelah peristiwa pembuatan; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Opsi multipage

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Mendapatkan atau mengatur palet warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Mendapatkan atau mengatur penangan peristiwa kemajuan.

Nilai: Penangan peristiwa kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah  PngOptions  bersifat progresif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika progresif; jika tidak,  false . |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Mendapatkan atau mengatur pengaturan resolusi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Mendapatkan atau mengatur sumber untuk membuat gambar.

Nilai: Sumber untuk membuat gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Mendapatkan atau mengatur opsi rasterisasi vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Mendapatkan atau mengatur kontainer metadata XMP.

Nilai: Kontainer data XMP.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate_internalized() {#validate-internalized--}
```
public void validate_internalized()
```


Rutinitas validasi opsi.

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

