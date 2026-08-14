---
title: "CustResource Kelas"
type: docs
weight: 230
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [CustResource()](#CustResource__1) | Menginisialisasi instance baru dari kelas [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
| [CustResource(data)](#CustResource_data_2) | Menginisialisasi instance baru dari kelas [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| layer_created_date_time | datetime | r/w | Mendapatkan atau mengatur tanggal pembuatan lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

Menginisialisasi instance baru dari kelas [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

Menginisialisasi instance baru dari kelas [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data sumber daya. |

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

