---
title: "Kelas ImageLoadersRegistry"
type: docs
weight: 2260
url: /id/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | Mendapatkan deskriptor yang terdaftar. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan format pemuatan gambar yang terdaftar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Membuat pemuat pertama yang ditemukan yang cocok untuk <paramref name="stream" /> yang ditentukan dan secara opsional <paramref name="loadOptions" />. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Mendapatkan deskriptor yang didukung pertama yang ditemukan yang cocok untuk <paramref name="stream" /> yang ditentukan dan secara opsional <paramref name="loadOptions" />. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Mendapatkan format file yang didukung pertama berdasarkan nama tipenya. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Mendapatkan deskriptor pertama yang didukung berdasarkan nama tipenya. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Mendaftarkan deskriptor pemuat gambar yang ditentukan. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Mendaftarkan pemuat. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Membatalkan pendaftaran pemuat. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Membuat pemuat pertama yang ditemukan yang cocok untuk <paramref name="stream" /> yang ditentukan dan secara opsional <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Pemuat yang mendukung <paramref name="stream" /> dan <paramref name="loadOptions" /> yang ditentukan atau null jika tidak ada pemuat seperti itu yang ditemukan. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Mendapatkan deskriptor yang didukung pertama yang ditemukan yang cocok untuk <paramref name="stream" /> yang ditentukan dan secara opsional <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Deskriptor pemuat yang mendukung <paramref name="stream" /> dan <paramref name="loadOptions" /> yang ditentukan atau null jika tidak ada deskriptor seperti itu yang ditemukan. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Mendapatkan format file yang didukung pertama berdasarkan nama tipenya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | Format file deskriptor yang didukung. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Deskriptor pemuat pertama yang ditemukan atau null jika tidak ada deskriptor seperti itu yang ditemukan. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


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
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Deskriptor pemuat pertama yang ditemukan atau null jika tidak ada deskriptor seperti itu yang ditemukan. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Mendaftarkan deskriptor pemuat gambar yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Deskriptor pemuat gambar. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Mendaftarkan pemuat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Deskriptor pemuat untuk didaftarkan. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Membatalkan pendaftaran pemuat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Deskriptor pemuat untuk dibatalkan pendaftarannya. |

