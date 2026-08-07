---
title: "PsdOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi pembuatan format file psd."
type: docs
weight: 21
url: /id/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Opsi pembuatan format file psd.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Menginisialisasi instance baru dari kelas [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | Menginisialisasi instance baru dari kelas [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | Menginisialisasi instance baru dari kelas [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Mengkloning instance ini. |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Mendapatkan atau mengatur warna latar belakang. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Mendapatkan atau mengatur jumlah bit per saluran warna. |
| [getChannelsCount()](#getChannelsCount--) | Mendapatkan atau mengatur jumlah saluran warna. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Mendapatkan atau mengatur mode warna psd. |
| [getCompressionMethod()](#getCompressionMethod--) | Mendapatkan atau mengatur metode kompresi psd. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getFullFrame()](#getFullFrame--) | Mendapatkan nilai yang menunjukkan apakah [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Opsi multipage |
| [getPalette()](#getPalette--) | Mendapatkan atau mengatur palet warna. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [getPsdVersion()](#getPsdVersion--) | Mendapatkan atau mengatur versi format file. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [refresh image preview data] - opsi yang digunakan untuk memaksimalkan kompatibilitas dengan penampil gambar PSD lainnya. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah - Hapus sumber daya mesin teks global - Digunakan untuk beberapa file psd berlapis teks, hanya dalam kasus ketika mereka tidak dapat dibuka di Adobe Photoshop setelah diproses (biasanya terkait lapisan teks dengan font yang hilang). |
| [getResolutionSettings()](#getResolutionSettings--) | Mendapatkan atau mengatur pengaturan resolusi. |
| [getResources()](#getResources--) | Mendapatkan atau mengatur sumber daya psd. |
| [getSource()](#getSource--) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [getUpdateMetadata()](#getUpdateMetadata--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [getVersion()](#getVersion--) | Mendapatkan atau mengatur versi file psd. |
| [getXmpData()](#getXmpData--) | Dapatkan atau atur kontainer data XMP |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | Menampilkan apakah properti ColorMode telah ditetapkan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Mendapatkan atau mengatur warna latar belakang. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Mendapatkan atau mengatur jumlah bit per saluran warna. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Mendapatkan atau mengatur jumlah saluran warna. |
| [setColorMode(short value)](#setColorMode-short-) | Mendapatkan atau mengatur mode warna psd. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Mendapatkan atau mengatur metode kompresi psd. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Mengatur nilai yang menunjukkan apakah [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Opsi multipage |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Mendapatkan atau mengatur palet warna. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Mendapatkan atau mengatur versi format file. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [refresh image preview data] - opsi yang digunakan untuk memaksimalkan kompatibilitas dengan penampil gambar PSD lainnya. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah - Hapus sumber daya mesin teks global - Digunakan untuk beberapa file psd berlapis teks, hanya dalam kasus ketika mereka tidak dapat dibuka di Adobe Photoshop setelah diproses (biasanya terkait lapisan teks dengan font yang hilang). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Mendapatkan atau mengatur pengaturan resolusi. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Mendapatkan atau mengatur sumber daya psd. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [setVersion(int value)](#setVersion-int-) | Mendapatkan atau mengatur versi file psd. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Dapatkan atau atur kontainer data XMP |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Menginisialisasi instance baru dari kelas [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Menginisialisasi instance baru dari kelas [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Opsi. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


Menginisialisasi instance baru dari kelas [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Gambar. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Mendapatkan atau mengatur warna latar belakang. Dapat dilihat di bawah objek transparan.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal.

Nilai: Petunjuk ukuran buffer, dalam megabyte. Nilai non-positif berarti tidak ada batas memori untuk buffer internal

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Mendapatkan atau mengatur jumlah bit per saluran warna.

Nilai: Jumlah bit per saluran warna.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Mendapatkan atau mengatur jumlah saluran warna.

Nilai: Jumlah saluran warna.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Mendapatkan atau mengatur mode warna psd.

Nilai: Mode warna.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Mendapatkan atau mengatur metode kompresi psd.

Nilai: Metode kompresi.

**Returns:**
short
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
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Mendapatkan atau mengatur versi format file. Bisa berupa PSD atau PSB.

Nilai: Versi format file.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [refresh image preview data] - opsi yang digunakan untuk memaksimalkan kompatibilitas dengan penampil gambar PSD lainnya. Harap dicatat, menggambar lapisan teks ke tata letak akhir tidak didukung untuk platform Compact Framework.

Nilai:  true  jika [refresh image preview data]; selainnya,  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah - Hapus sumber daya mesin teks global - Digunakan untuk beberapa file psd berlapis teks, hanya dalam kasus ketika mereka tidak dapat dibuka di Adobe Photoshop setelah diproses (biasanya terkait lapisan teks dengan font yang hilang). Setelah menggunakan opsi ini, pengguna perlu melakukan hal berikut pada file yang dibuka di Photoshop: Menu "Text" -> "Process absent fonts". Setelah operasi itu semua teks akan muncul kembali. Harap dicatat, operasi ini dapat menyebabkan beberapa perubahan pada tata letak akhir.

Nilai:  true  jika [remove global text engine resource]; selainnya,  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Mendapatkan atau mengatur pengaturan resolusi.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


Mendapatkan atau mengatur sumber daya psd. Jika nilai: NULL - maka simpan ImageResources asli (perilaku default) Tidak Kosong - maka simpan sumber daya yang diberikan ke properti ini + [required resources] Kosong - maka hanya [required resources] yang disimpan. Sumber daya yang diperlukan: ResolutionInfoResource, XmpResource

Nilai: Sumber daya psd.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Mendapatkan atau mengatur sumber untuk membuat gambar.

Nilai: Sumber untuk membuat gambar.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [update metadata]. Jika nilai true, metadata akan diperbarui saat menyimpan gambar.

Nilai:  true  jika [update metadata]; selainnya,  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Mendapatkan atau mengatur opsi rasterisasi vektor.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Mendapatkan atau mengatur versi file psd.

Nilai: Versi file psd.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Dapatkan atau atur kontainer data XMP

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


Menampilkan apakah properti ColorMode telah ditetapkan.

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




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
```


Mendapatkan atau mengatur warna latar belakang. Dapat dilihat di bawah objek transparan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Mendapatkan atau mengatur jumlah bit per saluran warna.

Nilai: Jumlah bit per saluran warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Mendapatkan atau mengatur jumlah saluran warna.

Nilai: Jumlah saluran warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Mendapatkan atau mengatur mode warna psd.

Nilai: Mode warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Mendapatkan atau mengatur metode kompresi psd.

Nilai: Metode kompresi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Mendapatkan atau mengatur versi format file. Bisa berupa PSD atau PSB.

Nilai: Versi format file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [refresh image preview data] - opsi yang digunakan untuk memaksimalkan kompatibilitas dengan penampil gambar PSD lainnya. Harap dicatat, menggambar lapisan teks ke tata letak akhir tidak didukung untuk platform Compact Framework.

Nilai:  true  jika [refresh image preview data]; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah - Hapus sumber daya mesin teks global - Digunakan untuk beberapa file psd berlapis teks, hanya dalam kasus ketika mereka tidak dapat dibuka di Adobe Photoshop setelah diproses (biasanya terkait lapisan teks dengan font yang hilang). Setelah menggunakan opsi ini, pengguna perlu melakukan hal berikut pada file yang dibuka di Photoshop: Menu "Text" -> "Process absent fonts". Setelah operasi itu semua teks akan muncul kembali. Harap dicatat, operasi ini dapat menyebabkan beberapa perubahan pada tata letak akhir.

Nilai:  true  jika [remove global text engine resource]; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Mendapatkan atau mengatur pengaturan resolusi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


Mendapatkan atau mengatur sumber daya psd. Jika nilai: NULL - maka simpan ImageResources asli (perilaku default) Tidak Kosong - maka simpan sumber daya yang diberikan ke properti ini + [required resources] Kosong - maka hanya [required resources] yang disimpan. Sumber daya yang diperlukan: ResolutionInfoResource, XmpResource

Nilai: Sumber daya psd.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [update metadata]. Jika nilai true, metadata akan diperbarui saat menyimpan gambar.

Nilai:  true  jika [update metadata]; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Mendapatkan atau mengatur opsi rasterisasi vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Mendapatkan atau mengatur versi file psd.

Nilai: Versi file psd.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Dapatkan atau atur kontainer data XMP

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

