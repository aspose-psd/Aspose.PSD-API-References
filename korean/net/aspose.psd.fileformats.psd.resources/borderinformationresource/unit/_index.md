---
title: "BorderInformationResource.Unit"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "BorderInformationResource 속성. 테두리 단위를 가져오거나 설정합니다"
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
{{< psd/tize >}}
## BorderInformationResource.Unit property

테두리 단위를 가져오거나 설정합니다.

```csharp
public PhysicalUnit Unit { get; set; }
```

## 예제

다음 예제는 BorderInformationResource 리소스의 지원을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // BorderInformationResource 업데이트
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### 또 보기

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


