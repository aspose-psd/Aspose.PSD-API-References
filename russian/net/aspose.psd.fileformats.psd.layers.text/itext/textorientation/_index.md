---
title: IText.TextOrientation
second_title: Справочник по Aspose.PSD для .NET API
description: IText свойство. Получает или задает ориентацию текста.
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Получает или задает ориентацию текста.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Стоимость имущества

Ориентация текста.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* сборка [Aspose.PSD](../../../)


