---
title: "Kelas PtFlResource"
type: docs
weight: 860
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PtFlResource()](#PtFlResource__1) | Menginisialisasi sebuah instance baru dari kelas [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_2) | Menginisialisasi sebuah instance baru dari kelas [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| align_with_layer | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [align with layer]. |
| sudut | double | r/w | Mendapatkan atau mengatur sudut. |
| is_linked_with_layer | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terhubung dengan lapisan. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | Mendapatkan atau mengatur offset. |
| pattern_id | string | r/w | Mendapatkan atau mengatur pengidentifikasi pola. |
| pattern_name | string | r/w | Mendapatkan atau mengatur nama pola. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| scale | double | r/w | Mendapatkan atau mengatur skala. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: PtFlResource() {#PtFlResource__1}


```
 PtFlResource() 
```

Menginisialisasi sebuah instance baru dari kelas [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_2}


```
 PtFlResource(pattern_name, pattern_id) 
```

Menginisialisasi sebuah instance baru dari kelas [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pattern_name | string | Nama pola. |
| pattern_id | string | Pengidentifikasi pola. |

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

