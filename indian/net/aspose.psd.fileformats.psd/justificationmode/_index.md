---
title: "Enum JustificationMode"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. टेक्स्ट एलाइन्मेंट मोड"
type: docs
weight: 1690
url: /hi/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

टेक्स्ट अलाइनमेंट मोड।

```csharp
public enum JustificationMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Left | `0` | बाएँ संरेखित टेक्स्ट। बाएँ-से-दाएँ मोड में, बाएँ स्थिति बाएँ होती है। दाएँ-से-बाएँ मोड में, बाएँ स्थिति दाएँ होती है। |
| Right | `1` | दाएँ संरेखित टेक्स्ट। बाएँ-से-दाएँ मोड में, दाएँ स्थिति दाएँ होती है। दाएँ-से-बाएँ मोड में, दाएँ स्थिति बाएँ होती है। |
| Center | `2` | केंद्रित टेक्स्ट। |

## उदाहरण

निम्नलिखित कोड JustificationMode enum के समर्थन को दर्शाता है जिससे टेक्स्ट भागों के लिए टेक्स्ट एलाइन्मेंट सेट किया जा सकता है।

```csharp
[C#]

string src = "source1107.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (var image = (PsdImage) Image.Load(src))
{
    var txtLayer = image.AddTextLayer("Text line1\rText line2\rText line3",
        new Rectangle(200, 200, 500, 500));
    var portions = txtLayer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Left;
    portions[1].Paragraph.Justification = JustificationMode.Right;
    portions[2].Paragraph.Justification = JustificationMode.Center;

    foreach (var portion in portions)
    {
        portion.Style.FontSize = 24;
    }

    txtLayer.TextData.UpdateLayerData();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


