---
title: "Перечисление JustificationMode"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. Режим выравнивания текста"
type: docs
weight: 1690
url: /ru/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

Режим выравнивания текста.

```csharp
public enum JustificationMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Left | `0` | Текст выравнивается по левому краю. В режиме слева направо позиция Left соответствует Left. В режиме справа налево позиция Left соответствует Right. |
| Right | `1` | Текст выравнивается по правому краю. В режиме слева направо позиция Right соответствует Right. В режиме справа налево позиция Right соответствует Left. |
| Center | `2` | Текст по центру. |

## Примеры

Следующий код демонстрирует поддержку перечисления JustificationMode для установки выравнивания текста в его частях.

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

### См. также

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


