---
title: "Kelas TypeToolInfo6Resource"
type: docs
weight: 990
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | Menginisialisasi instance baru dari kelas [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| bawah | int | r/w | Mendapatkan atau mengatur lokasi bawah. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur ID kelas. |
| class_name | string | r/w | Mendapatkan atau mengatur nama kelas. |
| descriptor_version | int | r/w | Mendapatkan atau mengatur versi deskriptor. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Mendapatkan atau mengatur item. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| kiri | int | r/w | Mendapatkan atau mengatur lokasi kiri. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| kanan | int | r/w | Mendapatkan atau mengatur lokasi kanan. |
| signature | int | r | Mendapatkan signature. |
| text_version | short | r/w | Mendapatkan atau mengatur versi teks. |
| atas | int | r/w | Mendapatkan atau mengatur lokasi atas. |
| transform_matrix | double | r/w | Mendapatkan atau mengatur matriks transformasi. |
| version | short | r/w | Mendapatkan atau mengatur versi alat tipe. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Mendapatkan atau mengatur ID kelas. |
| warp_class_name | string | r/w | Mendapatkan atau mengatur nama kelas warp. |
| warp_descriptor_version | int | r/w | Mendapatkan atau mengatur versi deskriptor warp. |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Mendapatkan atau mengatur item warp. |
| warp_version | short | r/w | Mendapatkan atau mengatur versi warp. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

Menginisialisasi instance baru dari kelas [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | ID kelas. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | ID kelas warp. |

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

