---
title: "Kelas CgEdResource"
type: docs
weight: 130
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Menginisialisasi sebuah instance baru dari kelas CgEdResource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| auto | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) ini otomatis. |
| kecerahan | int | r/w | Mendapatkan atau mengatur kecerahan. |
| kontras | int | r/w | Mendapatkan atau mengatur kontras. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| lab_color | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [lab color] digunakan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| mean_value_for_brightness_and_contrast | int | r/w | Mendapatkan atau mengatur nilai rata-rata untuk kecerahan dan kontras. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
| use_legacy | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use legacy] digunakan. |
| version | int | r/w | Mendapatkan atau mengatur versi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Menginisialisasi sebuah instance baru dari kelas CgEdResource

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

