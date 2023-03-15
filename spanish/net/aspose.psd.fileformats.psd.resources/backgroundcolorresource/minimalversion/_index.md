---
title: BackgroundColorResource.MinimalVersion
second_title: Referencia de API de Aspose.PSD para .NET
description: BackgroundColorResource propiedad. Obtiene la versión PSD mínima requerida.
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Obtiene la versión PSD mínima requerida.

```csharp
public override int MinimalVersion { get; }
```

### El valor de la propiedad

La versión PSD mínima.

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

* class [BackgroundColorResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* asamblea [Aspose.PSD](../../../)


