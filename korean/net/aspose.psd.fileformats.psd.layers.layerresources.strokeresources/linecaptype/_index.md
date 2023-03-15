---
title: Enum LineCapType
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType 열거형. 라인 캡 유형.
type: docs
weight: 3040
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

라인 캡 유형.

```csharp
public enum LineCapType : short
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| RoundCap | `0` | 원형 캡 유형. |
| SquareCap | `1` | 사각캡 타입. |
| ButtCap | `2` | 버트 캡 유형. |

### 예

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

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* 집회 [Aspose.PSD](../../)


