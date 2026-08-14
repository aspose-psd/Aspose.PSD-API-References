---
title: "Kelas PngOptions"
type: docs
weight: 90
url: /id/python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Menginisialisasi instansi baru dari kelas [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Menginisialisasi instansi baru dari kelas [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | Level kompresi default. |
| bit_depth | byte | r/w | Kedalaman bit. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | Mendapatkan atau mengatur tipe warna. |
| compression_level | int | r/w | Level kompresi gambar png dalam rentang 0-9, di mana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan. |
| default_replacement_font | string | r/w | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem).<br/>            Untuk mengambil nama font default yang tepat dapat digunakan cuplikan kode berikut:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | Mendapatkan atau mengatur tipe filter yang digunakan selama proses penyimpanan file png. |
| full_frame | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Opsi multipage |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. |
| progressive | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) bersifat progresif. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Mendapatkan atau mengatur pengaturan resolusi. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Mendapatkan atau mengatur sumber untuk membuat gambar di. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Mendapatkan atau mengatur kontainer metadata XMP. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Mengkloning instance ini. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Menginisialisasi instansi baru dari kelas [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Menginisialisasi instansi baru dari kelas [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | Opsi PNG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Mengkloning instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Mengembalikan salinan dangkal dari instance ini |


