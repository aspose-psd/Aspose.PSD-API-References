---
title: BorderInformationResource.DataSize
second_title: .NET API 참조용 Aspose.PSD
description: BorderInformationResource 재산. 리소스 데이터 크기를 바이트 단위로 가져옵니다.
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
## BorderInformationResource.DataSize property

리소스 데이터 크기를 바이트 단위로 가져옵니다.

```csharp
public override int DataSize { get; }
```

### 자산 가치

리소스 데이터 크기입니다.

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


