---
title: "Kelas GrdmResource"
type: docs
weight: 340
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Menginisialisasi instance baru dari kelas [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| color_model | short | r/w | Model Warna.<br/>            Ketika 'Gradient type' = 'Noise', kita dapat menetapkan 'Color Model' ke RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Mendapatkan atau mengatur titik warna. |
| dither | bool | r/w | Apakah gradien dithered. |
| expansion_count | short | r/w | Jumlah ekspansi ( = 2 untuk Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Mode untuk gradien ini<br/>            Menentukan 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Nama gradien: string Unicode, dipadding. |
| interpolasi | short | r/w | Interpolasi. Menentukan Kelancaran, ketika 'Gradient Type' = 'Solid' (GradientMode = 0). |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Warna maksimum dari format PixelDataFormat.Rgba64Bpp.<br/>            Warna memiliki saluran ARGB, setiap saluran berukuran 16 bit. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Warna minimum dari format PixelDataFormat.Rgba64Bpp.<br/>            Warna memiliki saluran ARGB, setiap saluran berukuran 16 bit. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| reverse | bool | r/w | Apakah gradien dibalik. |
| rnd_number_seed | int | r/w | Benih angka acak yang digunakan untuk menghasilkan warna pada gradien Noise. |
| kasaran | int | r/w | Faktor kekasaran<br/>            Ketika 'Gradient type' = 'Noise', kita dapat menetapkan 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | Bendera untuk menampilkan transparansi<br/>            Ketika 'Gradient type' = 'Noise', kita dapat menetapkan 'Add transparency' ke true. |
| signature | int | r | Mendapatkan signature. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Mendapatkan atau mengatur titik transparansi. |
| use_vector_color | short | r/w | Bendera untuk menggunakan warna vektor. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan data sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Menginisialisasi instance baru dari kelas [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| psd_version | int | Versi psd dari sumber daya. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan data sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |
| psd_version | int | Versi PSD. |

