---
title: "Перечисление LeadingType"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.FileFormats.Psd.LeadingType. Тип кернинга Photoshop, определяющий расстояние между строками"
type: docs
weight: 4030
url: /ru/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Тип межстрочного интервала Photoshop (вид расстояния между строками).

```csharp
public enum LeadingType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| BottomToBottom | `0` | Кернинг снизу к снизу. |
| TopToTop | `1` | Кернинг сверху к сверху. |

## Примеры

Следующий код демонстрирует поддержку режимов кернинга Bottom-to-bottom и Top-to-Top из настроек абзаца.

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

### См. также

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


