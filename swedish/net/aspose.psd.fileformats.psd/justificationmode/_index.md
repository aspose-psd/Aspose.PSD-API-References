---
title: Enum JustificationMode
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.JustificationMode uppräkning. Textjusteringsläget.
type: docs
weight: 1650
url: /sv/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

Textjusteringsläget.

```csharp
public enum JustificationMode
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Left | `0` | Den vänsterjusterade texten. |
| Right | `1` | Den högerjusterade texten. |
| Center | `2` | Mitttexten. |

### Exempel

Följande kod visar stöd för JustificationMode enum för att ställa in textjusteringen för textdelar.

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

* namnutrymme [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* hopsättning [Aspose.PSD](../../)


