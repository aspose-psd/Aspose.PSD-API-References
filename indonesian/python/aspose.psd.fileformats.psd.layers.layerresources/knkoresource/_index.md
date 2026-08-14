---
title: "Kelas KnkoResource"
type: docs
weight: 450
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/
---

**Summary:** Class KnkoResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.KnkoResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [KnkoResource()](#KnkoResource__1) | Menginisialisasi instance baru dari kelas [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/). |
| [KnkoResource(data)](#KnkoResource_data_2) | Menginisialisasi instance baru dari kelas [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).<br/>            Dengan nilai khusus atau tidak diketahui |
| [KnkoResource(knockout)](#KnkoResource_knockout_3) | Menginisialisasi instance baru dari kelas [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| knockout | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [blend interior elements]. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan kontainer aliran yang ditentukan. |


### Constructor: KnkoResource() {#KnkoResource__1}


```
 KnkoResource() 
```

Menginisialisasi instance baru dari kelas [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).

### Constructor: KnkoResource(data) {#KnkoResource_data_2}


```
 KnkoResource(data) 
```

Menginisialisasi instance baru dari kelas [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).<br/>            Dengan nilai khusus atau tidak diketahui

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data sumber daya. |

### Constructor: KnkoResource(knockout) {#KnkoResource_knockout_3}


```
 KnkoResource(knockout) 
```

Menginisialisasi instance baru dari kelas [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| knockout | bool | jika diatur ke <c>true</c> [blend interior elements]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |
| psd_version | int | Versi PSD. |

