---
title: "Kelas LinkResource"
type: docs
weight: 540
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---

**Summary:** Defines the LinkResource class that contains information about linked or embedded files in the PSD format image.<br/>            The link resource may contain several [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) instances which can be accessed by indexers in any derived class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| data_source_count | int | r | Mendapatkan jumlah sumber data tautan yang dapat diakses melalui pengindeks. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah instance sumber daya tautan ini kosong. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya tautan global PSD dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan data blok sumber daya. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan data blok sumber daya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

