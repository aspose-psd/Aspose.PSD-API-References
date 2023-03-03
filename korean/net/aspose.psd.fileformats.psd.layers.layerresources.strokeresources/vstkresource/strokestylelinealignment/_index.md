---
title: VstkResource.StrokeStyleLineAlignment
second_title: .NET API 참조용 Aspose.PSD
description: VstkResource 재산. 획 스타일 선 정렬을 가져오거나 설정합니다.
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

획 스타일 선 정렬을 가져오거나 설정합니다.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* 집회 [Aspose.PSD](../../../)


