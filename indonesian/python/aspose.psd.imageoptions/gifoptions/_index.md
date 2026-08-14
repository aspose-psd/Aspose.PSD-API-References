---
title: "Kelas GifOptions"
type: docs
weight: 30
url: /id/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Menginisialisasi instance baru dari kelas [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Menginisialisasi instance baru dari kelas [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | Mendapatkan atau mengatur indeks warna latar belakang GIF. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| color_resolution | byte | r/w | Mendapatkan atau mengatur resolusi warna GIF. |
| default_replacement_font | string | r/w | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem).<br/>            Untuk mengambil nama font default yang tepat dapat digunakan cuplikan kode berikut:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| do_palette_correction | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan. |
| full_frame | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| has_trailer | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer. |
| interlaced | bool | r/w | Benar jika gambar harus diinterlaced. |
| is_palette_sorted | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan. |
| max_diff | int | r/w | Mendapatkan atau mengatur selisih piksel maksimum yang diizinkan. Jika lebih besar dari nol, kompresi lossy akan digunakan.<br/>            Nilai yang direkomendasikan untuk kompresi lossy optimal adalah 80. 30 adalah kompresi sangat ringan, 200 adalah berat.<br/>            Ini bekerja paling baik ketika hanya sedikit kehilangan yang diperkenalkan, dan karena keterbatasan algoritma kompresi, tingkat kehilangan yang sangat tinggi tidak akan memberikan banyak keuntungan.<br/>            Rentang nilai yang diizinkan adalah [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Opsi multipage |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. |
| pixel_aspect_ratio | byte | r/w | Mendapatkan atau mengatur rasio aspek piksel GIF. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Mendapatkan atau mengatur pengaturan resolusi. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Mendapatkan atau mengatur sumber untuk membuat gambar di. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Mendapatkan atau mengatur kontainer metadata XMP. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Mengkloning instance ini. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Menginisialisasi instance baru dari kelas [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Menginisialisasi instance baru dari kelas [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | Opsi GIF. |

### Method: clone() {#clone__1}


```
 clone() 
```

Mengkloning instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Mengembalikan salinan dangkal dari instance ini |


