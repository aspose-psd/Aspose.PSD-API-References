---
title: "Kelas IImageExporterDescriptor"
type: docs
weight: 1800
url: /id/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan format yang didukung. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Menentukan apakah pengekspor gambar dapat mengekspor gambar yang ditentukan ke format gambar yang ditentukan oleh opsi penyimpanan. |
| [create_instance()](#create_instance__2) | Membuat instance pengekspor baru. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Menentukan apakah pengekspor gambar dapat mengekspor gambar yang ditentukan ke format gambar yang ditentukan oleh opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan diekspor. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Basis opsi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>True</c> jika pengekspor yang dibuat oleh deskriptor ini dapat mengekspor gambar yang ditentukan ke format file yang ditentukan; jika tidak, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Membuat instance pengekspor baru.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Sebuah instance pengekspor baru. |


