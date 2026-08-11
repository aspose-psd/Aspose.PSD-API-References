---
title: "AiImage.PageCount"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà AiImage. Il numero di pagine. Per le immagini del vecchio formato AI è sempre uguale a 0"
type: docs
weight: 110
url: /it/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

Il numero di pagine. Per le immagini del vecchio formato AI è sempre uguale a 0.

```csharp
public int PageCount { get; }
```

### Property Value

Il numero di pagine.

## Esempi

Il codice seguente dimostra il supporto della proprietà AiImage per il numero di pagine AiImage.PageCount.

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

### Vedi anche

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


