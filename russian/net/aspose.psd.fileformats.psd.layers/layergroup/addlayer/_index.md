---
title: LayerGroup.AddLayer
second_title: Справочник по Aspose.PSD для .NET API
description: LayerGroup метод. Добавляет слой в группу слоев.
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

Добавляет слой в группу слоев.

```csharp
public void AddLayer(Layer layer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| layer | Layer | Слой. |

### Примеры

В следующем примере показано, как можно добавлять изображения Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif в качестве слоев в PsdImage.

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### Смотрите также

* class [Layer](../../layer/)
* class [LayerGroup](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* сборка [Aspose.PSD](../../../)


