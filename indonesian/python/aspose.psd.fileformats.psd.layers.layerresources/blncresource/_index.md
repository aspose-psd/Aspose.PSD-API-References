---
title: "Kelas BlncResource"
type: docs
weight: 80
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Menginisialisasi instance baru dari kelas [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| highlights_cyan_red_balance | short | r/w | Mendapatkan atau mengatur Highlights Cyan Red Balance. |
| highlights_magenta_green_balance | short | r/w | Mendapatkan atau mengatur Highlights Magenta Green Balance. |
| highlights_yellow_blue_balance | short | r/w | Mendapatkan atau mengatur Highlights Yellow Blue Balance. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| midtones_cyan_red_balance | short | r/w | Mendapatkan atau mengatur Midtones Cyan Red Balance. |
| midtones_magenta_green_balance | short | r/w | Mendapatkan atau mengatur Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | Mendapatkan atau mengatur Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) ini mempertahankan luminositas. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| shadows_cyan_red_balance | short | r/w | Mendapatkan atau mengatur Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | Mendapatkan atau mengatur Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | Mendapatkan atau mengatur Keseimbangan Bayangan Kuning Biru. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Menginisialisasi instance baru dari kelas [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/).

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

