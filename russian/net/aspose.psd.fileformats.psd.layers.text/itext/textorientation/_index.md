---
title: "IText.TextOrientation"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство IText. Получает или задаёт ориентацию текста"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
{{< psd/tize >}}
## IText.TextOrientation property

Получает или задает ориентацию текста.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Property Value

Ориентация текста.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


