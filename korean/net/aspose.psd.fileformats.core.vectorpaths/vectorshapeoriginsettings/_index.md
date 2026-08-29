---
title: "클래스 VectorShapeOriginSettings"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings 클래스. 벡터 형태 기원 설정"
type: docs
weight: 1450
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
{{< psd/tize >}}
## VectorShapeOriginSettings class

벡터 형태 시작 설정.

```csharp
public sealed class VectorShapeOriginSettings
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | `VectorShapeOriginSettings` 클래스의 새 인스턴스를 초기화합니다. |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor_1)(bool, int) | `VectorShapeOriginSettings` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | 이 인스턴스에 원본 상자 모서리 속성이 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | 이 인스턴스에 원본 인덱스 속성이 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | 이 인스턴스에 원본 반경 사각형 속성이 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | 이 인스턴스에 원본 해상도 속성이 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | 이 인스턴스에 사각형 속성이 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | 이 인스턴스에 원본 유형 속성이 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | 형상이 무효화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | 이 인스턴스에 형상 무효화 속성 집합이 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | 이 인스턴스에 변환 속성이 있는지 여부를 나타내는 값을 가져옵니다. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | 원본 박스 모서리를 가져오거나 설정합니다. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | 원본 형상 인덱스를 가져오거나 설정합니다. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | 원본 반경 사각형을 가져오거나 설정합니다. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | 원본 해상도를 가져오거나 설정합니다. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | 원본 형상 경계 상자를 가져오거나 설정합니다. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | 원본의 유형을 가져오거나 설정합니다. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | 변환 행렬을 가져오거나 설정합니다. |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


