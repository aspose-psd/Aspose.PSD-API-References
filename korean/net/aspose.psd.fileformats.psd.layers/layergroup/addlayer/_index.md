---
title: "LayerGroup.AddLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LayerGroup 메서드. 레이어를 레이어 그룹에 추가합니다."
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
{{< psd/tize >}}
## LayerGroup.AddLayer method

레이어를 레이어 그룹에 추가합니다.

```csharp
public void AddLayer(Layer layer)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 레이어 | 레이어 | 레이어. |

## 예제

다음 예제는 Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif 이미지들을 레이어로 PsdImage에 추가하는 방법을 보여줍니다.

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

### 또 보기

* class [Layer](../../layer/)
* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


