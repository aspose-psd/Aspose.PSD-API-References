---
title: "AiImage.PageCount"
second_title: "Aspose.PSD for .NET API Reference"
description: "AiImage プロパティ。ページ数です。古い AI フォーマットでは画像は常に 0 になります"
type: docs
weight: 110
url: /ja/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

ページ数です。古い AI フォーマットの画像では常に 0 です。

```csharp
public int PageCount { get; }
```

### Property Value

ページ数です。

## 例

以下のコードは、ページ数に対する AiImage プロパティのサポート（AiImage.PageCount）を示しています。

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

### 関連項目

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


