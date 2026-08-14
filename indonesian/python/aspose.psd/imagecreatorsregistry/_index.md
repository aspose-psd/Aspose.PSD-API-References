---
title: "Kelas ImageCreatorsRegistry"
type: docs
weight: 2210
url: /id/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Mendapatkan deskriptor yang terdaftar. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan format pembuatan gambar yang terdaftar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Membuat pembuat pertama yang ditemukan yang cocok untuk yang ditentukan. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Mendapatkan deskriptor yang pertama ditemukan yang didukung dan cocok untuk yang ditentukan. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Mendaftarkan deskriptor pembuat gambar yang ditentukan. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Mendaftarkan pembuat. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Membatalkan pendaftaran pembuat. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Membuat pembuat pertama yang ditemukan yang cocok untuk yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Pembuat yang mendukung yang ditentukan atau null jika tidak ada pembuat seperti itu yang ditemukan. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Mendapatkan deskriptor yang pertama ditemukan yang didukung dan cocok untuk yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Deskriptor pembuat yang mendukung yang ditentukan atau null jika tidak ada deskriptor seperti itu yang ditemukan. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Mendaftarkan deskriptor pembuat gambar yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Deskriptor pembuat gambar. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Mendaftarkan pembuat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Deskriptor pembuat untuk didaftarkan. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Membatalkan pendaftaran pembuat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Deskriptor pembuat. |

