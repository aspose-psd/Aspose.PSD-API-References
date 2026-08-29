---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerGroup メソッド。レイヤーをレイヤー グループに追加します"
type: docs
weight: 60
url: /ja/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

レイヤーをレイヤー グループに追加します。

```csharp
public void AddLayer(Layer layer)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| レイヤー | レイヤー | レイヤーです。 |

## 例

次の例は、Bmp、Jpeg、Jpeg2000、Png、Psd、Tiff、Gif 画像をレイヤーとして PsdImage に追加できる方法を示しています

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

### 関連項目

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


