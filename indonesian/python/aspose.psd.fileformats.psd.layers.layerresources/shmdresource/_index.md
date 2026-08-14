---
title: "ShmdResource Kelas"
type: docs
weight: 890
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---

**Summary:** Class ShmdResource. Metadata settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ShmdResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ShmdResource()](#ShmdResource__1) | Menginisialisasi instance baru dari kelas [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/). |
| [ShmdResource(data)](#ShmdResource_data_2) | Menginisialisasi instance baru dari kelas [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| SUB_RESOURCE_HEADER_LENGTH [statis] | int | r | Panjang header sub sumber daya |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| layer_created_date_time | datetime | r/w | Mendapatkan atau mengatur waktu pembuatan lapisan. Jika waktu pembuatan lapisan tidak ditentukan maka mengembalikan DateTime(0) baru. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
| sub_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r | Mendapatkan sub sumber daya dari sumber shmd. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan kontainer aliran yang ditentukan. |


### Constructor: ShmdResource() {#ShmdResource__1}


```
 ShmdResource() 
```

Menginisialisasi instance baru dari kelas [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/).

### Constructor: ShmdResource(data) {#ShmdResource_data_2}


```
 ShmdResource(data) 
```

Menginisialisasi instance baru dari kelas [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data sumber daya. |

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

