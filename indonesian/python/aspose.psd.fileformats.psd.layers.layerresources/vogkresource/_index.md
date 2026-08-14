---
title: "Kelas VogkResource"
type: docs
weight: 1110
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---

**Summary:** The Vector Origination Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VogkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [VogkResource()](#VogkResource__1) | Menginisialisasi instance baru dari kelas [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| shape_origin_settings | [VectorShapeOriginSettings[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/) | r/w | Mendapatkan atau mengatur pengaturan asal bentuk. |
| signature | int | r | Mendapatkan signature. |
| version | int | r/w | Mendapatkan atau mengatur versi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: VogkResource() {#VogkResource__1}


```
 VogkResource() 
```

Menginisialisasi instance baru dari kelas [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/).

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

