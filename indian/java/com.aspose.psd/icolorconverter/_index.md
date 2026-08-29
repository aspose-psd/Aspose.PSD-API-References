---
title: "IColorConverter"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "रंग परिवर्तक."
type: docs
weight: 116
url: /hi/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

रंग परिवर्तक.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | पास किए गए डेटा को आउटपुट फ़ॉर्मेट में परिवर्तित करता है। |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


पास किए गए डेटा को आउटपुट फ़ॉर्मेट में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | स्रोत प्रारूप। |
| डेटा | byte[] | स्रोत डेटा। |
| ऑफ़सेट | int | डेटा कॉपी करना शुरू करने के लिए बाइट्स में ऑफ़सेट। |
| bitStart | int | बिट प्रारंभ। नोट: यह मान बाइट संरेखित नहीं है, बल्कि वह वास्तविक बिट है जहाँ कॉपी शुरू होनी चाहिए। |
| samplesCount | int | सैंपल्स की गिनती। |
| linesCount | int | लाइन की गिनती। |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | गंतव्य प्रारूप। |
| outputData | byte[] | आउटपुट डेटा। |
| outputOffset | int | आउटपुट ऑफ़सेट जहाँ डेटा कॉपी शुरू होना चाहिए। |

**Returns:**
int - परिवर्तित बाइट्स की गिनती।
