---
title: "Enum JustificationMode"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. Metin hizalama modu"
type: docs
weight: 1690
url: /tr/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

Metin hizalama modu.

```csharp
public enum JustificationMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Left | `0` | Metni sola hizalar. Soldan sağa modda, Sol konum Sol'dur. Sağdan sola modda, Sol konum Sağ'dır. |
| Right | `1` | Metni sağa hizalar. Soldan sağa modda, Sağ konum Sağ'dır. Sağdan sola modda, Sağ konum Sol'dur. |
| Center | `2` | Metni ortala. |

## Örnekler

Aşağıdaki kod, JustificationMode enum'ının metin bölümleri için metin hizalamasını ayarlama desteğini gösterir.

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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


