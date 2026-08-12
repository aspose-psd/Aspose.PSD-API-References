---
title: "PsdImage.AddLayer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод PsdImage. Добавляет слой"
type: docs
weight: 390
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

Добавляет слой.

```csharp
public void AddLayer(Layer layer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| слой | Слой | Слой. |

## Примеры

В следующем примере показано, как можно рисовать на только что созданном слое, если используется простая версия конструктора в Aspose.PSD

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

    // нарисуйте прямоугольник с помощью инструмента Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // нарисуйте другой прямоугольник с помощью Solid Brush синего цвета
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### См. также

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


