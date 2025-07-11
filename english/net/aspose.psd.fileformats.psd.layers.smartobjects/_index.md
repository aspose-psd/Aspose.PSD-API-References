---
title: Aspose.PSD.FileFormats.Psd.Layers.SmartObjects
second_title: Aspose.PSD for .NET API Reference
description: The namespace contains API to manipulate smart object layer data
type: docs
weight: 350
url: /net/aspose.psd.fileformats.psd.layers.smartobjects/
---
{{< psd/tize >}}
The namespace contains API to manipulate smart object layer data

## Classes

| Class | Description |
| --- | --- |
| [SmartObjectLayer](./smartobjectlayer/) | Defines the SmartObjectLayer class that contains embedded in the PSD file or linked smart object in the external file. With Smart Objects, you can: Perform nondestructive transforms. You can scale, rotate, skew, distort, perspective transform, or warp a layer without losing original image data or quality because the transforms don�t affect the original data. Work with vector data, such as vector artwork from Illustrator, that otherwise would be rasterized. Perform nondestructive filtering. You can edit filters applied to Smart Objects at any time. Edit one Smart Object and automatically update all its linked instances. Apply a layer mask that�s either linked or unlinked to the Smart Object layer. Try various designs with low-resolution placeholder images that you later replace with final versions. In Adobe� Photoshop�, you can embed the contents of an image into a PSD document. More information is here: [https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) A layer with an embedded smart object contains placed (PlLd) and SoLd resources with smart object properties. The PlLd resource can be alone for PSD versions older then 10. These resources contain UniqueId of the LiFdDataSource in the global Lnk2Resource with the embedded filename and other parameters, including the embedded file contents in the original format as a byte array. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [SmartObjectType](./smartobjecttype/) | Defines the SmartObjectType enumeration for smart object content type |


