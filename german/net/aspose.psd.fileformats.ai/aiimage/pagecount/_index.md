---
title: "AiImage.PageCount"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "AiImage-Eigenschaft. Die Anzahl der Seiten. Für das alte AI-Format ist die Seitenzahl immer 0"
type: docs
weight: 110
url: /de/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

Die Anzahl der Seiten. Für das alte AI-Format sind Bilder immer gleich 0.

```csharp
public int PageCount { get; }
```

### Property Value

Die Anzahl der Seiten.

## Beispiele

Der folgende Code demonstriert die Unterstützung der AiImage-Eigenschaft für die Seitenanzahl AiImage.PageCount.

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

### Siehe auch

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


