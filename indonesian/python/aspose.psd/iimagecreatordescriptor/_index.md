---
title: "Kelas IImageCreatorDescriptor"
type: docs
weight: 1770
url: /id/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan format yang didukung. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Menentukan apakah pembuat gambar dapat membuat gambar baru menggunakan <paramref name="imageOptions" />. |
| [create_instance()](#create_instance__2) | Membuat instance pembuat baru. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Menentukan apakah pembuat gambar dapat membuat gambar baru menggunakan <paramref name="imageOptions" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>True</c> jika pembuat gambar yang dibuat oleh deskriptor ini dapat membuat data gambar menggunakan <paramref name="imageOptions" /> yang ditentukan; jika tidak, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Membuat instance pembuat baru.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Sebuah instance pembuat baru. |


