---
title: "Перечисление TextOrientation"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.FileFormats.Psd.TextOrientation. Перечисление режимов ориентации текста"
type: docs
weight: 4480
url: /ru/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

Перечисление режима ориентации текста.

```csharp
public enum TextOrientation
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Horizontal | `0` | Горизонтальная ориентация текста. |
| Vertical | `2` | Вертикальная ориентация текста. |

## Примеры

Следующий код демонстрирует возможность редактировать новое свойство TextOrientation. Это пока не влияет на рендеринг, а только позволяет изменить значение свойства.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Корректное чтение
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // Корректное чтение
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### См. также

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


