---
title: "क्लास LayerMaskData"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData वर्ग। बेस LayerMaskData वर्ग को परिभाषित करता है जो PSD फ़ाइल में लेयर मास्क डेटा के बारे में जानकारी रखता है। यह Adobe Photoshop फ़ाइलों को प्रोग्रामेटिक रूप से संशोधित करने और PSD फ़ॉर्मेट संपादन को स्वचालित करने में मदद कर सकता है। यदि लेयर में केवल रास्टर मास्क है तो ImageData रास्टर मास्क डेटा बाइट्स रखता है। यदि लेयर में केवल वेक्टर मास्क है तो ImageData वेक्टर मास्क को रास्टराइज़्ड कैश्ड डेटा बाइट्स रखता है। यदि लेयर में दोनों लेयर और वेक्टर मास्क हैं तो ImageData रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क को मिलाकर रखता है। ImageData बाइट्स की लंबाई MaskRectangle गुणों की Width * Height के बराबर होनी चाहिए। ध्यान दें कि केवल LayerMaskData को हटाना / जोड़ना / अपडेट करना सही सहेजने के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं होते हैं हालांकि यह सही रेंडरिंग प्रदान कर सकता है। इस हेतु AddLayerMask मेथड का उपयोग किया जाना चाहिए।"
type: docs
weight: 2440
url: /hi/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

बेस LayerMaskData वर्ग को परिभाषित करता है जो PSD फ़ाइल में लेयर मास्क डेटा के बारे में जानकारी रखता है। यह Adobe® Photoshop® फ़ाइलों को प्रोग्रामेटिक रूप से संशोधित करने और PSD फ़ॉर्मेट संपादन को स्वचालित करने में मदद कर सकता है। यदि लेयर में केवल रास्टर मास्क है तो ImageData रास्टर मास्क डेटा बाइट्स रखता है। यदि लेयर में केवल वेक्टर मास्क है तो ImageData वेक्टर मास्क को रास्टराइज़्ड (कैश्ड) डेटा बाइट्स रखता है। यदि लेयर में दोनों लेयर और वेक्टर मास्क हैं तो ImageData रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क को मिलाकर रखता है। [`ImageData`](./imagedata/) बाइट्स की लंबाई [`MaskRectangle`](./maskrectangle/) गुणों की Width * Height के बराबर होनी चाहिए। ध्यान दें, केवल LayerMaskData को हटाना / जोड़ना / अपडेट करना सही सहेजने के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं होते हैं; हालांकि यह सही रेंडरिंग प्रदान कर सकता है। इस हेतु [`AddLayerMask`](../layer/addlayermask/) मेथड का उपयोग किया जाना चाहिए।

```csharp
public abstract class LayerMaskData
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | नीचे की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | लेयर मास्क डेटा का आकार प्राप्त करता है। |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | डिफ़ॉल्ट रंग को प्राप्त करता है या सेट करता है। |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | लेयर मास्क फ़्लैग्स को प्राप्त करता है या सेट करता है। |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD फ़ाइल में लेयर मास्क डेटा (या संयुक्त/अंतिम मास्क यदि वेक्टर मास्क मौजूद है) को प्राप्त करता है या सेट करता है। |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | बाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | PSD फ़ाइल में लेयर मास्क के मास्क [`Rectangle`](../../aspose.psd/rectangle/) को प्राप्त करता है या सेट करता है। यह बाएँ, दाएँ, ऊपर और नीचे गुण लेता है और एक [`Rectangle`](../../aspose.psd/rectangle/) बनाता है। |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | दाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | ऊपर की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


