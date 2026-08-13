---
title: "فئة LayerMaskData"
type: docs
weight: 970
url: /ar/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| أسفل | int | r/w | يحصل أو يعيّن موضع قناع الطبقة السفلية. |
| data_size | int | r | يحصل على حجم بيانات قناع الطبقة. |
| default_color | byte | r/w | يحصل أو يعيّن اللون الافتراضي. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | يحصل أو يعيّن علامات قناع الطبقة. |
| image_data | byte | r/w | يحصل أو يعيّن بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| left | int | r/w | يحصل أو يعيّن موضع قناع الطبقة الأيسر. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | يحصل أو يعيّن قناع [Rectangle](/psd/python-net/aspose.psd/rectangle/) لقناع الطبقة في ملف PSD.<br/>            يأخذ خصائص اليسار واليمين والأعلى والأسفل وينشئ [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| right | int | r/w | يحصل أو يعيّن موضع قناع الطبقة الأيمن. |
| أعلى | int | r/w | يحصل أو يعيّن موضع قناع الطبقة العلوي. |


