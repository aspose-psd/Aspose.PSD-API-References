---
title: BorderInformationResource.MinimalVersion
second_title: .NET API 참조용 Aspose.PSD
description: BorderInformationResource 재산. 필요한 최소 PSD 버전을 가져옵니다.
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

필요한 최소 PSD 버전을 가져옵니다.

```csharp
public override int MinimalVersion { get; }
```

### 자산 가치

최소 PSD 버전.

### 예

다음 예제는 BorderInformationResource 자원의 지원을 보여줍니다.

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

### 또한보십시오

* class [BorderInformationResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* 집회 [Aspose.PSD](../../../)


