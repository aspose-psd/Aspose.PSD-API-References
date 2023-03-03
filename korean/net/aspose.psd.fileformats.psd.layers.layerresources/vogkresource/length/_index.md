---
title: VogkResource.Length
second_title: .NET API 참조용 Aspose.PSD
description: VogkResource 재산. 레이어 리소스 길이를 바이트 단위로 가져옵니다.
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/
---
## VogkResource.Length property

레이어 리소스 길이를 바이트 단위로 가져옵니다.

```csharp
public override int Length { get; }
```

### 예

다음 예제는 VogkResource 리소스의 지원을 보여줍니다.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // 독서
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // 편집
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### 또한보십시오

* class [VogkResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* 집회 [Aspose.PSD](../../../)


