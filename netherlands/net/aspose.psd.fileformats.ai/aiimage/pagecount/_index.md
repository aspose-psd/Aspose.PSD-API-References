---
title: "AiImage.PageCount"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "AiImage property. Het aantal pagina's. Voor het oude AI-formaat zijn afbeeldingen altijd gelijk aan 0"
type: docs
weight: 110
url: /nl/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

Het aantal pagina's. Voor het oude AI-formaat zijn afbeeldingen altijd gelijk aan 0.

```csharp
public int PageCount { get; }
```

### Property Value

Het aantal pagina's.

## Voorbeelden

De volgende code toont de ondersteuning van de AiImage-eigenschap voor het aantal pagina's AiImage.PageCount.

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

### Zie ook

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


