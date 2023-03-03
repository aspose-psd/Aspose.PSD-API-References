---
title: BackgroundColorResource.DataSize
second_title: Referencia de API de Aspose.PSD para .NET
description: BackgroundColorResource propiedad. Obtiene el tamaño de los datos del recurso en bytes.
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

Obtiene el tamaño de los datos del recurso en bytes.

```csharp
public override int DataSize { get; }
```

### El valor de la propiedad

El tamaño de los datos del recurso.

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


