---
title: "Enum JustificationMode"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. Der Textausrichtungsmodus"
type: docs
weight: 1690
url: /de/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

Der Textausrichtungsmodus.

```csharp
public enum JustificationMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Left | `0` | Der links ausgerichtete Text. In einem Links‑nach‑Rechts‑Modus ist die Left‑Position Left. In einem Rechts‑nach‑Links‑Modus ist die Left‑Position Right. |
| Right | `1` | Der rechts ausgerichtete Text. In einem Links‑nach‑Rechts‑Modus ist die Right‑Position Right. In einem Rechts‑nach‑Links‑Modus ist die Right‑Position Left. |
| Center | `2` | Der zentrierte Text. |

## Beispiele

Der folgende Code demonstriert die Unterstützung des JustificationMode‑Enums, um die Textausrichtung für Textabschnitte festzulegen.

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


