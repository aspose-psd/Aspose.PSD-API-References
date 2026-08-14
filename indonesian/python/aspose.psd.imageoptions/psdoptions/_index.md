---
title: "Kelas PsdOptions"
type: docs
weight: 100
url: /id/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Menginisialisasi sebuah instance baru dari kelas [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | Menginisialisasi sebuah instance baru dari kelas [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | Menginisialisasi sebuah instance baru dari kelas [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Mendapatkan atau mengatur warna latar belakang.<br/>            Dapat dilihat di bawah objek transparan. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| channel_bits_count | short | r/w | Mendapatkan atau mengatur jumlah bit per saluran warna. |
| channels_count | short | r/w | Mendapatkan atau mengatur jumlah saluran warna. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Mendapatkan atau mengatur mode warna PSD. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Mendapatkan atau mengatur metode kompresi PSD. |
| default_replacement_font | string | r/w | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem).<br/>            Untuk mengambil nama font default yang tepat dapat digunakan cuplikan kode berikut:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| full_frame | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Opsi multipage |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Mendapatkan atau mengatur versi format file. Bisa berupa PSD atau PSB. |
| refresh_image_preview_data | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [refresh image preview data] - opsi yang digunakan untuk memaksimalkan kompatibilitas dengan penampil gambar PSD lainnya.<br/>            Harap dicatat, menggambar lapisan teks ke tata letak akhir tidak didukung untuk platform Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah - Hapus sumber daya mesin teks global - Digunakan untuk beberapa file PSD berlapis teks, hanya dalam kasus ketika mereka tidak dapat dibuka di Adobe Photoshop setelah pemrosesan (biasanya terkait lapisan teks dengan font yang tidak ada).<br/>            Setelah menggunakan opsi ini, pengguna perlu melakukan langkah berikut pada file yang dibuka di Photoshop: Menu \"Text\" -&gt; \"Process absent fonts\". Setelah operasi itu semua teks akan muncul kembali.<br/>            Harap dicatat, bahwa operasi ini dapat menyebabkan beberapa perubahan pada tata letak akhir. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Mendapatkan atau mengatur pengaturan resolusi. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Mendapatkan atau mengatur sumber daya PSD. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Mendapatkan atau mengatur sumber untuk membuat gambar di. |
| update_metadata | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [update metadata].<br/>            Jika nilai true, metadata akan diperbarui saat menyimpan gambar. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| version | int | r/w | Mendapatkan atau mengatur versi file PSD. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Dapatkan atau atur kontainer data XMP |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Mengkloning instance ini. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Menginisialisasi sebuah instance baru dari kelas [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Menginisialisasi sebuah instance baru dari kelas [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | Gambar. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Menginisialisasi sebuah instance baru dari kelas [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Opsi. |

### Method: clone() {#clone__1}


```
 clone() 
```

Mengkloning instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Mengembalikan salinan dangkal dari instance ini |


