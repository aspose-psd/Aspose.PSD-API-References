---
title: "Kelas OSTypeStructuresRegistry"
type: docs
weight: 720
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | Mendapatkan deskriptor yang terdaftar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Mendapatkan deskriptor pembuka pertama yang didukung. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Mendapatkan deskriptor pertama yang didukung berdasarkan nama tipenya. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | Memuat [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) menggunakan pembuka pertama yang ditemukan yang cocok untuk <paramref name="stream" /> yang ditentukan. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Mendaftarkan pembuka. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Membatalkan pendaftaran pembuka. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Mendapatkan deskriptor pembuka pertama yang didukung.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Deskriptor pemuat sumber daya lapisan atau null jika tidak ada deskriptor pemuat yang didukung untuk aliran tersebut. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Mendapatkan deskriptor pertama yang didukung berdasarkan nama tipenya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| descriptor_type_name | string | Nama tipe deskriptor. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Deskriptor pembuka pertama yang ditemukan atau null jika tidak ada deskriptor semacam itu yang ditemukan. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

Memuat [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) menggunakan pembuka pertama yang ditemukan yang cocok untuk <paramref name="stream" /> yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) yang dimuat atau null jika tidak ada pembuka yang ditemukan. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Mendaftarkan pembuka.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Deskriptor pembuka untuk didaftarkan. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Membatalkan pendaftaran pembuka.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Deskriptor pembuka untuk dibatalkan pendaftarannya. |

