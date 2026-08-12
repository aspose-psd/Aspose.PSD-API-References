---
title: "AiImage.PageCount"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad AiImage. El número de páginas. Para las imágenes del formato AI antiguo siempre es 0"
type: docs
weight: 110
url: /es/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

El número de páginas. Para las imágenes del formato AI antiguo siempre es 0.

```csharp
public int PageCount { get; }
```

### Property Value

El número de páginas.

## Ejemplos

El siguiente código demuestra el soporte de la propiedad AiImage para el número de páginas AiImage.PageCount.

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

### Ver también

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


