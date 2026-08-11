---
title: "BackgroundColorResource.Color"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "BackgroundColorResource 속성. 배경 색상을 가져오거나 설정합니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
{{< psd/tize >}}
## BackgroundColorResource.Color property

배경 색상을 가져오거나 설정합니다.

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


