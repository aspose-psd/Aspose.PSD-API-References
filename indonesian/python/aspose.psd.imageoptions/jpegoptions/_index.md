---
title: "Kelas JpegOptions"
type: docs
weight: 60
url: /id/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Menginisialisasi instance baru dari kelas [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Menginisialisasi instance baru dari kelas [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Mendapatkan atau mengatur bit per saluran untuk gambar jpeg lossless. Sekarang kami mendukung dari 2 hingga 8 bit per saluran. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Profil warna CMYK tujuan untuk gambar jpeg CMYK. Gunakan untuk menyimpan gambar. Harus dipasangkan dengan RGBColorProfile untuk konversi warna yang tepat. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Mendapatkan atau mengatur jenis warna untuk gambar jpeg. |
| komentar | string | r/w | Mendapatkan atau mengatur komentar file jpeg. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Mendapatkan atau mengatur jenis kompresi. |
| default_memory_allocation_limit | int | r/w | Mendapatkan atau mengatur batas alokasi memori default. |
| default_replacement_font | string | r/w | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem).<br/>            Untuk mengambil nama font default yang tepat dapat digunakan cuplikan kode berikut:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Dapatkan atau atur kontainer data exif |
| full_frame | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| horizontal_sampling | byte | r/w | Mendapatkan atau mengatur sub-sampling horizontal untuk setiap komponen. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Mendapatkan atau mengatur jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Mendapatkan atau mengatur batas perbedaan JPEG-LS untuk pengkodean hampir tak hilang (parameter NEAR dari spesifikasi JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Mendapatkan atau mengatur mode interleave JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Mendapatkan atau mengatur parameter preset JPEG-LS. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Opsi multipage |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. |
| preblend_alpha_if_present | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen merah, hijau, dan biru harus dicampur dengan warna latar belakang, jika saluran alfa hadir. |
| quality | int | r/w | Mendapatkan atau mengatur kualitas gambar. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Mendapatkan atau mengatur pengaturan optimizer RD. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Mendapatkan atau mengatur pengaturan resolusi. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Mendapatkan atau mengatur satuan resolusi. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Profil warna RGB tujuan untuk gambar jpeg CMYK. Gunakan untuk menyimpan gambar. Harus dipasangkan dengan CMYKColorProfile untuk konversi warna yang tepat. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Mendapatkan atau mengatur mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | Kualitas terukur. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Mendapatkan atau mengatur sumber untuk membuat gambar di. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| vertical_sampling | byte | r/w | Mendapatkan atau mengatur subsampling vertikal untuk setiap komponen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Mendapatkan atau mengatur kontainer metadata XMP. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Mengkloning instance ini. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Menginisialisasi instance baru dari kelas [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Menginisialisasi instance baru dari kelas [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | Opsi JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Mengkloning instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Mengembalikan salinan dangkal dari instance ini |


