---
title: "AiImage.PageCount"
second_title: "Aspose.PSD för .NET API‑referens"
description: "AiImage-egenskap. Antalet sidor. För de gamla AI-formatbilderna är det alltid 0."
type: docs
weight: 110
url: /sv/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

Antalet sidor. För de gamla AI‑formatbilderna är det alltid 0.

```csharp
public int PageCount { get; }
```

### Property Value

Antalet sidor.

## Exempel

Följande kod demonstrerar stöd för AiImage-egenskapen för antalet sidor AiImage.PageCount.

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

### Se även

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


