---
title: LayerGroup.AddLayer
second_title: .NET API 참조용 Aspose.PSD
description: LayerGroup 방법. 레이어 그룹에 레이어를 추가합니다.
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

레이어 그룹에 레이어를 추가합니다.

```csharp
public void AddLayer(Layer layer)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| layer | Layer | 레이어. |

### 예

다음 예제는 Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif 이미지를 레이어로 PsdImage에 추가하는 방법을 보여줍니다.

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

### 또한보십시오

* class [Layer](../../layer/)
* class [LayerGroup](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* 집회 [Aspose.PSD](../../../)


