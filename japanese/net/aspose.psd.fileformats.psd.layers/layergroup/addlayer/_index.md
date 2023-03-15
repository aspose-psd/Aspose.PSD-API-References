---
title: LayerGroup.AddLayer
second_title: Aspose.PSD for .NET API リファレンス
description: LayerGroup 方法. レイヤーをレイヤー グループに追加します
type: docs
weight: 60
url: /ja/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

レイヤーをレイヤー グループに追加します。

```csharp
public void AddLayer(Layer layer)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| layer | Layer | 層。 |

### 例

次の例は、Bmp、Jpeg、Jpeg2000、Png、Psd、Tiff、Gif 画像をレイヤーとして PsdImage に追加する方法を示しています。

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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* 組み立て [Aspose.PSD](../../../)


