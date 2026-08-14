---
title: "Kelas VectorRasterizationOptions"
type: docs
weight: 150
url: /id/python-net/aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.VectorRasterizationOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna latar belakang. |
| border_x | float | r/w | Mendapatkan atau mengatur batas X. |
| border_y | float | r/w | Mendapatkan atau mengatur batas Y. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| center_drawing | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah menggambar di tengah. |
| default_replacement_font | string | r/w | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem).<br/>            Untuk mengambil nama font default yang tepat dapat digunakan cuplikan kode berikut:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna latar depan. |
| full_frame | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Opsi multipage |
| page_height | float | r/w | Mendapatkan atau mengatur tinggi halaman. |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Mendapatkan atau mengatur ukuran halaman. |
| page_width | float | r/w | Mendapatkan atau mengatur lebar halaman. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Mendapatkan atau mengatur pengaturan resolusi. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Mendapatkan atau mengatur mode penghalusan. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Mendapatkan atau mengatur sumber untuk membuat gambar di. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Mendapatkan atau mengatur petunjuk rendering teks. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Mendapatkan atau mengatur kontainer metadata XMP. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Mengkloning instance ini. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Menyalin ke. |


### Method: clone() {#clone__1}


```
 clone() 
```

Mengkloning instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Mengembalikan salinan dangkal dari instance ini |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Menyalin ke.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | Opsi rasterisasi vektor. |

