---
title: Class LayerMaskDataFull
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull कक्ष. LayerMaskDataFull क्लस क परभषत करत है जसमें PSD फ़इल लेयर में मस्क डेट के बरे में जनकर हत है जब लेयर में लेयर और वेक्टर मस्क दनं हते हैं अन्यथ एLayerMaskDataShort उपयग कय जत है इमेजडट में रस्टर मस्क और रस्टरइज्ड वेक्टर मस्क संयुक्त हते हैं इमेजडट बइट्स क लंबई मस्करेक्टेंगल के बरबर हन चहए
type: docs
weight: 2250
url: /hi/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

LayerMaskDataFull क्लास को परिभाषित करता है जिसमें PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी होती है, जब लेयर में लेयर और वेक्टर मास्क दोनों होते हैं। अन्यथा, ए[`LayerMaskDataShort`](../layermaskdatashort/) उपयोग किया जाता है। इमेजडाटा में रास्टर मास्क और रास्टराइज्ड वेक्टर मास्क संयुक्त होते हैं। इमेजडाटा बाइट्स की लंबाई मास्करेक्टेंगल के बराबर होनी चाहिए।

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | पृष्ठभूमि का रंग प्राप्त या सेट करता है। |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | बॉटम लेयर मास्क पोजीशन प्राप्त या सेट करता है। |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | लेयर मास्क मास्क डेटा का आकार प्राप्त करता है। |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | डिफ़ॉल्ट रंग प्राप्त या सेट करता है। |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | PSD इमेज लेयर में एनक्लोज़िंग बॉटम रास्टर मास्क पोजिशन प्राप्त या सेट करता है। |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | PSD फ़ाइल परत में संलग्न बाएँ रास्टर मास्क स्थिति को प्राप्त या सेट करता है। |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | PSD फ़ाइल लेयर में संलग्न राइट रास्टर मास्क स्थिति प्राप्त या सेट करता है। |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | PSD छवि परत में रास्टर मास्क की संलग्न शीर्ष स्थिति प्राप्त या सेट करता है। |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | लेयर मास्क फ़्लैग प्राप्त या सेट करता है. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD फ़ाइल में लेयर मास्क डेटा (या संयुक्त / अंतिम मास्क अगर कोई वेक्टर मास्क है) प्राप्त या सेट करता है। |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | लेफ्ट लेयर मास्क पोजीशन प्राप्त या सेट करता है। |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | मास्क प्राप्त करता है या सेट करता है[`Rectangle`](../../aspose.psd/rectangle/)PSD फ़ाइल में लेयर मास्क का। यह बाएँ, दाएँ, ऊपर और नीचे के गुणों को लेता है और बनाता है[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | उपयोगकर्ता / रेखापुंज मास्क के लिए उपयोग किए जाने वाले लेयर मास्क फ़्लैग्स को प्राप्त या सेट करता है। वेक्टर मास्क के लिए फ़्लैग्स गुण का उपयोग किया जाता है. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | लेयर मास्क की सही स्थिति प्राप्त या सेट करता है। |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | शीर्ष परत मुखौटा स्थिति प्राप्त या सेट करता है। |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | PSD फ़ाइल में एक परत के उपयोगकर्ता (रेखापुंज) मास्क डेटा को प्राप्त या सेट करता है। (MaskData प्रॉपर्टी में रेटराइज़्ड वेक्टर मास्क है). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | PSD छवि परत में उपयोगकर्ता मुखौटा (संलग्न) आयत प्राप्त करता है या सेट करता है .. |

### यह सभी देखें

* class [LayerMaskData](../layermaskdata/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* सभा [Aspose.PSD](../../)


