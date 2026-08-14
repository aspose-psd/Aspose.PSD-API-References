---
title: "ClblResource Kelas"
type: docs
weight: 160
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Menginisialisasi instance baru dari kelas [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Menginisialisasi instance baru dari kelas [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(data)](#ClblResource_data_3) | Menginisialisasi instance baru dari kelas [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) .<br/>            Dengan nilai khusus atau tidak diketahui |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| blend_clipped_elements | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [blend clipped elements]. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan kontainer aliran yang ditentukan. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Menginisialisasi instance baru dari kelas [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Menginisialisasi instance baru dari kelas [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| blend_clipped_elements | bool | jika diatur ke <c>true</c> [blend clipped elements]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Menginisialisasi instance baru dari kelas [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) .<br/>            Dengan nilai khusus atau tidak diketahui

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

