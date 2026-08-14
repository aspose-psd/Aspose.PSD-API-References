---
title: "Kelas ImageExportersRegistry"
type: docs
weight: 2230
url: /id/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Mendapatkan deskriptor pengekspor yang terdaftar. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan format ekspor yang terdaftar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Membuat pengekspor pertama yang ditemukan yang cocok untuk opsi penyimpanan dan gambar yang ditentukan. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Mendapatkan deskriptor dukungan pertama yang ditemukan yang cocok untuk opsi penyimpanan dan gambar yang ditentukan. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Mendaftarkan deskriptor pengekspor gambar yang ditentukan. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Mendaftarkan pengekspor. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Membatalkan pendaftaran pengekspor. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Membuat pengekspor pertama yang ditemukan yang cocok untuk opsi penyimpanan dan gambar yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan diekspor. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi penyimpanan yang akan digunakan untuk ekspor. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Pengekspor yang mendukung gambar dan opsi penyimpanan yang ditentukan atau null jika tidak ada pengekspor seperti itu yang ditemukan. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Mendapatkan deskriptor dukungan pertama yang ditemukan yang cocok untuk opsi penyimpanan dan gambar yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan diekspor. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Deskriptor pengekspor yang mendukung gambar dan opsi penyimpanan yang ditentukan atau null jika tidak ada deskriptor seperti itu yang ditemukan. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Mendaftarkan deskriptor pengekspor gambar yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Deskriptor pengekspor gambar. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Mendaftarkan pengekspor.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Deskriptor pengekspor untuk didaftarkan. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Membatalkan pendaftaran pengekspor.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Deskriptor pengekspor untuk dibatalkan pendaftarannya. |

