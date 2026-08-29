---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IColorConverter मेथड। पास किए गए डेटा को आउटपुट फ़ॉर्मेट में परिवर्तित करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

प्रेषित डेटा को आउटपुट फ़ॉर्मेट में परिवर्तित करता है।

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | स्रोत फ़ॉर्मेट। |
| डेटा | Byte[] | स्रोत डेटा। |
| offset | Int32 | बाइट्स में ऑफ़सेट जहाँ डेटा कॉपी करना शुरू होना चाहिए। |
| bitStart | Int32 | बिट स्टार्ट। ध्यान दें कि यह मान बाइट-एलाइन्ड नहीं है, बल्कि वह वास्तविक बिट है जहाँ कॉपी शुरू होनी चाहिए। |
| samplesCount | Int32 | सैंपल्स की गिनती। |
| linesCount | Int32 | लाइन की गिनती। |
| destFormat | PixelDataFormat | गंतव्य फ़ॉर्मेट। |
| outputData | Byte[] | आउटपुट डेटा। |
| outputOffset | Int32 | आउटपुट ऑफ़सेट जहाँ डेटा कॉपी शुरू होना चाहिए। |

### रिटर्न वैल्यू

परिवर्तित बाइट्स की गिनती।

### देखें भी

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


