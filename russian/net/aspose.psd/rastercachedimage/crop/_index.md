---
title: RasterCachedImage.Crop
second_title: Справочник по Aspose.PSD для .NET API
description: RasterCachedImage метод. Обрезка изображения.
type: docs
weight: 90
url: /ru/net/aspose.psd/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

Обрезка изображения.

```csharp
public override void Crop(Rectangle rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | Rectangle | Прямоугольник. |

### Примеры

Следующий код демонстрирует возможность обрезать изображение по определенному прямоугольнику.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // Сохранить psd
    image.Save(exportPath, new PsdOptions());

    // Сохранить png
    image.Save(exportPathPng, new PngOptions());
}
```

### Смотрите также

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* пространство имен [Aspose.PSD](../../rastercachedimage/)
* сборка [Aspose.PSD](../../../)


