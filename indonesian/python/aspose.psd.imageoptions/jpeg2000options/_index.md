---
title: "Kelas Jpeg2000Options"
type: docs
weight: 50
url: /id/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Menginisialisasi sebuah instance baru dari kelas [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Menginisialisasi sebuah instance baru dari kelas [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | Mendapatkan atau mengatur codec JPEG2000 |
| komentar | string | r/w | Mendapatkan atau mengatur penanda komentar Jpeg. |
| compression_ratios | int | r/w | Mendapatkan atau mengatur Array rasio kompresi.<br/>            Rasio kompresi yang berbeda untuk lapisan berturut-turut.<br/>            Tingkat yang ditentukan untuk setiap level kualitas adalah yang diinginkan<br/>            faktor kompresi.<br/>            Rasio yang menurun diperlukan. |
| default_replacement_font | string | r/w | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem).<br/>            Untuk mengambil nama font default yang tepat dapat digunakan cuplikan kode berikut:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| full_frame | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| irreversible | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah menggunakan DWT 9-7 irreversible (true) atau menggunakan kompresi DWT 5-3 lossless (default). |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Opsi multipage |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Mendapatkan atau mengatur pengaturan resolusi. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Mendapatkan atau mengatur sumber untuk membuat gambar di. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Mendapatkan atau mengatur kontainer metadata XMP. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Mengkloning instance ini. |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Menginisialisasi sebuah instance baru dari kelas [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/)

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Menginisialisasi sebuah instance baru dari kelas [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/)

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | Opsi format file Jpeg2000 untuk menyalin pengaturan dari. |

### Method: clone() {#clone__1}


```
 clone() 
```

Mengkloning instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Mengembalikan salinan dangkal dari instance ini |


