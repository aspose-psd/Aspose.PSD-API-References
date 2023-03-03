---
title: PsdImage.AddLayer
second_title: Справочник по Aspose.PSD для .NET API
description: PsdImage метод. Добавляет слой.
type: docs
weight: 370
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

Добавляет слой.

```csharp
public void AddLayer(Layer layer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| layer | Layer | Слой. |

### Примеры

В следующем примере показано, как можно рисовать на вновь созданном слое, если в Aspose.PSD используется версия простого конструктора.

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // рисуем прямоугольник инструментом Перо
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // рисуем еще один прямоугольник сплошной кистью синего цвета
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Смотрите также

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* сборка [Aspose.PSD](../../../)


