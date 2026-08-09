---
title: "Énumération LeadingType"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énumération Aspose.PSD.FileFormats.Psd.LeadingType. Type de crénage Photoshop, type de distance entre les lignes"
type: docs
weight: 4030
url: /fr/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Type d'interligne Photoshop (type de distance entre les lignes).

```csharp
public enum LeadingType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| BottomToBottom | `0` | Le crénage de bas en bas. |
| TopToTop | `1` | Le crénage de haut en haut. |

## Exemples

Le code suivant démontre la prise en charge des modes de crénage de bas en bas et de haut en haut provenant des paramètres de paragraphe.

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

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


