---
title: "Kelas GradientFillSettings"
type: docs
weight: 50
url: /id/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Menginisialisasi instance baru dari kelas [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [align with layer]. |
| sudut | double | r/w | Mendapatkan atau mengatur sudut. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Mendapatkan atau mengatur titik warna. |
| dither | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) ini menggunakan dither. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Tipe isian. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Mendapatkan mode untuk gradien ini.<br/>            Menentukan 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Mendapatkan atau mengatur nama gradien. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Mendapatkan atau mengatur tipe gradien. |
| horizontal_offset | double | r/w | Mendapatkan atau mengatur offset horizontal dalam persentase. |
| interpolasi | short | r/w | Interpolasi. Menentukan Kelancaran, ketika 'Gradient Type' = 'Solid'. Rentang nilai: 0-4096. |
| reverse | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) ini terbalik. |
| scale | int | r/w | Mendapatkan atau mengatur skala. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Mendapatkan atau mengatur titik transparansi. |
| vertical_offset | double | r/w | Mendapatkan atau mengatur offset vertikal dalam persentase. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Menambahkan titik warna. |
| [add_transparency_point()](#add_transparency_point__2) | Menambahkan titik warna. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Menghasilkan node sumber daya LFX2. |
| [remove_color_point(point)](#remove_color_point_point_4) | Menghapus titik warna. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Menghapus titik transparansi. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Menginisialisasi instance baru dari kelas [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/)

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Menambahkan titik warna.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Titik warna dibuat |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Menambahkan titik warna.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Titik transparansi dibuat |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Menghasilkan node sumber daya LFX2.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Daftar yang dihasilkan dari [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Menghapus titik warna.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Titik tersebut. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Menghapus titik transparansi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Titik tersebut. |

