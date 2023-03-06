---
title: Enum JustificationMode
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.JustificationMode opsomming. De tekstuitlijningsmodus.
type: docs
weight: 1650
url: /nl/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

De tekstuitlijningsmodus.

```csharp
public enum JustificationMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Left | `0` | De links uitgelijnde tekst. |
| Right | `1` | De rechts uitgelijnde tekst. |
| Center | `2` | De middelste tekst. |

### Voorbeelden

De volgende code demonstreert de ondersteuning van JustificationMode enum om de tekstuitlijning voor tekstgedeelten in te stellen.

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

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* montage [Aspose.PSD](../../)


