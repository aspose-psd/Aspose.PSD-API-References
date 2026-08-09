---
title: "AiImage.PageCount"
second_title: "Aspose.PSD for .NET API 参考"
description: "AiImage 属性。页面数量。对于旧的 AI 格式，图像始终等于 0"
type: docs
weight: 110
url: /zh/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

页面数量。对于旧的 AI 格式图像始终等于 0。

```csharp
public int PageCount { get; }
```

### Property Value

页面数量。

## 示例

以下代码演示了对页面数量的 AiImage 属性支持 AiImage.PageCount。

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

### 另请参阅

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


