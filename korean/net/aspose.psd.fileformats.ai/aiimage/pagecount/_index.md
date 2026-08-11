---
title: "AiImage.PageCount"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "AiImage 속성. 페이지 수. 오래된 AI 형식에서는 이미지가 항상 0과 같습니다"
type: docs
weight: 110
url: /ko/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

페이지 수입니다. 오래된 AI 형식 이미지의 경우 항상 0입니다.

```csharp
public int PageCount { get; }
```

### Property Value

페이지 수.

## 예제

다음 코드는 페이지 수에 대한 AiImage 속성 지원을 보여줍니다 AiImage.PageCount.

```csharp
[C#]

string sourceFile = "2241.ai";
string[] outputFiles = new string[3]
{
    "2241_pageNumber_0.png",
    "2241_pageNumber_1.png",
    "2241_pageNumber_2.png",
};

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.PageCount, 3);

    for (int i = 0; i < image.PageCount; i++)
    {
        image.ActivePageIndex = i;
        image.Save(outputFiles[i], new PngOptions());
    }
}
```

### 또 보기

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


