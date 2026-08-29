---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "BackgroundColorResource 속성. 최소 요구 PSD 버전을 가져옵니다"
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

필요한 최소 PSD 버전을 가져옵니다.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

최소 PSD 버전.

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


