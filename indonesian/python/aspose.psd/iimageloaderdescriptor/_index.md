---
title: "Kelas IImageLoaderDescriptor"
type: docs
weight: 1820
url: /id/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan format yang didukung. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Menentukan apakah pemuat gambar dapat membaca gambar baru dari aliran yang ditentukan dan secara opsional menggunakan <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__2) | Membuat instance pemuat baru. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Menentukan apakah pemuat gambar dapat membaca gambar baru dari aliran yang ditentukan dan secara opsional menggunakan <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Detail format file yang ditentukan oleh <paramref name="loadOptions" />. <paramref name="loadOptions" /> dapat bernilai null. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika pemuat gambar yang dibuat oleh deskriptor ini dapat membaca gambar dari aliran; jika tidak, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Membuat instance pemuat baru.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Instance pemuat baru. |


