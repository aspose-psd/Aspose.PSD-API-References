---
title: VectorShapeOriginSettings.IsShapeInvalidated
second_title: .NET API 참조용 Aspose.PSD
description: VectorShapeOriginSettings 재산. 모양이 무효화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.
type: docs
weight: 80
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/
---
## VectorShapeOriginSettings.IsShapeInvalidated property

모양이 무효화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

```csharp
public bool IsShapeInvalidated { get; set; }
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

* class [VectorShapeOriginSettings](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* 집회 [Aspose.PSD](../../../)


