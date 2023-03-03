---
title: Class ProgressEventHandlerInfo
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo कक्ष. यह वर्ग छव लड/सहेजें/नर्यत संचलन प्रगत के बरे में जनकर क प्रतनधत्व करत है जसक उपयग बहर अनुप्रयग में अंतम उपयगकर्त क रूपंतरण प्रगत दखने के लए कय ज सकत है
type: docs
weight: 5300
url: /hi/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

यह वर्ग छवि लोड/सहेजें/निर्यात संचालन प्रगति के बारे में जानकारी का प्रतिनिधित्व करता है, जिसका उपयोग बाहरी अनुप्रयोग में अंतिम उपयोगकर्ता को रूपांतरण प्रगति दिखाने के लिए किया जा सकता है

```csharp
public class ProgressEventHandlerInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | घटना का विवरण प्राप्त करता है |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | घटना का प्रकार प्राप्त करता है। |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | ऊपरी प्रगति मान सीमा प्राप्त करता है। |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | वर्तमान प्रगति मान प्राप्त करता है। |

### उदाहरण

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

### यह सभी देखें

* नाम स्थान [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* सभा [Aspose.PSD](../../)


