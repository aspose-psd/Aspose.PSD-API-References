---
title: "TiffOptions"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Opsi format file tiff."
type: docs
weight: 25
url: /id/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Opsi format file tiff. Perhatikan bahwa tag lebar dan tinggi akan ditimpa saat pembuatan gambar oleh parameter lebar dan tinggi sehingga tidak perlu menyebutkannya secara langsung. Perhatikan bahwa banyak opsi mengembalikan nilai default tetapi itu tidak berarti bahwa opsi ini diatur secara eksplisit sebagai nilai tag. Untuk memverifikasi keberadaan tag, gunakan properti Tags atau metode IsTagPresent yang bersangkutan.

PERINGATAN! jangan pernah mengubah opsi tiff saat menyimpan karena hal ini dapat menyebabkan efek samping dan bug yang sulit ditemukan. Baris berikut secara khusus dibiarkan dalam komentar karena menyebabkan penentuan awal data yang tidak tepat. Opsi yang diberikan tidak mengandung spp (meskipun opsi tersebut tidak benar dalam kasus ini tetapi tetap skenario ini menyebabkan kesalahan) dan baris berikutnya menambahkan tag +spp dan tag +bpp dan ketika opsi ditulis setelah data selesai ditulis mereka menimpa awal data untuk codec tidak terkompresi!!! Lihat TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Menginisialisasi instance baru dari kelas  TiffOptions  . |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Menginisialisasi instance baru dari kelas  TiffOptions  . |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Menginisialisasi instance baru dari kelas  TiffOptions  . |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Menginisialisasi instance baru dari kelas  TiffOptions  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Menambahkan tag baru. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Menambahkan tag-tag. |
| [clone()](#clone--) |  |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [deepClone()](#deepClone--) | Mengkloning instance ini. |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Mendapatkan atau mengatur opsi penyimpanan alfa. |
| [getArtist()](#getArtist--) | Mendapatkan atau mengatur artis. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Mendapatkan atau mengatur warna latar belakang. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Menampilkan bit per piksel. |
| [getBitsPerSample()](#getBitsPerSample--) | Mendapatkan bit per sampel. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getByteOrder()](#getByteOrder--) | Mendapatkan atau mengatur nilai yang menunjukkan urutan byte tiff. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Mendapatkan cache. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Mendapatkan atau mengatur peta warna. |
| [getCompressedQuality()](#getCompressedQuality--) | Mendapatkan kualitas gambar terkompresi. |
| [getCompression()](#getCompression--) | Mendapatkan kompresi. |
| [getCopyright()](#getCopyright--) | Mendapatkan hak cipta. |
| [getDateTime()](#getDateTime--) | Mendapatkan atau mengatur tanggal dan waktu. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Mendapatkan atau mengatur batas alokasi memori default. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getDocumentName()](#getDocumentName--) | Mendapatkan atau mengatur nama dokumen. |
| [getExifIfd()](#getExifIfd--) | Mendapatkan atau mengatur penunjuk ke EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Mendapatkan jumlah sampel ekstra. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Mendapatkan nilai sampel ekstra. |
| [getFaxT4Options()](#getFaxT4Options--) | Mendapatkan atau mengatur opsi fax t4. |
| [getFileStandard()](#getFileStandard--) | Mendapatkan atau mengatur standar file TIFF. |
| [getFillOrder()](#getFillOrder--) | Mendapatkan atau mengatur urutan pengisian bit byte. |
| [getFullFrame()](#getFullFrame--) | Mendapatkan nilai yang menunjukkan apakah [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | Mendapatkan atau mengatur petunjuk setengah nada. |
| [getIccProfile()](#getIccProfile--) | Mendapatkan aliran profil icc. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [getImageDescription()](#getImageDescription--) | Mendapatkan atau mengatur deskripsi gambar. |
| [getImageLength()](#getImageLength--) | Mendapatkan atau mengatur panjang gambar. |
| [getImageWidth()](#getImageWidth--) | Mendapatkan atau mengatur lebar gambar. |
| [getInkNames()](#getInkNames--) | Mendapatkan atau mengatur nama tinta. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Mendapatkan atau mengatur nilai sampel maksimum. |
| [getMinSampleValue()](#getMinSampleValue--) | Mendapatkan atau mengatur nilai sampel minimum. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Opsi multipage |
| [getOrientation()](#getOrientation--) | Mendapatkan atau mengatur orientasi. |
| [getPageName()](#getPageName--) | Mendapatkan atau mengatur nama halaman. |
| [getPageNumber()](#getPageNumber--) | Mendapatkan atau mengatur tag nomor halaman. |
| [getPalette()](#getPalette--) | Mendapatkan atau mengatur palet warna. |
| [getPhotometric()](#getPhotometric--) | Mendapatkan atau mengatur fotometrik. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Mendapatkan atau mengatur konfigurasi planar. |
| [getPredictor()](#getPredictor--) | Mendapatkan atau mengatur prediktor untuk kompresi LZW. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen harus dipremultiplikasi. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [getResolutionSettings()](#getResolutionSettings--) | Mendapatkan atau mengatur pengaturan resolusi. |
| [getResolutionUnit()](#getResolutionUnit--) | Mendapatkan atau mengatur satuan resolusi. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Mendapatkan atau mengatur baris per strip. |
| [getSampleFormat()](#getSampleFormat--) | Mendapatkan atau mengatur format sampel. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Mendapatkan sampel per piksel. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Mendapatkan atau mengatur produsen pemindai. |
| [getScannerModel()](#getScannerModel--) | Mendapatkan atau mengatur model pemindai. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Mendapatkan atau mengatur nilai sampel maksimum. |
| [getSminSampleValue()](#getSminSampleValue--) | Mendapatkan atau mengatur nilai sampel minimum. |
| [getSoftwareType()](#getSoftwareType--) | Mendapatkan atau mengatur jenis perangkat lunak. |
| [getSource()](#getSource--) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [getStripByteCounts()](#getStripByteCounts--) | Mendapatkan atau mengatur jumlah byte strip. |
| [getStripOffsets()](#getStripOffsets--) | Mendapatkan atau mengatur offset strip. |
| [getSubFileType()](#getSubFileType--) | Mendapatkan atau mengatur indikasi umum tentang jenis data yang terdapat dalam subfile ini. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Mendapatkan instance tag berdasarkan tipe. |
| [getTags()](#getTags--) | Mendapatkan atau mengatur tag. |
| [getTargetPrinter()](#getTargetPrinter--) | Mendapatkan atau mengatur printer target. |
| [getThreshholding()](#getThreshholding--) | Mendapatkan atau mengatur penetapan ambang. |
| [getTileByteCounts()](#getTileByteCounts--) | Mendapatkan atau mengatur jumlah byte ubin. |
| [getTileLength()](#getTileLength--) | Mendapatkan ot mengatur panjang ubin. |
| [getTileOffsets()](#getTileOffsets--) | Mendapatkan atau mengatur offset ubin. |
| [getTileWidth()](#getTileWidth--) | Mendapatkan ot mengatur lebar ubin. |
| [getTotalPages()](#getTotalPages--) | Mendapatkan total halaman. |
| [getValidTagCount()](#getValidTagCount--) | Mendapatkan jumlah tag yang valid. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Mendapatkan jumlah tag yang valid. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [getXPAuthor()](#getXPAuthor--) | Mendapatkan penulis gambar, yang digunakan oleh Windows Explorer. |
| [getXPComment()](#getXPComment--) | Mendapatkan komentar pada gambar, yang digunakan oleh Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Mendapatkan subjek gambar, yang digunakan oleh Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Mendapatkan informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| [getXPTitle()](#getXPTitle--) | Mendapatkan informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| [getXmpData()](#getXmpData--) | Mendapatkan atau mengatur kontainer metadata XMP. |
| [getXposition()](#getXposition--) | Mendapatkan atau mengatur posisi x. |
| [getXresolution()](#getXresolution--) | Mendapatkan atau mengatur resolusi x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Mendapatkan atau mengatur YCbCrCoefficients. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Mendapatkan atau mengatur faktor subsampling untuk fotometrik YCbCr. |
| [getYposition()](#getYposition--) | Mendapatkan atau mengatur posisi y. |
| [getYresolution()](#getYresolution--) | Mendapatkan atau mengatur resolusi y. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Mendapatkan nilai yang menunjukkan apakah extra samples ada. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Menentukan apakah tag ada dalam opsi atau tidak. |
| [isTiled()](#isTiled--) | Mendapatkan nilai yang menunjukkan apakah gambar ditile. |
| [isValid()](#isValid--) | Mendapatkan nilai yang menunjukkan apakah TiffOptions telah dikonfigurasi dengan benar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Menghapus tag. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Mendapatkan atau mengatur opsi penyimpanan alfa. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Mendapatkan atau mengatur artis. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Mendapatkan atau mengatur warna latar belakang. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Mengatur bits per sample. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setByteOrder(int value)](#setByteOrder-int-) | Mendapatkan atau mengatur nilai yang menunjukkan urutan byte tiff. |
| [setColorMap(int[] value)](#setColorMap-int---) | Mendapatkan atau mengatur peta warna. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Mengatur kualitas gambar terkompresi. |
| [setCompression(int value)](#setCompression-int-) | Mengatur kompresi. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Mengatur hak cipta. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Mendapatkan atau mengatur tanggal dan waktu. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Mendapatkan atau mengatur batas alokasi memori default. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Mendapatkan atau mengatur nama dokumen. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Mengatur nilai extra samples. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Mendapatkan atau mengatur opsi fax t4. |
| [setFileStandard(int value)](#setFileStandard-int-) | Mendapatkan atau mengatur standar file TIFF. |
| [setFillOrder(int value)](#setFillOrder-int-) | Mendapatkan atau mengatur urutan pengisian bit byte. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Mengatur nilai yang menunjukkan apakah [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Mendapatkan atau mengatur petunjuk setengah nada. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Mengatur aliran profil icc. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Mendapatkan atau mengatur deskripsi gambar. |
| [setImageLength(long value)](#setImageLength-long-) | Mendapatkan atau mengatur panjang gambar. |
| [setImageWidth(long value)](#setImageWidth-long-) | Mendapatkan atau mengatur lebar gambar. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Mendapatkan atau mengatur nama tinta. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Mendapatkan atau mengatur nilai sampel maksimum. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Mendapatkan atau mengatur nilai sampel minimum. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Opsi multipage |
| [setOrientation(int value)](#setOrientation-int-) | Mendapatkan atau mengatur orientasi. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Mendapatkan atau mengatur nama halaman. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Mendapatkan atau mengatur tag nomor halaman. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Mendapatkan atau mengatur palet warna. |
| [setPhotometric(int value)](#setPhotometric-int-) | Mendapatkan atau mengatur fotometrik. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Mendapatkan atau mengatur konfigurasi planar. |
| [setPredictor(int value)](#setPredictor-int-) | Mendapatkan atau mengatur prediktor untuk kompresi LZW. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen harus dipremultiplikasi. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mendapatkan atau mengatur penangan peristiwa kemajuan. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Mendapatkan atau mengatur pengaturan resolusi. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Mendapatkan atau mengatur satuan resolusi. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Mendapatkan atau mengatur baris per strip. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Mendapatkan atau mengatur format sampel. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Mendapatkan atau mengatur produsen pemindai. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Mendapatkan atau mengatur model pemindai. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Mendapatkan atau mengatur nilai sampel maksimum. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Mendapatkan atau mengatur nilai sampel minimum. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Mendapatkan atau mengatur jenis perangkat lunak. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Mendapatkan atau mengatur sumber untuk membuat gambar. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Mendapatkan atau mengatur jumlah byte strip. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Mendapatkan atau mengatur offset strip. |
| [setSubFileType(long value)](#setSubFileType-long-) | Mendapatkan atau mengatur indikasi umum tentang jenis data yang terdapat dalam subfile ini. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Mendapatkan atau mengatur tag. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Mendapatkan atau mengatur printer target. |
| [setThreshholding(int value)](#setThreshholding-int-) | Mendapatkan atau mengatur penetapan ambang. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Mendapatkan atau mengatur jumlah byte ubin. |
| [setTileLength(long value)](#setTileLength-long-) | Mendapatkan ot mengatur panjang ubin. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Mendapatkan atau mengatur offset ubin. |
| [setTileWidth(long value)](#setTileWidth-long-) | Mendapatkan ot mengatur lebar ubin. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Mengatur penulis gambar, yang digunakan oleh Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Mengatur komentar pada gambar, yang digunakan oleh Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Mengatur subjek gambar, yang digunakan oleh Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Mendapatkan atau mengatur kontainer metadata XMP. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur posisi x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur resolusi x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Mendapatkan atau mengatur YCbCrCoefficients. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Mendapatkan atau mengatur faktor subsampling untuk fotometrik YCbCr. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur posisi y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Mendapatkan atau mengatur resolusi y. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Memvalidasi apakah opsi memiliki kombinasi tag yang valid |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Menginisialisasi instance baru dari kelas  TiffOptions  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expectedFormat | int | Format file tiff yang diharapkan. |
| byteOrder | int | Urutan byte format file tiff yang akan digunakan. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Menginisialisasi instance baru dari kelas TiffOptions. Secara default konvensi little endian digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expectedFormat | int | Format file tiff yang diharapkan. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Menginisialisasi instance baru dari kelas  TiffOptions  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Opsi yang akan disalin dari. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Menginisialisasi instance baru dari kelas  TiffOptions  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tag yang akan digunakan untuk menginisialisasi opsi. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Menambahkan tag baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tag yang akan ditambahkan. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Menambahkan tag-tag.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tag yang akan ditambahkan. |

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Mendapatkan atau mengatur opsi penyimpanan alpha. Opsi selain TiffAlphaStorage.Unspecified digunakan ketika ada lebih dari 3 SamplesPerPixel yang didefinisikan.

**Returns:**
int - Opsi penyimpanan alfa.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Mendapatkan atau mengatur artis.

**Returns:**
java.lang.String - Artis.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Mendapatkan atau mengatur warna latar belakang. Digunakan untuk keperluan internal menyimpan warna latar belakang gambar.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Menampilkan bit per piksel.

**Returns:**
int - Bit per piksel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Mendapatkan bit per sampel.

**Returns:**
int[] - Nilai bit per sampel.

Saat mengatur nilai ini, ingat bahwa nilai SamplesPerPixel juga akan diatur ke panjang array. Kedua properti ini sangat terkait erat sehingga hanya dapat diatur sekaligus.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal.

Nilai: Petunjuk ukuran buffer, dalam megabyte. Nilai non-positif berarti tidak ada batas memori untuk buffer internal

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Mendapatkan atau mengatur nilai yang menunjukkan urutan byte tiff.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Mendapatkan cache.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tag | int | Tag (yang merupakan tipe array). |

**Returns:**
long[] - Nilai tag.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Mendapatkan atau mengatur peta warna.

**Returns:**
int[] - Peta warna.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Mendapatkan kualitas gambar terkompresi. Digunakan dengan kompresi JPEG.

**Returns:**
int - kualitas gambar terkompresi.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Mendapatkan kompresi.

**Returns:**
int - Kompresi.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Mendapatkan hak cipta.

**Returns:**
java.lang.String - Hak cipta.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Mendapatkan atau mengatur tanggal dan waktu.

**Returns:**
java.lang.String - Tanggal dan waktu.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Mendapatkan atau mengatur batas alokasi memori default.

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
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Mendapatkan atau mengatur nama dokumen.

**Returns:**
java.lang.String - Nama dokumen.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Mendapatkan atau mengatur penunjuk ke EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Mendapatkan jumlah sampel ekstra.

Nilai: Jumlah sampel ekstra.

**Returns:**
long - jumlah sampel ekstra.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Mendapatkan nilai sampel ekstra.

Nilai: Nilai sampel ekstra.

**Returns:**
int[] - nilai sampel ekstra.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Mendapatkan atau mengatur opsi fax t4.

**Returns:**
long - Opsi fax t4.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Mendapatkan atau mengatur standar file TIFF.

**Returns:**
int - Standar file TIFF.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Mendapatkan atau mengatur urutan pengisian bit byte.

**Returns:**
int - Urutan pengisian bit byte.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Mendapatkan nilai yang menunjukkan apakah [full frame].

Nilai:  true  jika [full frame]; selainnya,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Mendapatkan atau mengatur petunjuk setengah nada.

**Returns:**
int[] - Petunjuk setengah nada.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Mendapatkan aliran profil icc.

**Returns:**
byte[] - Profil ICC.
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah mengabaikan setelah peristiwa pembuatan.

Nilai:  true  jika mengabaikan setelah peristiwa pembuatan; selainnya,  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Mendapatkan atau mengatur deskripsi gambar.

**Returns:**
java.lang.String - Deskripsi gambar.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Mendapatkan atau mengatur panjang gambar.

**Returns:**
long - Panjang gambar.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Mendapatkan atau mengatur lebar gambar.

**Returns:**
long - Lebar gambar.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Mendapatkan atau mengatur nama tinta.

**Returns:**
java.lang.String - Nama tinta.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Mendapatkan atau mengatur nilai sampel maksimum.

**Returns:**
int[] - Nilai sampel maksimum.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Mendapatkan atau mengatur nilai sampel minimum.

**Returns:**
int[] - Nilai sampel minimum.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Opsi multipage

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Mendapatkan atau mengatur orientasi.

**Returns:**
int - Orientasi.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Mendapatkan atau mengatur nama halaman.

**Returns:**
java.lang.String - Nama halaman.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Mendapatkan atau mengatur tag nomor halaman.

**Returns:**
int[] - Tag nomor halaman.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Mendapatkan atau mengatur palet warna.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Mendapatkan atau mengatur fotometrik.

**Returns:**
int - Fotometrik.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Mendapatkan atau mengatur konfigurasi planar.

**Returns:**
int - Konfigurasi planar.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Mendapatkan atau mengatur prediktor untuk kompresi LZW.

**Returns:**
int - Tipe prediktor.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen harus dipremultiplikasi.

**Returns:**
boolean -  true  jika komponen harus dipremultiplikasi; sebaliknya,  false .
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
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Mendapatkan atau mengatur satuan resolusi.

**Returns:**
int - Unit resolusi.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Mendapatkan atau mengatur baris per strip.

**Returns:**
long - Baris per strip.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Mendapatkan atau mengatur format sampel.

**Returns:**
int[] - Format sampel.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Mendapatkan sampel per piksel. Untuk mengubah nilai properti ini gunakan setter properti  BitsPerSample .

**Returns:**
int - Sampel per piksel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Mendapatkan atau mengatur produsen pemindai.

**Returns:**
java.lang.String - Produsen pemindai.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Mendapatkan atau mengatur model pemindai.

**Returns:**
java.lang.String - Model pemindai.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Mendapatkan atau mengatur nilai sampel maksimum. Nilai memiliki tipe bidang yang paling cocok dengan data sampel (tipe Byte, Short, atau Long).

**Returns:**
long[] - Nilai sampel maksimum.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Mendapatkan atau mengatur nilai sampel minimum. Nilai memiliki tipe bidang yang paling cocok dengan data sampel (tipe Byte, Short, atau Long).

**Returns:**
long[] - Nilai sampel minimum.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Mendapatkan atau mengatur jenis perangkat lunak.

**Returns:**
java.lang.String - Tipe perangkat lunak.
### getSource() {#getSource--}
```
public final Source getSource()
```


Mendapatkan atau mengatur sumber untuk membuat gambar.

Nilai: Sumber untuk membuat gambar.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Mendapatkan atau mengatur jumlah byte strip.

**Returns:**
long[] - Hitungan byte strip.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Mendapatkan atau mengatur offset strip.

**Returns:**
long[] - Offset strip.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Mendapatkan atau mengatur indikasi umum tentang jenis data yang terdapat dalam subfile ini.

**Returns:**
long - Indikasi umum tentang jenis data yang terkandung dalam subfile ini.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Mendapatkan instance tag berdasarkan tipe.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tagKey | int | Kunci tag. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Mendapatkan atau mengatur tag.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - Tag-tag.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Mendapatkan atau mengatur printer target.

**Returns:**
java.lang.String - Printer target.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Mendapatkan atau mengatur penetapan ambang.

**Returns:**
int - Ambang batas.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Mendapatkan atau mengatur jumlah byte ubin.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Mendapatkan ot mengatur panjang ubin.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Mendapatkan atau mengatur offset ubin.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Mendapatkan ot mengatur lebar ubin.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Mendapatkan total halaman.

**Returns:**
int - Total halaman.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Mendapatkan jumlah tag yang valid. Ini bukan jumlah total tag tetapi jumlah tag yang dapat dipertahankan.

**Returns:**
int - Jumlah tag yang valid.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Mendapatkan jumlah tag yang valid.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tag yang akan divalidasi. |

**Returns:**
int - Jumlah tag yang valid.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Mendapatkan atau mengatur opsi rasterisasi vektor.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Mendapatkan penulis gambar, yang digunakan oleh Windows Explorer.

Nilai: Penulis Gambar, digunakan oleh Windows Explorer. XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) diabaikan oleh Windows Explorer jika tag Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) ada.

**Returns:**
java.lang.String - penulis gambar, yang digunakan oleh Windows Explorer.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Mendapatkan komentar pada gambar, yang digunakan oleh Windows Explorer.

Nilai: Komentar pada gambar, digunakan oleh Windows Explorer.

**Returns:**
java.lang.String - komentar pada gambar, yang digunakan oleh Windows Explorer.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Mendapatkan subjek gambar, yang digunakan oleh Windows Explorer.

Nilai: Subjek gambar, digunakan oleh Windows Explorer.

**Returns:**
java.lang.String - subjek gambar, yang digunakan oleh Windows Explorer.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Mendapatkan informasi tentang gambar, yang digunakan oleh Windows Explorer.

Nilai: Informasi tentang gambar, digunakan oleh Windows Explorer.

**Returns:**
java.lang.String - informasi tentang gambar, yang digunakan oleh Windows Explorer.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Mendapatkan informasi tentang gambar, yang digunakan oleh Windows Explorer.

Nilai: Informasi tentang gambar, digunakan oleh Windows Explorer. XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) diabaikan oleh Windows Explorer jika tag ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) ada.

**Returns:**
java.lang.String - informasi tentang gambar, yang digunakan oleh Windows Explorer.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Mendapatkan atau mengatur kontainer metadata XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Mendapatkan atau mengatur posisi x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Mendapatkan atau mengatur resolusi x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Mendapatkan atau mengatur YCbCrCoefficients.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Koefisien YCbCr.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Mendapatkan atau mengatur faktor subsampling untuk fotometrik YCbCr.

**Returns:**
int[] - Faktor subsampling untuk fotometrik YCbCr.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Mendapatkan atau mengatur posisi y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Mendapatkan atau mengatur resolusi y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Mendapatkan nilai yang menunjukkan apakah extra samples ada.

**Returns:**
boolean -  true  jika sampel ekstra hadir; jika tidak,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Menentukan apakah tag ada dalam opsi atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tag | int | ID tag untuk diperiksa. |

**Returns:**
boolean -  true  jika tag ada; jika tidak,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Mendapatkan nilai yang menunjukkan apakah gambar ditile.

**Returns:**
boolean -  true  jika gambar berubin; jika tidak,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Mendapatkan nilai yang menunjukkan apakah TiffOptions telah dikonfigurasi dengan benar. Gunakan metode Validate untuk menemukan alasan kegagalan.

**Returns:**
boolean - true jika TiffOptions dikonfigurasi dengan benar; sebaliknya, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Menghapus tag.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tag | int | Tag yang akan dihapus. |

**Returns:**
boolean - true jika berhasil dihapus
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Mendapatkan atau mengatur opsi penyimpanan alpha. Opsi selain TiffAlphaStorage.Unspecified digunakan ketika ada lebih dari 3 SamplesPerPixel yang didefinisikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Opsi penyimpanan alfa. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Mendapatkan atau mengatur artis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Artis. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Mendapatkan atau mengatur warna latar belakang. Digunakan untuk keperluan internal menyimpan warna latar belakang gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Warna latar belakang. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Mengatur bits per sample.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int[] | Nilai bit per sampel. |

Saat mengatur nilai ini, ingat bahwa ini juga akan mengatur nilai SamplesPerPixel ke panjang array. Kedua properti ini sangat terkait erat sehingga hanya dapat diatur sekaligus. |

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

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Mendapatkan atau mengatur nilai yang menunjukkan urutan byte tiff.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Mendapatkan atau mengatur peta warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] | Peta warna. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Mengatur kualitas gambar terkompresi. Digunakan dengan kompresi Jpeg.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | kualitas gambar terkompresi. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Mengatur kompresi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Kompresi. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Mengatur hak cipta.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Hak cipta. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Mendapatkan atau mengatur tanggal dan waktu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Tanggal dan waktu. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Mendapatkan atau mengatur batas alokasi memori default.

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

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Mendapatkan atau mengatur nama dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nama dokumen. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Mengatur nilai extra samples.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] | Nilai sampel ekstra. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Mendapatkan atau mengatur opsi fax t4.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long | Opsi fax t4. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Mendapatkan atau mengatur standar file TIFF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Standar file TIFF. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Mendapatkan atau mengatur urutan pengisian bit byte.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Urutan pengisian bit byte. |

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

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Mendapatkan atau mengatur petunjuk setengah nada.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] | Petunjuk halftone. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Mengatur aliran profil icc.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] | Profil icc. |

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

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Mendapatkan atau mengatur deskripsi gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Deskripsi gambar. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Mendapatkan atau mengatur panjang gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long | Panjang gambar. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Mendapatkan atau mengatur lebar gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long | Lebar gambar. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Mendapatkan atau mengatur nama tinta.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nama tinta. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Mendapatkan atau mengatur nilai sampel maksimum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] | Nilai sampel maksimum. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Mendapatkan atau mengatur nilai sampel minimum.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] | Nilai sampel minimum. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Opsi multipage

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Mendapatkan atau mengatur orientasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Orientasi. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Mendapatkan atau mengatur nama halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nama halaman. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Mendapatkan atau mengatur tag nomor halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] | Tag nomor halaman. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Mendapatkan atau mengatur palet warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Mendapatkan atau mengatur fotometrik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Fotometrik. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Mendapatkan atau mengatur konfigurasi planar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Konfigurasi planar. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Mendapatkan atau mengatur prediktor untuk kompresi LZW.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Jenis prediktor. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen harus dipremultiplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true jika komponen harus dipremultiplikasi; jika tidak, false. |

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

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Mendapatkan atau mengatur satuan resolusi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Unit resolusi. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Mendapatkan atau mengatur baris per strip.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long | Baris per strip. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Mendapatkan atau mengatur format sampel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] | Format sampel. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Mendapatkan atau mengatur produsen pemindai.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Produsen pemindai. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Mendapatkan atau mengatur model pemindai.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Model pemindai. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Mendapatkan atau mengatur nilai sampel maksimum. Nilai memiliki tipe bidang yang paling cocok dengan data sampel (tipe Byte, Short, atau Long).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long[] | Nilai sampel maksimum. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Mendapatkan atau mengatur nilai sampel minimum. Nilai memiliki tipe bidang yang paling cocok dengan data sampel (tipe Byte, Short, atau Long).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long[] | Nilai sampel minimum. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Mendapatkan atau mengatur jenis perangkat lunak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Jenis perangkat lunak. |

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

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Mendapatkan atau mengatur jumlah byte strip.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long[] | Hitungan byte strip. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Mendapatkan atau mengatur offset strip.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long[] | Offset strip. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Mendapatkan atau mengatur indikasi umum tentang jenis data yang terdapat dalam subfile ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long | Indikasi umum tentang jenis data yang terdapat dalam subfile ini. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Mendapatkan atau mengatur tag.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Tag. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Mendapatkan atau mengatur printer target.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Printer target. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Mendapatkan atau mengatur penetapan ambang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Penentuan ambang. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Mendapatkan atau mengatur jumlah byte ubin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Mendapatkan ot mengatur panjang ubin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Mendapatkan atau mengatur offset ubin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Mendapatkan ot mengatur lebar ubin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Mendapatkan atau mengatur opsi rasterisasi vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Mengatur penulis gambar, yang digunakan oleh Windows Explorer.

Nilai: Image Author, digunakan oleh Windows Explorer. XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) diabaikan oleh Windows Explorer jika tag Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) ada.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | penulis gambar, yang digunakan oleh Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Mengatur komentar pada gambar, yang digunakan oleh Windows Explorer.

Nilai: Komentar pada gambar, digunakan oleh Windows Explorer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | komentar pada gambar, yang digunakan oleh Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Mengatur subjek gambar, yang digunakan oleh Windows Explorer.

Nilai: Subjek gambar, digunakan oleh Windows Explorer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | subjek gambar, yang digunakan oleh Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer.

Nilai: Informasi tentang gambar, digunakan oleh Windows Explorer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | informasi tentang gambar, yang digunakan oleh Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer.

Nilai: Information about image, digunakan oleh Windows Explorer. XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) diabaikan oleh Windows Explorer jika tag ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) ada.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | informasi tentang gambar, yang digunakan oleh Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Mendapatkan atau mengatur kontainer metadata XMP.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Kontainer data XMP. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Mendapatkan atau mengatur posisi x.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Posisi x. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Mendapatkan atau mengatur resolusi x.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Resolusi x. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Mendapatkan atau mengatur YCbCrCoefficients.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Koefisien YCbCr. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Mendapatkan atau mengatur faktor subsampling untuk fotometrik YCbCr.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] | Faktor sub-sampling untuk fotometrik YCbCr. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Mendapatkan atau mengatur posisi y.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Posisi y. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Mendapatkan atau mengatur resolusi y.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Resolusi y. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


Memvalidasi apakah opsi memiliki kombinasi tag yang valid

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

