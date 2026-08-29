---
title: "क्लास LayerMaskDataShort"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort क्लास। यह LayerMaskDataShort क्लास को परिभाषित करता है जो PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखती है जब लेयर में केवल रास्टर या वेक्टर मास्क हो लेकिन दोनों नहीं। अन्यथा LayerMaskDataFull का उपयोग किया जाता है। यदि लेयर में केवल रास्टर मास्क है तो ImageData रास्टर मास्क डेटा बाइट्स रखता है। यदि लेयर में केवल वेक्टर मास्क है तो ImageData वेक्टर मास्क को रास्टराइज़्ड कैश्ड डेटा बाइट्स रखता है। ImageData बाइट्स की लंबाई MaskRectangle गुणों की Width Height के बराबर होनी चाहिए।"
type: docs
weight: 2460
url: /hi/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

यह LayerMaskDataShort क्लास को परिभाषित करता है जो PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखती है जब लेयर में केवल रास्टर या वेक्टर मास्क हो लेकिन दोनों नहीं। अन्यथा, एक [`LayerMaskDataFull`](../layermaskdatafull/) का उपयोग किया जाता है। यदि लेयर में केवल रास्टर मास्क है तो ImageData रास्टर मास्क डेटा बाइट्स रखता है। यदि लेयर में केवल वेक्टर मास्क है तो ImageData वेक्टर मास्क को रास्टराइज़्ड (कैश्ड) डेटा बाइट्स रखता है। [`ImageData`](../layermaskdata/imagedata/) बाइट्स की लंबाई [`MaskRectangle`](../layermaskdata/maskrectangle/) गुणों की Width * Height के बराबर होनी चाहिए।

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | `LayerMaskDataShort` क्लास का नया उदाहरण प्रारंभ करता है। |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | लेयर मास्क पैडिंग को प्राप्त करता है या सेट करता है। |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | दाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | ऊपर की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |

### देखें भी

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


