---
title: "Kelas LayerMaskDataFull"
type: docs
weight: 980
url: /id/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Menginisialisasi instance baru dari kelas LayerMaskDataFull |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Mendapatkan atau mengatur warna latar belakang. |
| bawah | int | r/w | Mendapatkan atau mengatur posisi mask lapisan bawah. |
| data_size | int | r | Mendapatkan ukuran data mask lapisan. |
| default_color | byte | r/w | Mendapatkan atau mengatur warna default. |
| enclosing_bottom | int | r/w | Mendapatkan atau mengatur posisi raster mask bawah yang melingkupi dalam lapisan gambar PSD. |
| enclosing_left | int | r/w | Mendapatkan atau mengatur posisi raster mask kiri yang melingkupi dalam lapisan file PSD. |
| enclosing_right | int | r/w | Mendapatkan atau mengatur posisi raster mask kanan yang melingkupi dalam lapisan file PSD. |
| enclosing_top | int | r/w | Mendapatkan atau mengatur posisi atas yang melingkupi dari raster mask dalam lapisan gambar PSD. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Mendapatkan atau mengatur flag mask lapisan. |
| image_data | byte | r/w | Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD. |
| kiri | int | r/w | Mendapatkan atau mengatur posisi mask lapisan kiri. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Mendapatkan atau mengatur mask [Rectangle](/psd/python-net/aspose.psd/rectangle/) dari mask lapisan dalam file PSD.<br/>            Ini mengambil properti left, right, top, dan bottom serta membuat [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Mendapatkan atau mengatur flag masker lapisan yang digunakan untuk masker pengguna / raster. Untuk masker vektor properti Flags digunakan. |
| kanan | int | r/w | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| atas | int | r/w | Mendapatkan atau mengatur posisi mask lapisan atas. |
| user_mask_data | byte | r/w | Mendapatkan atau mengatur data masker pengguna (raster) dari sebuah lapisan dalam file PSD. (Ada masker vektor yang dirasterkan dalam properti MaskData). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Mendapatkan atau mengatur persegi panjang penutup masker pengguna dalam lapisan gambar PSD.. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Menginisialisasi instance baru dari kelas LayerMaskDataFull

