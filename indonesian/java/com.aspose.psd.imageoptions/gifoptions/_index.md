---
title: "GifOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi pembuatan format file gif."
type: docs
weight: 12
url: /id/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

Opsi pembuatan format file gif.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GifOptions()](#GifOptions--) | Menginisialisasi instance baru dari kelas GifOptions. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | Menginisialisasi instance baru dari kelas GifOptions. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Mengkloning instance ini. |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Mendapatkan atau mengatur indeks warna latar belakang GIF. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | Mendapatkan atau mengatur resolusi warna GIF. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan. |
| [getFullFrame()](#getFullFrame--) | Mendapatkan nilai yang menunjukkan apakah [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [getInterlaced()](#getInterlaced--) | Benar jika gambar harus diinterlace. |
| [getMaxDiff()](#getMaxDiff--) | Mendapatkan atau mengatur perbedaan piksel maksimum yang diizinkan. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Opsi multipage |
| [getPalette()](#getPalette--) | Mendapatkan atau mengatur palet warna. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Mendapatkan atau mengatur rasio aspek piksel GIF. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [getResolutionSettings()](#getResolutionSettings--) | Mendapatkan atau mengatur pengaturan resolusi. |
| [getSource()](#getSource--) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [getXmpData()](#getXmpData--) | Mendapatkan atau mengatur kontainer metadata XMP. |
| [hasTrailer()](#hasTrailer--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Mendapatkan atau mengatur indeks warna latar belakang GIF. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Mendapatkan atau mengatur resolusi warna GIF. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Mengatur nilai yang menunjukkan apakah [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Benar jika gambar harus diinterlace. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Mendapatkan atau mengatur perbedaan piksel maksimum yang diizinkan. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Opsi multipage |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Mendapatkan atau mengatur palet warna. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Mendapatkan atau mengatur rasio aspek piksel GIF. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Mendapatkan atau mengatur pengaturan resolusi. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Mendapatkan atau mengatur kontainer metadata XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Menginisialisasi instance baru dari kelas GifOptions.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Menginisialisasi instance baru dari kelas GifOptions.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | Opsi GIF. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Mendapatkan atau mengatur indeks warna latar belakang GIF.

**Returns:**
byte - Indeks warna latar belakang GIF.
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Mendapatkan atau mengatur resolusi warna GIF.

**Returns:**
byte - Resolusi warna.

Color Resolution - Jumlah bit per warna utama yang tersedia pada gambar asli, dikurangi 1. Nilai ini mewakili ukuran seluruh palet dari mana warna dalam grafik dipilih, bukan jumlah warna yang sebenarnya digunakan dalam grafik. Misalnya, jika nilai pada bidang ini adalah 3, maka palet gambar asli memiliki 4 bit per warna utama yang tersedia untuk membuat gambar. Nilai ini harus diatur untuk menunjukkan kekayaan palet asli, meskipun tidak semua warna dari seluruh palet tersedia pada mesin sumber.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan.

**Returns:**
boolean -  true  jika koreksi palet diterapkan; jika tidak,  false .

Koreksi palet berarti bahwa setiap kali gambar diekspor ke GIF, warna gambar sumber akan dianalisis untuk membangun palet yang paling cocok (jika Palet gambar tidak ada atau tidak ditentukan dalam opsi). Proses analisis memerlukan waktu, namun gambar output akan memiliki palet warna yang paling cocok dan hasilnya secara visual lebih baik.
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
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Benar jika gambar harus diinterlace.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Mengambil atau mengatur perbedaan piksel maksimum yang diizinkan. Jika lebih besar dari nol, kompresi lossy akan digunakan. Nilai yang direkomendasikan untuk kompresi lossy optimal adalah 80. 30 adalah kompresi sangat ringan, 200 sangat berat. Ini bekerja paling baik ketika hanya sedikit kehilangan yang diperkenalkan, dan karena keterbatasan algoritma kompresi, tingkat kehilangan yang sangat tinggi tidak memberikan banyak keuntungan. Rentang nilai yang diizinkan adalah [0, 1000].

**Returns:**
int - Rentang nilai yang diizinkan.
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Mendapatkan atau mengatur rasio aspek piksel GIF.

Pixel Aspect Ratio - Faktor yang digunakan untuk menghitung perkiraan rasio aspek piksel dalam gambar asli. Jika nilai bidang ini bukan 0, perkiraan rasio aspek ini dihitung berdasarkan rumus: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio didefinisikan sebagai hasil bagi lebar piksel dengan tinggi piksel. Rentang nilai dalam bidang ini memungkinkan spesifikasi piksel terlebar 4:1 hingga piksel tertinggi 1:4 dengan kenaikan 1/64. Nilai: 0 - Tidak ada informasi rasio aspek yang diberikan. 1..255 - Nilai yang digunakan dalam perhitungan.

**Returns:**
byte - Rasio aspek piksel GIF.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Mendapatkan atau mengatur penangan peristiwa kemajuan.

Nilai: Penangan peristiwa kemajuan.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer.

**Returns:**
boolean -  true  jika GIF memiliki trailer; jika tidak,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan.

**Returns:**
boolean -  true  jika entri palet diurutkan; jika tidak,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Mendapatkan atau mengatur indeks warna latar belakang GIF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte | Indeks warna latar belakang GIF. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Mendapatkan atau mengatur resolusi warna GIF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | byte | Resolusi warna. |

Color Resolution - Jumlah bit per warna utama yang tersedia pada gambar asli, dikurangi 1. Nilai ini mewakili ukuran seluruh palet dari mana warna dalam grafik dipilih, bukan jumlah warna yang sebenarnya digunakan dalam grafik. Misalnya, jika nilai pada bidang ini adalah 3, maka palet gambar asli memiliki 4 bit per warna utama yang tersedia untuk membuat gambar. Nilai ini harus diatur untuk menunjukkan kekayaan palet asli, meskipun tidak semua warna dari seluruh palet tersedia pada mesin sumber. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  jika koreksi palet diterapkan; jika tidak,  false . |

Koreksi palet berarti bahwa setiap kali gambar diekspor ke GIF, warna gambar sumber akan dianalisis untuk membangun palet yang paling cocok (jika Palet gambar tidak ada atau tidak ditentukan dalam opsi). Proses analisis memerlukan waktu, namun gambar output akan memiliki palet warna yang paling cocok dan hasilnya secara visual lebih baik. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Benar jika gambar harus diinterlace.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Mengambil atau mengatur perbedaan piksel maksimum yang diizinkan. Jika lebih besar dari nol, kompresi lossy akan digunakan. Nilai yang direkomendasikan untuk kompresi lossy optimal adalah 80. 30 adalah kompresi sangat ringan, 200 sangat berat. Ini bekerja paling baik ketika hanya sedikit kehilangan yang diperkenalkan, dan karena keterbatasan algoritma kompresi, tingkat kehilangan yang sangat tinggi tidak memberikan banyak keuntungan. Rentang nilai yang diizinkan adalah [0, 1000].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Rentang nilai yang diizinkan. |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika entri palet diurutkan; jika tidak,  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Mendapatkan atau mengatur rasio aspek piksel GIF.

Pixel Aspect Ratio - Faktor yang digunakan untuk menghitung perkiraan rasio aspek piksel dalam gambar asli. Jika nilai bidang ini bukan 0, perkiraan rasio aspek ini dihitung berdasarkan rumus: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio didefinisikan sebagai hasil bagi lebar piksel dengan tinggi piksel. Rentang nilai dalam bidang ini memungkinkan spesifikasi piksel terlebar 4:1 hingga piksel tertinggi 1:4 dengan kenaikan 1/64. Nilai: 0 - Tidak ada informasi rasio aspek yang diberikan. 1..255 - Nilai yang digunakan dalam perhitungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte | Rasio aspek piksel GIF. |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika GIF memiliki trailer; jika tidak,  false . |

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

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Kontainer data XMP. |

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

