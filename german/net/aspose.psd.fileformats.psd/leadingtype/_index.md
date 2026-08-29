---
title: "Enum LeadingType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.LeadingType enum. Der Photoshop‑Leading‑Typ, Abstand zwischen Zeilen"
type: docs
weight: 4030
url: /de/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Photoshop-Absatztyp (Art des Abstands zwischen Zeilen).

```csharp
public enum LeadingType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| BottomToBottom | `0` | Der Bottom‑to‑Bottom‑Leading. |
| TopToTop | `1` | Der Zeilenabstand von oben nach oben. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der Bottom-to-bottom- und Top-to-Top-Zeilenabstandsmodi aus den Absatz-Einstellungen.

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

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


