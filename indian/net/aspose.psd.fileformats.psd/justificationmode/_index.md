---
title: Enum JustificationMode
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.JustificationMode एनुम. पठ संरेखण मड
type: docs
weight: 1650
url: /hi/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

पाठ संरेखण मोड।

```csharp
public enum JustificationMode
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Left | `0` | टेक्स्ट को बाईं ओर संरेखित करें. |
| Right | `1` | टेक्स्ट को दाहिनी ओर संरेखित करें. |
| Center | `2` | मध्य पाठ। |

### उदाहरण

निम्नलिखित कोड पाठ भागों के लिए पाठ संरेखण सेट करने के लिए JustificationMode एनम के समर्थन को प्रदर्शित करता है।

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

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* सभा [Aspose.PSD](../../)


