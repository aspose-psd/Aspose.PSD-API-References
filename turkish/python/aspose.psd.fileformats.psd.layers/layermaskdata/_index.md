---
title: "LayerMaskData Sınıfı"
type: docs
weight: 970
url: /tr/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

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
| sağ | int | r/w | Sağ katman maskesi konumunu alır veya ayarlar. |
| üst | int | r/w | Üst katman maskesi konumunu alır veya ayarlar. |


