---
title: "Enum LineJoinType"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enum. 라인 조인 유형"
type: docs
weight: 3410
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
{{< psd/tize >}}
## LineJoinType enumeration

라인 조인 유형.

```csharp
public enum LineJoinType : short
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| BevelJoin | `0` | 베벨 조인 유형. |
| RoundJoin | `1` | 라운드 조인 유형. |
| MiterJoin | `2` | 미터 조인 유형. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


