---
title: "Enum JustificationMode"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. Le mode d’alignement du texte"
type: docs
weight: 1690
url: /fr/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

Le mode d'alignement du texte.

```csharp
public enum JustificationMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Left | `0` | Le texte aligné à gauche. En mode de gauche à droite, la position Left est Left. En mode de droite à gauche, la position Left est Right. |
| Right | `1` | Le texte aligné à droite. En mode de gauche à droite, la position Right est Right. En mode de droite à gauche, la position Right est Left. |
| Center | `2` | Le texte centré. |

## Exemples

Le code suivant montre la prise en charge de JustificationMode enum pour définir l’alignement du texte pour les portions de texte.

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

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


