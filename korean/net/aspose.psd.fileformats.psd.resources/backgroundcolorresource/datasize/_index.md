---
title: "BackgroundColorResource.DataSize"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "BackgroundColorResource 속성. 리소스 데이터 크기를 바이트 단위로 가져옵니다"
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

리소스 데이터 크기를 바이트 단위로 가져옵니다.

```csharp
public override int DataSize { get; }
```

### Property Value

리소스 데이터 크기.

## 예제

다음 예제는 BackgroundColorResource 리소스의 지원을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // BackgroundColorResource 업데이트
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### 또 보기

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


