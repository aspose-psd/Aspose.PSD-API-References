---
title: "LayerMaskDataShort Sınıf"
type: docs
weight: 990
url: /tr/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | LayerMaskDataShort sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| alt | int | r/w | Alt katman maskesi konumunu alır veya ayarlar. |
| data_size | int | r | Katman maskesi veri boyutunu alır. |
| default_color | byte | r/w | Varsayılan rengi alır veya ayarlar. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Katman maskesi bayraklarını alır veya ayarlar. |
| image_data | byte | r/w | PSD dosyasındaki katman maskesi verisini (veya bir vektör maskesi varsa birleşik / son maskeyi) alır veya ayarlar. |
| sol | int | r/w | Sol katman maskesi konumunu alır veya ayarlar. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD dosyasındaki katman maskesinin maske [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini alır veya ayarlar.<br/>            Sol, sağ, üst ve alt özelliklerini alır ve [Rectangle](/psd/python-net/aspose.psd/rectangle/) oluşturur. |
| dolgu | short | r/w | Katman maskesi dolgusunu alır veya ayarlar. |
| sağ | int | r/w | Sağ katman maskesi konumunu alır veya ayarlar. |
| üst | int | r/w | Üst katman maskesi konumunu alır veya ayarlar. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

LayerMaskDataShort sınıfının yeni bir örneğini başlatır.

