---
title: Enum JustificationMode
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.JustificationMode opsomming. Der Textausrichtungsmodus.
type: docs
weight: 1650
url: /de/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

Der Textausrichtungsmodus.

```csharp
public enum JustificationMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Left | `0` | Der linksbündige Text. |
| Right | `1` | Der rechtsbündige Text. |
| Center | `2` | Der Text in der Mitte. |

### Beispiele

Der folgende Code demonstriert die Unterstützung der JustificationMode-Enumeration zum Festlegen der Textausrichtung für Textabschnitte.

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

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Montage [Aspose.PSD](../../)


