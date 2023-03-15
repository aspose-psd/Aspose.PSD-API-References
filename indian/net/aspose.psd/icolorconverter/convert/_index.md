---
title: IColorConverter.Convert
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: IColorConverter तरक. पस कए गए डेट क आउटपुट स्वरूप में कनवर्ट करत है
type: docs
weight: 10
url: /hi/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

पास किए गए डेटा को आउटपुट स्वरूप में कनवर्ट करता है।

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | स्रोत प्रारूप। |
| data | Byte[] | स्रोत डेटा। |
| offset | Int32 | ऑफ़सेट बाइट्स में जहाँ डेटा कॉपी करना शुरू होना चाहिए। |
| bitStart | Int32 | बिट स्टार्ट। ध्यान दें कि यह मान बाइट संरेखित मान नहीं है बल्कि यह वास्तविक बिट है जहां प्रतिलिपि शुरू होनी चाहिए। |
| samplesCount | Int32 | नमूने गिने जाते हैं। |
| linesCount | Int32 | रेखाएँ गिनती हैं। |
| destFormat | PixelDataFormat | गंतव्य प्रारूप। |
| outputData | Byte[] | आउटपुट डेटा। |
| outputOffset | Int32 | आउटपुट ऑफ़सेट जहां डेटा कॉपी करना शुरू होना चाहिए। |

### प्रतिलाभ की मात्रा

रूपांतरित बाइट गिनती.

### यह सभी देखें

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* नाम स्थान [Aspose.PSD](../../icolorconverter/)
* सभा [Aspose.PSD](../../../)


