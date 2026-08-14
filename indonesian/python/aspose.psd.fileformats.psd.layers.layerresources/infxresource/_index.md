---
title: "Kelas InfxResource"
type: docs
weight: 420
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | Menginisialisasi instance baru dari kelas [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | Menginisialisasi instance baru dari kelas [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(data)](#InfxResource_data_3) | Menginisialisasi instance baru dari kelas [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            Dengan nilai khusus atau tidak diketahui |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| blend_interior_elements | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [blend interior elements]. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan kontainer aliran yang ditentukan. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

Menginisialisasi instance baru dari kelas [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

Menginisialisasi instance baru dari kelas [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| blend_interior_elements | bool | jika diatur ke <c>true</c> [blend interior elements]. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

Menginisialisasi instance baru dari kelas [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            Dengan nilai khusus atau tidak diketahui

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

