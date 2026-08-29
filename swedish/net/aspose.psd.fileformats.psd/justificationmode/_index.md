---
title: "Enum JustificationMode"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. Textjusteringsläget"
type: docs
weight: 1690
url: /sv/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

Textjusteringsläge.

```csharp
public enum JustificationMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Left | `0` | Den vänstra justeringen av texten. I ett vänster‑till‑höger‑läge är den vänstra positionen Vänster. I ett höger‑till‑vänster‑läge är den vänstra positionen Höger. |
| Right | `1` | Den högermarginaljusterade texten. I ett vänster-till-höger-läge är den högra positionen Höger. I ett höger-till-vänster-läge är den högra positionen Vänster. |
| Center | `2` | Den centrerade texten. |

## Exempel

Följande kod demonstrerar stöd för JustificationMode‑enum för att ställa in textjusteringen för textavsnitt.

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

### Se även

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


