---
title: "Kelas LayerMaskData"
type: docs
weight: 970
url: /id/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

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
| kanan | int | r/w | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| atas | int | r/w | Mendapatkan atau mengatur posisi mask lapisan atas. |


