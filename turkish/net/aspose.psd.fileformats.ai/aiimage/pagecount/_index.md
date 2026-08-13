---
title: "AiImage.PageCount"
second_title: "Aspose.PSD for .NET API Referansı"
description: "AiImage özelliği. Sayfa sayısı. Eski AI formatındaki görüntüler için her zaman 0'dır"
type: docs
weight: 110
url: /tr/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

Sayfa sayısı. Eski AI formatı görüntüleri için her zaman 0'dır.

```csharp
public int PageCount { get; }
```

### Property Value

Sayfa sayısı.

## Örnekler

Aşağıdaki kod, sayfa sayısı için AiImage özelliği AiImage.PageCount desteğini gösterir.

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

### Ayrıca Bakınız

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


