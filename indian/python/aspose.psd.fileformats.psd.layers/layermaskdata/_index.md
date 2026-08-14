---
title: "LayerMaskData क्लास"
type: docs
weight: 970
url: /hi/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| नीचे | int | r/w | नीचे की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| data_size | int | r | लेयर मास्क डेटा का आकार प्राप्त करता है। |
| default_color | byte | r/w | डिफ़ॉल्ट रंग को प्राप्त करता है या सेट करता है। |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | लेयर मास्क फ्लैग्स को प्राप्त करता है या सेट करता है। |
| image_data | byte | r/w | PSD फ़ाइल में लेयर मास्क डेटा (या संयुक्त/अंतिम मास्क यदि वेक्टर मास्क है) को प्राप्त करता है या सेट करता है। |
| left | int | r/w | बाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | लेयर मास्क के मास्क [Rectangle](/psd/python-net/aspose.psd/rectangle/) को PSD फ़ाइल में प्राप्त करता है या सेट करता है।<br/>            यह बाएँ, दाएँ, ऊपर और नीचे की प्रॉपर्टीज़ लेता है और [Rectangle](/psd/python-net/aspose.psd/rectangle/) बनाता है। |
| right | int | r/w | दाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| ऊपर | int | r/w | ऊपर की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |


