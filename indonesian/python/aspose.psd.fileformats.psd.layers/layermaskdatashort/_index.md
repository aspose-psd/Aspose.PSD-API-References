---
title: "Kelas LayerMaskDataShort"
type: docs
weight: 990
url: /id/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | Menginisialisasi instance baru dari kelas LayerMaskDataShort |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bawah | int | r/w | Mendapatkan atau mengatur posisi mask lapisan bawah. |
| data_size | int | r | Mendapatkan ukuran data mask lapisan. |
| default_color | byte | r/w | Mendapatkan atau mengatur warna default. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Mendapatkan atau mengatur flag mask lapisan. |
| image_data | byte | r/w | Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD. |
| kiri | int | r/w | Mendapatkan atau mengatur posisi mask lapisan kiri. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Mendapatkan atau mengatur mask [Rectangle](/psd/python-net/aspose.psd/rectangle/) dari mask lapisan dalam file PSD.<br/>            Ini mengambil properti left, right, top, dan bottom serta membuat [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| padding | short | r/w | Mendapatkan atau mengatur padding masker lapisan. |
| kanan | int | r/w | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| atas | int | r/w | Mendapatkan atau mengatur posisi mask lapisan atas. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

Menginisialisasi instance baru dari kelas LayerMaskDataShort

