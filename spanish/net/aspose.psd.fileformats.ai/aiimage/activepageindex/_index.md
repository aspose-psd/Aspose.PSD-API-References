---
title: "AiImage.ActivePageIndex"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad AiImage. Obtiene o establece el índice de la página activa"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Obtiene o establece el índice de la página activa.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Esta propiedad solo es válida para imágenes AI en formato PDF. Si la imagen no está en formato PDF o no hay páginas, la propiedad será -1. Esta propiedad indica qué página de la imagen AI será la base para el renderizado.

## Ejemplos

El siguiente código demuestra la capacidad de cambiar la página activa en imágenes Ai.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Cargue la imagen AI.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Por defecto, ActivePageIndex es 0.
    // Por lo tanto, si guarda la imagen AI sin cambiar esta propiedad, la primera página se renderizará y guardará.
    image.Save(firstPageOutputPng, new PngOptions());

    // Cambie el índice de la página activa a la segunda página.
    image.ActivePageIndex = 1;

    // Guarde la segunda página de la imagen AI como una imagen PNG.
    image.Save(secondPageOutputPng, new PngOptions());

    // Cambie el índice de la página activa a la tercera página.
    image.ActivePageIndex = 2;

    // Guarde la tercera página de la imagen AI como una imagen PNG.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Ver también

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


