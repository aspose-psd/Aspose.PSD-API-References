---
title: Enum JustificationMode
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.JustificationMode Sıralama. Metin hizalama modu.
type: docs
weight: 1650
url: /tr/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

Metin hizalama modu.

```csharp
public enum JustificationMode
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Left | `0` | Sola hizalanan metin. |
| Right | `1` | Sağa hizalama metni. |
| Center | `2` | Orta metin. |

### Örnekler

Aşağıdaki kod, metin bölümleri için metin hizalamasını ayarlamak için JustificationMode enum desteğini gösterir.

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

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* toplantı [Aspose.PSD](../../)


