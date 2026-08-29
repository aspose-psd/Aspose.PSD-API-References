---
title: "AiImage.PageCount"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété AiImage. Le nombre de pages. Pour les images au format AI ancien, il est toujours égal à 0"
type: docs
weight: 110
url: /fr/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

Le nombre de pages. Pour les images du ancien format AI, il est toujours égal à 0.

```csharp
public int PageCount { get; }
```

### Property Value

Le nombre de pages.

## Exemples

Le code suivant démontre la prise en charge de la propriété AiImage pour le nombre de pages AiImage.PageCount.

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

### Voir aussi

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


