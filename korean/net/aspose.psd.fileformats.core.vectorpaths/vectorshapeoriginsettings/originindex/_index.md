---
title: "VectorShapeOriginSettings.OriginIndex"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VectorShapeOriginSettings 속성. 원본 형태 인덱스를 가져오거나 설정합니다"
type: docs
weight: 120
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.OriginIndex property

원본 형상 인덱스를 가져오거나 설정합니다.

```csharp
public int OriginIndex { get; set; }
```

## 예제

다음 예제는 VogkResource 리소스 지원을 보여줍니다.

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

    // 읽기
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

### 또 보기

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


