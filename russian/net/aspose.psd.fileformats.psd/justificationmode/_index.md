---
title: Enum JustificationMode
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.JustificationMode перечисление. Режим выравнивания текста.
type: docs
weight: 1650
url: /ru/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

Режим выравнивания текста.

```csharp
public enum JustificationMode
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Left | `0` | Текст с выравниванием по левому краю. |
| Right | `1` | Текст с выравниванием по правому краю. |
| Center | `2` | Текст в центре. |

### Примеры

Следующий код демонстрирует поддержку перечисления JustificationMode для установки выравнивания текста для текстовых частей.

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

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* сборка [Aspose.PSD](../../)


