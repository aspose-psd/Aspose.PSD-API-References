---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "AiImage 속성. 활성 페이지의 인덱스를 가져오거나 설정합니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

활성 페이지의 인덱스를 가져오거나 설정합니다.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

이 속성은 PDF 형식 AI 이미지에만 적용됩니다. 이미지가 PDF 형식이 아니거나 페이지가 없으면, 이 속성은 -1이 됩니다. 이 속성은 AI 이미지의 어느 페이지가 렌더링의 기준이 될지를 나타냅니다.

## 예제

다음 코드는 Ai 이미지에서 활성 페이지를 변경할 수 있는 기능을 지원함을 보여줍니다.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// AI 이미지를 로드합니다.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // 기본값으로 ActivePageIndex는 0입니다.
    // 따라서 이 속성을 변경하지 않고 AI 이미지를 저장하면 첫 번째 페이지가 렌더링되고 저장됩니다.
    image.Save(firstPageOutputPng, new PngOptions());

    // 활성 페이지 인덱스를 두 번째 페이지로 변경합니다.
    image.ActivePageIndex = 1;

    // AI 이미지의 두 번째 페이지를 PNG 이미지로 저장합니다.
    image.Save(secondPageOutputPng, new PngOptions());

    // 활성 페이지 인덱스를 세 번째 페이지로 변경합니다.
    image.ActivePageIndex = 2;

    // AI 이미지의 세 번째 페이지를 PNG 이미지로 저장합니다.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### 또 보기

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


