---
title: "Класс LayerMaskData"
type: docs
weight: 970
url: /ru/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bottom | int | r/w | Получает или задает положение нижней маски слоя. |
| data_size | int | r | Получает размер данных маски слоя. |
| default_color | байт | r/w | Получает или задает цвет по умолчанию. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Получает или задает флаги маски слоя. |
| image_data | байт | r/w | Получает или задает данные маски слоя (или объединённую/конечную маску, если существует векторная маска) в файле PSD. |
| слева | int | r/w | Получает или задает положение левой маски слоя. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает маску [Rectangle](/psd/python-net/aspose.psd/rectangle/) маски слоя в файле PSD.<br/>            Он принимает свойства left, right, top и bottom и создаёт [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| справа | int | r/w | Получает или задает положение правой маски слоя. |
| верх | int | r/w | Получает или задает положение верхней маски слоя. |


