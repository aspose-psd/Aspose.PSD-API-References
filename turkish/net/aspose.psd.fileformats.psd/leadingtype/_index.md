---
title: "Enum LeadingType"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.LeadingType enum. Photoshop satır aralığı türü, satırlar arasındaki mesafe"
type: docs
weight: 4060
url: /tr/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Photoshop satır aralığı tipi (satırlar arasındaki mesafe türü).

```csharp
public enum LeadingType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| BottomToBottom | `0` | Alt-Alt satır aralığı. |
| TopToTop | `1` | Üst-Üst satır aralığı. |

## Örnekler

Aşağıdaki kod, Paragraf ayarlarından Alt-Alt ve Üst-Üst satır aralığı modlarının desteğini gösterir.

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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


