---
title: RasterCachedImage.Crop
second_title: .NET API 참조용 Aspose.PSD
description: RasterCachedImage 방법. 이미지 자르기.
type: docs
weight: 90
url: /ko/net/aspose.psd/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

이미지 자르기.

```csharp
public override void Crop(Rectangle rectangle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rectangle | Rectangle | 직사각형. |

### 예

다음 코드는 특정 사각형으로 이미지를 자르는 기능을 보여줍니다.

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

    // psd 저장
    image.Save(exportPath, new PsdOptions());

    // png 저장
    image.Save(exportPathPng, new PngOptions());
}
```

### 또한보십시오

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* 네임스페이스 [Aspose.PSD](../../rastercachedimage/)
* 집회 [Aspose.PSD](../../../)


