---
title: "Kelas LspfResource"
type: docs
weight: 640
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | Menginisialisasi instance baru dari kelas [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
| [LspfResource(data)](#LspfResource_data_2) | Menginisialisasi instance baru dari kelas [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).<br/>            Dengan nilai khusus atau tidak diketahui |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | Menginisialisasi instance baru dari kelas [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info alat tipe 1819504742 |
| is_composite_protected | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi secara komposit. |
| is_position_protected | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi posisi. |
| is_transparency_protected | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dilindungi transparansi. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | Mendapatkan atau mengatur tipe kunci. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

Menginisialisasi instance baru dari kelas [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

Menginisialisasi instance baru dari kelas [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).<br/>            Dengan nilai khusus atau tidak diketahui

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data sumber daya. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

Menginisialisasi instance baru dari kelas [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| is_transparency_protected | bool | jika diatur ke <c>true</c> [dilindungi transparansi]. |
| is_composite_protected | bool | jika diatur ke <c>true</c> [dilindungi komposit]. |
| is_position_protected | bool | jika diatur ke <c>true</c> [dilindungi posisi]. |

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

