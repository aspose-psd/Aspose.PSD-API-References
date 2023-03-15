---
title: BackgroundColorResource.Color
second_title: Referencia de API de Aspose.PSD para .NET
description: BackgroundColorResource propiedad. Obtiene o establece el color de fondo.
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Obtiene o establece el color de fondo.

```csharp
public Color Color { get; set; }
```

### Ejemplos

El siguiente ejemplo demuestra la compatibilidad con el recurso BackgroundColorResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // actualizar BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Ver también

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* asamblea [Aspose.PSD](../../../)


