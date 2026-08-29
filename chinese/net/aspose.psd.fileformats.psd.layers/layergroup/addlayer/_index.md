---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD for .NET API 参考"
description: "LayerGroup 方法。将图层添加到图层组"
type: docs
weight: 60
url: /zh/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

将图层添加到图层组。

```csharp
public void AddLayer(Layer layer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | 图层 | 图层。 |

## 示例

以下示例演示如何将 Bmp、Jpeg、Jpeg2000、Png、Psd、Tiff、Gif 图像作为图层添加到 PsdImage

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

### 另请参阅

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


