---
title: "JpegOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi pembuatan format file jpeg."
type: docs
weight: 15
url: /id/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

Opsi pembuatan format file jpeg.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Menginisialisasi instance baru dari kelas  JpegOptions  class. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Menginisialisasi instance baru dari kelas  JpegOptions  class. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Mengkloning instance ini. |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Mengambil bit per kanal untuk gambar jpeg lossless. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Profil warna CMYK tujuan untuk gambar jpeg CMYK. |
| [getColorType()](#getColorType--) | Mendapatkan tipe warna untuk gambar jpeg. |
| [getComment()](#getComment--) | Mendapatkan komentar file jpeg. |
| [getCompressionType()](#getCompressionType--) | Mendapatkan tipe kompresi. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Mendapatkan batas alokasi memori default. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getExifData()](#getExifData--) | Dapatkan atau atur kontainer data exif |
| [getFullFrame()](#getFullFrame--) | Mendapatkan nilai yang menunjukkan apakah [full frame]. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Mendapatkan subsampling horizontal untuk setiap komponen. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [getJfif()](#getJfif--) | Mendapatkan jfif. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Mendapatkan batas perbedaan JPEG-LS untuk pengkodean hampir lossless (parameter NEAR dari spesifikasi JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Mendapatkan mode interleave JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Mendapatkan parameter preset JPEG-LS. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Opsi multipage |
| [getPalette()](#getPalette--) | Mendapatkan atau mengatur palet warna. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Mendapatkan nilai yang menunjukkan apakah komponen merah, hijau, dan biru harus dicampur dengan warna latar belakang, jika saluran alfa hadir. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [getQuality()](#getQuality--) | Mendapatkan kualitas gambar. |
| [getRdOptSettings()](#getRdOptSettings--) | Mendapatkan pengaturan optimizer RD. |
| [getResolutionSettings()](#getResolutionSettings--) | Mendapatkan atau mengatur pengaturan resolusi. |
| [getResolutionUnit()](#getResolutionUnit--) | Mendapatkan satuan resolusi. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Profil warna RGB tujuan untuk gambar jpeg CMYK. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Mendapatkan mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit. |
| [getScaledQuality()](#getScaledQuality--) | Kualitas yang diskalakan. |
| [getSource()](#getSource--) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [getVerticalSampling()](#getVerticalSampling--) | Mendapatkan subsampling vertikal untuk setiap komponen. |
| [getXmpData()](#getXmpData--) | Mendapatkan kontainer metadata XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Mengatur bit per saluran untuk gambar jpeg lossless. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Profil warna CMYK tujuan untuk gambar jpeg CMYK. |
| [setColorType(int value)](#setColorType-int-) | Mengatur tipe warna untuk gambar jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Mengatur komentar file jpeg. |
| [setCompressionType(int value)](#setCompressionType-int-) | Mengatur tipe kompresi. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Mengatur batas alokasi memori default. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | Dapatkan atau atur kontainer data exif |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Mengatur nilai yang menunjukkan apakah [full frame]. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Mengatur subsampling horizontal untuk setiap komponen. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | Mengatur jfif. |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Mengatur batas perbedaan JPEG-LS untuk pengkodean hampir lossless (parameter NEAR dari spesifikasi JPEG-LS). |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Mengatur mode interleave JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | Mengatur parameter preset JPEG-LS. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Opsi multipage |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Mendapatkan atau mengatur palet warna. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Mengatur nilai yang menunjukkan apakah komponen merah, hijau, dan biru harus dicampur dengan warna latar belakang, jika saluran alfa hadir. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [setQuality(int value)](#setQuality-int-) | Mengatur kualitas gambar. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | Mengatur pengaturan optimizer RD. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Mendapatkan atau mengatur pengaturan resolusi. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Mengatur satuan resolusi. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Profil warna RGB tujuan untuk gambar jpeg CMYK. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Mengatur mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Mengatur subsampling vertikal untuk setiap komponen. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Mengatur kontainer metadata XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Menginisialisasi instance baru dari kelas  JpegOptions  class.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Menginisialisasi instance baru dari kelas  JpegOptions  class.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | Opsi JPEG. |

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Mendapatkan bit per saluran untuk gambar jpeg lossless. Sekarang kami mendukung dari 2 hingga 8 bit per saluran.

**Returns:**
byte
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
### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Profil warna CMYK tujuan untuk gambar jpeg CMYK. Gunakan untuk menyimpan gambar. Harus dipasangkan dengan RGBColorProfile untuk konversi warna yang tepat.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


Mendapatkan tipe warna untuk gambar jpeg.

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


Mendapatkan komentar file jpeg.

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Mendapatkan tipe kompresi.

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Mendapatkan batas alokasi memori default.

**Returns:**
int - Batas alokasi memori default.
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
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Dapatkan atau atur kontainer data exif

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Mendapatkan nilai yang menunjukkan apakah [full frame].

Nilai:  true  jika [full frame]; selainnya,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah [full frame].
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Mendapatkan subsampling horizontal untuk setiap komponen.

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan.

Nilai:  true  jika mengabaikan setelah peristiwa pembuatan; selainnya,  false .

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Mendapatkan jfif.

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Mendapatkan batas perbedaan JPEG-LS untuk pengkodean hampir lossless (parameter NEAR dari spesifikasi JPEG-LS).

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Mendapatkan mode interleave JPEG-LS.

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Mendapatkan parameter preset JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
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
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Mendapatkan nilai yang menunjukkan apakah komponen merah, hijau, dan biru harus dicampur dengan warna latar belakang, jika saluran alfa hadir.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Mendapatkan atau mengatur penangan peristiwa kemajuan.

Nilai: Penangan peristiwa kemajuan.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Mendapatkan kualitas gambar.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Mendapatkan pengaturan optimizer RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Mendapatkan atau mengatur pengaturan resolusi.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Mendapatkan satuan resolusi.

**Returns:**
byte - satuan resolusi.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Profil warna RGB tujuan untuk gambar jpeg CMYK. Gunakan untuk menyimpan gambar. Harus dipasangkan dengan CMYKColorProfile untuk konversi warna yang tepat.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Mendapatkan mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit.  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Kualitas yang diskalakan.

**Returns:**
int
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
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Mendapatkan subsampling vertikal untuk setiap komponen.

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Mendapatkan kontainer metadata XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
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




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Mengatur bit per saluran untuk gambar jpeg lossless. Sekarang kami mendukung dari 2 hingga 8 bit per saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Profil warna CMYK tujuan untuk gambar jpeg CMYK. Gunakan untuk menyimpan gambar. Harus dipasangkan dengan RGBColorProfile untuk konversi warna yang tepat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Mengatur tipe warna untuk gambar jpeg.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Mengatur komentar file jpeg.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Mengatur tipe kompresi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Mengatur batas alokasi memori default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Batas alokasi memori default. |

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Dapatkan atau atur kontainer data exif

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

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

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Mengatur subsampling horizontal untuk setiap komponen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

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

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Mengatur jfif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Mengatur batas perbedaan JPEG-LS untuk pengkodean hampir lossless (parameter NEAR dari spesifikasi JPEG-LS).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Mengatur mode interleave JPEG-LS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Mengatur parameter preset JPEG-LS.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

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

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Mengatur nilai yang menunjukkan apakah komponen merah, hijau, dan biru harus dicampur dengan warna latar belakang, jika saluran alfa hadir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Mengatur kualitas gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Mengatur pengaturan optimizer RD.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | Pengaturan optimizer RD. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Mendapatkan atau mengatur pengaturan resolusi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Mengatur satuan resolusi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte | satuan resolusi. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Profil warna RGB tujuan untuk gambar jpeg CMYK. Gunakan untuk menyimpan gambar. Harus dipasangkan dengan CMYKColorProfile untuk konversi warna yang tepat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Mengatur mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit.  P:JpegOptions.BitsPerChannel

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Mengatur subsampling vertikal untuk setiap komponen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Mengatur kontainer metadata XMP.

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

