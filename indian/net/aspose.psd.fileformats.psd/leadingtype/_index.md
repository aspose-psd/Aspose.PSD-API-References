---
title: "एनम LeadingType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.LeadingType एनम। Photoshop लीडिंग टाइप, पंक्तियों के बीच की दूरी का प्रकार"
type: docs
weight: 4030
url: /hi/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Photoshop लीडिंग टाइप (पंक्तियों के बीच की दूरी का प्रकार)।

```csharp
public enum LeadingType
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| BottomToBottom | `0` | बॉटम-टू-बॉटम लीडिंग। |
| TopToTop | `1` | टॉप-टू-टॉप लीडिंग। |

## उदाहरण

निम्नलिखित कोड पैराग्राफ सेटिंग्स से Bottom-to-bottom और Top-to-Top लीडिंग मोड्स के समर्थन को दर्शाता है।

```csharp
[C#]

string input = "leadingMode.psd";
string output = "output_leadingMode.png";

using (var psdImage = (PsdImage)Image.Load(input, new PsdLoadOptions()))
{
    IText text1 = ((TextLayer)psdImage.Layers[1]).TextData;
    foreach (var textPortion in text1.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.TopToTop; // Change LeadingType value   
    }
    text1.Items[8].Text = "TopToTop";
    text1.Items[8].Style.FillColor = Color.ForestGreen;
    text1.UpdateLayerData();

    IText text2 = ((TextLayer)psdImage.Layers[2]).TextData;
    foreach (var textPortion in text2.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.BottomToBottom; // Change LeadingType value   
    }
    text2.Items[8].Text = "BottomToBottom";
    text2.Items[8].Style.FillColor = Color.ForestGreen;
    text2.UpdateLayerData();

    psdImage.Save(output, new PngOptions());
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


