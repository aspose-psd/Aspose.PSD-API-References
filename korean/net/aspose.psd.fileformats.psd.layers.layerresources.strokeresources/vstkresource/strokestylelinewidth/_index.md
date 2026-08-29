---
title: "VstkResource.StrokeStyleLineWidth"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VstkResource 속성. Stroke 라인 너비를 가져오거나 설정합니다"
type: docs
weight: 140
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineWidth property

스트로크 라인 너비를 가져오거나 설정합니다.

```csharp
public double StrokeStyleLineWidth { get; set; }
```

## 예제

다음 코드는 VstkResource 리소스의 지원을 보여줍니다.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### 또 보기

* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


