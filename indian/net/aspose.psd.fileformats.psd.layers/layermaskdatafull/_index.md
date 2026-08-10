---
title: "क्लास LayerMaskDataFull"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull वर्ग। LayerMaskDataFull वर्ग को परिभाषित करता है जो PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखता है जब लेयर में दोनों लेयर और वेक्टर मास्क होते हैं। अन्यथा LayerMaskDataShort का उपयोग किया जाता है। ImageData रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क को मिलाकर रखता है। ImageData बाइट्स की लंबाई MaskRectangle.Width * MaskRectangle.Height गुणों के बराबर होनी चाहिए।"
type: docs
weight: 2450
url: /hi/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

LayerMaskDataFull वर्ग को परिभाषित करता है जो PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखता है जब लेयर में दोनों लेयर और वेक्टर मास्क होते हैं। अन्यथा, एक [`LayerMaskDataShort`](../layermaskdatashort/) का उपयोग किया जाता है। ImageData रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क को मिलाकर रखता है। ImageData बाइट्स की लंबाई MaskRectangle.Width * MaskRectangle.Height गुणों के बराबर होनी चाहिए।

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग को प्राप्त करता है या सेट करता है। |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | नीचे की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | लेयर मास्क डेटा का आकार प्राप्त करता है। |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | डिफ़ॉल्ट रंग को प्राप्त करता है या सेट करता है। |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | PSD इमेज लेयर में संलग्न नीचे रास्टर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | PSD फ़ाइल लेयर में संलग्न बाएँ रास्टर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | PSD फ़ाइल लेयर में संलग्न दाएँ रास्टर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | PSD इमेज लेयर में रास्टर मास्क की संलग्न ऊपर स्थिति को प्राप्त करता है या सेट करता है। |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | लेयर मास्क फ़्लैग्स को प्राप्त करता है या सेट करता है। |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD फ़ाइल में लेयर मास्क डेटा (या संयुक्त/अंतिम मास्क यदि वेक्टर मास्क मौजूद है) को प्राप्त करता है या सेट करता है। |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | बाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | PSD फ़ाइल में लेयर मास्क के मास्क [`Rectangle`](../../aspose.psd/rectangle/) को प्राप्त करता है या सेट करता है। यह बाएँ, दाएँ, ऊपर और नीचे गुण लेता है और एक [`Rectangle`](../../aspose.psd/rectangle/) बनाता है। |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | लेयर मास्क फ़्लैग्स को प्राप्त करता है या सेट करता है जो उपयोगकर्ता/रास्टर मास्क के लिए उपयोग होते हैं। वेक्टर मास्क के लिए Flags प्रॉपर्टी उपयोग की जाती है। |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | दाएँ लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | ऊपर की लेयर मास्क स्थिति को प्राप्त करता है या सेट करता है। |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | PSD फ़ाइल में लेयर के उपयोगकर्ता (रास्टर) मास्क डेटा को प्राप्त करता है या सेट करता है। (MaskData प्रॉपर्टी में एक रास्टराइज़्ड वेक्टर मास्क है)। |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | PSD इमेज लेयर में उपयोगकर्ता मास्क (संलग्न) आयत को प्राप्त करता है या सेट करता है। |

### देखें भी

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


