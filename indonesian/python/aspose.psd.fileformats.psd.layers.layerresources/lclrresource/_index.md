---
title: "Kelas LclrResource"
type: docs
weight: 470
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | Menginisialisasi instance baru dari kelas [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
| [LclrResource(color)](#LclrResource_color_2) | Menginisialisasi instance baru dari kelas [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
| [LclrResource(data)](#LclrResource_data_3) | Menginisialisasi instance baru dari kelas [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | Mendapatkan atau mengatur warna lapisan. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

Menginisialisasi instance baru dari kelas [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

Menginisialisasi instance baru dari kelas [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | Warna. |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

Menginisialisasi instance baru dari kelas [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

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

