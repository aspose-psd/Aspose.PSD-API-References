---
title: Enum TextOrientation
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.TextOrientation перечисление. Перечисление для режима ориентации текста.
type: docs
weight: 4010
url: /ru/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

Перечисление для режима ориентации текста.

```csharp
public enum TextOrientation
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Horizontal | `0` | Горизонтальная ориентация текста. |
| Vertical | `2` | Вертикальная ориентация текста. |

### Примеры

Следующий код демонстрирует возможность редактирования нового свойства TextOrientation. В данный момент это не влияет на рендеринг, а только позволяет редактировать значение свойства.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Правильное чтение
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
        // Правильное чтение
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* сборка [Aspose.PSD](../../)


