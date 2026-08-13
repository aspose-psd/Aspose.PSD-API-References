---
title: "فئة LayerMaskDataShort"
type: docs
weight: 990
url: /ar/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | ينشئ مثالًا جديدًا من فئة LayerMaskDataShort |
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
| الحشو | short | r/w | يحصل أو يضبط حشو قناع الطبقة. |
| right | int | r/w | يحصل أو يعيّن موضع قناع الطبقة الأيمن. |
| أعلى | int | r/w | يحصل أو يعيّن موضع قناع الطبقة العلوي. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

ينشئ مثالًا جديدًا من فئة LayerMaskDataShort

