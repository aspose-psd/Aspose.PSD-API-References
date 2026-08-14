---
title: "Kelas GdFlResource"
type: docs
weight: 330
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Menginisialisasi instance baru dari kelas GdFlResource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| align_with_layer | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [align with layer]. |
| sudut | double | r/w | Mendapatkan atau mengatur sudut. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan warna dari RGB. |
| color_model | string | r/w | Model Warna - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Mendapatkan titik warna. |
| dither | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) ini menggunakan dither. |
| gradient_interval | double | r/w | Mendapatkan atau mengatur interval gradien. |
| gradient_mode | string | r/w | Mode untuk gradien ini.<br/>            Menentukan 'Gradient Type' = 'Solid/Noise' = \"CstS\"/\"ClNs\". |
| gradient_name | string | r/w | Mendapatkan atau mengatur nama gradien. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Mendapatkan atau mengatur tipe gradien. |
| horizontal_offset | double | r/w | Mendapatkan atau mengatur offset horizontal. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Warna maksimum dari PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Warna minimum dari PixelDataFormat. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| reverse | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) ini dibalik. |
| rnd_number_seed | int | r/w | Benih angka acak yang digunakan untuk menghasilkan warna pada gradien Noise. |
| kasaran | int | r/w | Faktor kasaran. |
| scale | int | r/w | Mendapatkan atau mengatur skala. |
| show_transparency | bool | r/w | Bendera untuk menampilkan transparansi. |
| signature | int | r | Mendapatkan signature. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Mendapatkan titik transparansi. |
| use_vector_color | bool | r/w | Bendera untuk menggunakan warna vektor. |
| vertical_offset | double | r/w | Mendapatkan atau mengatur offset vertikal. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Menginisialisasi instance baru dari kelas GdFlResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

