---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD for .NET API 参考"
description: "AiImage 属性。获取或设置活动页的索引"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

获取或设置活动页的索引。

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

此属性仅适用于 PDF 格式的 AI 图像。如果图像不是 PDF 格式或没有页面，则该属性为 -1。此属性指示 AI 图像的哪一页将用作渲染的基准。

## 示例

以下代码演示了在 Ai 图像中更改活动页的功能支持。

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// 加载 AI 图像。
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // 默认情况下，ActivePageIndex 为 0。
    // 因此，如果在未更改此属性的情况下保存 AI 图像，第一页将被渲染并保存。
    image.Save(firstPageOutputPng, new PngOptions());

    // 将活动页索引更改为第二页。
    image.ActivePageIndex = 1;

    // 将 AI 图像的第二页保存为 PNG 图像。
    image.Save(secondPageOutputPng, new PngOptions());

    // 将活动页索引更改为第三页。
    image.ActivePageIndex = 2;

    // 将 AI 图像的第三页保存为 PNG 图像。
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### 另请参阅

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


