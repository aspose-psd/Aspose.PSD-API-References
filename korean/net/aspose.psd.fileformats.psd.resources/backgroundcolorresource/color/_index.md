---
title: BackgroundColorResource.Color
second_title: .NET API 참조용 Aspose.PSD
description: BackgroundColorResource 재산. 배경색을 가져오거나 설정합니다.
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

배경색을 가져오거나 설정합니다.

```csharp
public Color Color { get; set; }
```

### 예

다음 예제는 BackgroundColorResource 자원의 지원을 보여줍니다.

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

### 또한보십시오

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* 집회 [Aspose.PSD](../../../)


