---
title: "Kelas BlwhResource"
type: docs
weight: 90
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Menginisialisasi instance baru dari kelas BlwhResource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| black_and_white_preset_file_name | string | r/w | Mendapatkan atau mengatur nama file preset hitam putih. |
| biru | int | r/w | Mendapatkan atau mengatur nilai biru. |
| bw_preset_kind | int | r/w | Mendapatkan atau mengatur nilai jenis preset hitam putih. |
| sian | int | r/w | Mendapatkan atau mengatur nilai sian. |
| hijau | int | r/w | Mendapatkan atau mengatur nilai hijau. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| magenta | int | r/w | Mendapatkan atau mengatur nilai magenta. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| merah | int | r/w | Mendapatkan atau mengatur nilai merah. |
| signature | int | r | Mendapatkan signature. |
| tint_color | int | r/w | Mendapatkan atau mengatur nilai ARGB Warna Tint. |
| use_tint | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [tint color] digunakan. |
| yellows | int | r/w | Mendapatkan atau mengatur nilai kuning. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Menginisialisasi instance baru dari kelas BlwhResource

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

