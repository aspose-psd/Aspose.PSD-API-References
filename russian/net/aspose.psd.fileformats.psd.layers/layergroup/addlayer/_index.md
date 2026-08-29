---
title: "LayerGroup.AddLayer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод LayerGroup. Добавляет слой в группу слоев"
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

Добавляет слой в группу слоёв.

```csharp
public void AddLayer(Layer layer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| слой | Слой | Слой. |

## Примеры

В следующем примере показано, как можно добавить изображения Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif в виде слоев в PsdImage

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

### См. также

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


