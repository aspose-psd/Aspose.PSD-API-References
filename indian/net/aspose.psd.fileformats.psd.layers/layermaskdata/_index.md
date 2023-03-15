---
title: Class LayerMaskData
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData कक्ष. आधर LayerMaskData वर्ग क परभषत करत है जसमें PSD फ़इल में लेयर मस्क डेट के बरे में जनकर हत है यह Adobe Photoshop फ़इलं क प्रग्रमेटक रूप से संशधत करने और PSD प्ररूप संपदन क स्वचलत करने में मदद कर सकत है यद परत में केवल एक रेखपुंज मुखट है त ImageData में रेखपुंज हत है मस्क डेट बइट्स. यद लेयर में केवल वेक्टर मस्क है त ImageData में वेक्टर मस्क रैस्टरइज़्ड कैश्ड डेट बइट्स हते हैं यद लेयर में लेयर और वेक्टर मस्क दनं हैं त इमेजडेट में रैस्टर मस्क और रैस्टरइज़्ड वेक्टर मस्क संयुक्त हते हैं ImageDataबइट्स क लंबई समन चड़ई  क ऊँचई हन चहएMaskRectangle properties. नटस क सर्फ LayerMaskData क हटन/जड़न/अपडेट करन सह सेवंग के लए पर्यप्त नहं है क्यंक चैनल अपडेट नहं हते हैं हलंक यह सह प्रतपदन प्रदन कर सकत है दAddLayerMask उसके लए वध क उपयग कय जन चहए
type: docs
weight: 2240
url: /hi/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

आधार LayerMaskData वर्ग को परिभाषित करता है जिसमें PSD फ़ाइल में लेयर मास्क डेटा के बारे में जानकारी होती है। यह Adobe® Photoshop® फ़ाइलों को प्रोग्रामेटिक रूप से संशोधित करने और PSD प्रारूप संपादन को स्वचालित करने में मदद कर सकता है। यदि परत में केवल एक रेखापुंज मुखौटा है तो ImageData में रेखापुंज होता है मास्क डेटा बाइट्स. यदि लेयर में केवल वेक्टर मास्क है तो ImageData में वेक्टर मास्क रैस्टराइज़्ड (कैश्ड) डेटा बाइट्स होते हैं। यदि लेयर में लेयर और वेक्टर मास्क दोनों हैं तो इमेजडेटा में रैस्टर मास्क और रैस्टराइज़्ड वेक्टर मास्क संयुक्त होते हैं। [`ImageData`](./imagedata/)बाइट्स की लंबाई समान चौड़ाई * की ऊँचाई होनी चाहिए[`MaskRectangle`](./maskrectangle/) properties. नोटिस, कि सिर्फ LayerMaskData को हटाना/जोड़ना/अपडेट करना सही सेविंग के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं होते हैं; हालांकि यह सही प्रतिपादन प्रदान कर सकता है। द[`AddLayerMask`](../layer/addlayermask/) उसके लिए विधि का उपयोग किया जाना चाहिए।

```csharp
public abstract class LayerMaskData
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | बॉटम लेयर मास्क पोजीशन प्राप्त या सेट करता है। |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | लेयर मास्क मास्क डेटा का आकार प्राप्त करता है। |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | डिफ़ॉल्ट रंग प्राप्त या सेट करता है। |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | लेयर मास्क फ़्लैग प्राप्त या सेट करता है. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD फ़ाइल में लेयर मास्क डेटा (या संयुक्त / अंतिम मास्क अगर कोई वेक्टर मास्क है) प्राप्त या सेट करता है। |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | लेफ्ट लेयर मास्क पोजीशन प्राप्त या सेट करता है। |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | मास्क प्राप्त करता है या सेट करता है[`Rectangle`](../../aspose.psd/rectangle/)PSD फ़ाइल में लेयर मास्क का। यह बाएँ, दाएँ, ऊपर और नीचे के गुणों को लेता है और बनाता है[`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | लेयर मास्क की सही स्थिति प्राप्त या सेट करता है। |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | शीर्ष परत मुखौटा स्थिति प्राप्त या सेट करता है। |

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* सभा [Aspose.PSD](../../)


