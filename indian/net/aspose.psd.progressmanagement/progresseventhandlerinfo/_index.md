---
title: "क्लास ProgressEventHandlerInfo"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo क्लास. यह क्लास इमेज लोड/सेव/एक्सपोर्ट ऑपरेशन्स की प्रगति के बारे में जानकारी दर्शाती है जिसे बाहरी एप्लिकेशन में उपयोग करके अंतिम उपयोगकर्ता को रूपांतरण प्रगति दिखाने के लिए इस्तेमाल किया जा सकता है।"
type: docs
weight: 5800
url: /hi/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

यह क्लास छवि लोड/सेव/एक्सपोर्ट ऑपरेशनों की प्रगति के बारे में जानकारी दर्शाती है, जिसे बाहरी एप्लिकेशन में उपयोगकर्ता को रूपांतरण प्रगति दिखाने के लिए इस्तेमाल किया जा सकता है।

```csharp
public class ProgressEventHandlerInfo
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | इवेंट का विवरण प्राप्त करता है। |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | इवेंट का प्रकार प्राप्त करता है। |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | ऊपरी प्रगति मान सीमा प्राप्त करता है। |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | वर्तमान प्रगति मान प्राप्त करता है। |

## उदाहरण

निम्न उदाहरण दर्शाता है कि दस्तावेज़ रूपांतरण प्रगति सही ढंग से और बिना किसी अपवाद के काम करती है।

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### देखें भी

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


