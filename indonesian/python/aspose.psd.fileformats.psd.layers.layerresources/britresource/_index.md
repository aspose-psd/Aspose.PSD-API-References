---
title: "Kelas BritResource"
type: docs
weight: 120
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [BritResource()](#BritResource__1) | Menginisialisasi instance baru dari kelas [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Menginisialisasi instance baru dari kelas [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(bytes)](#BritResource_bytes_3) | Menginisialisasi instance baru dari kelas [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            Spesifikasi format PSD berisi deskripsi berikut:<br/>            2 Kecerahan<br/>            2 Kontras<br/>            2 Nilai rata-rata untuk kecerahan dan kontras<br/>            1 Hanya warna Lab<br/>            Tidak digunakan dalam PSD modern (CS5 ke atas) di mana CgEd berada. CgEd menyimpan properti info |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| kecerahan | short | r/w | Mendapatkan atau mengatur kecerahan. |
| kontras | short | r/w | Mendapatkan atau mengatur kontras. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| lab_color | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [lab color]. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| mean_value_for_brightness_and_contrast | short | r/w | Mendapatkan atau mengatur nilai rata-rata untuk kecerahan dan kontras. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Menginisialisasi instance baru dari kelas [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Menginisialisasi instance baru dari kelas [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| kecerahan | short | Kecerahan. |
| kontras | short | Kontras. |
| mean_value_for_brightness_and_contrast | short | Nilai rata-rata untuk kecerahan dan kontras. |
| lab_color | bool | jika diatur ke <c>true</c> [lab color]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Menginisialisasi instance baru dari kelas [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            Spesifikasi format PSD berisi deskripsi berikut:<br/>            2 Kecerahan<br/>            2 Kontras<br/>            2 Nilai rata-rata untuk kecerahan dan kontras<br/>            1 Hanya warna Lab<br/>            Tidak digunakan dalam PSD modern (CS5 ke atas) di mana CgEd berada. CgEd menyimpan properti info

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| byte | byte | Byte-byte. |

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

