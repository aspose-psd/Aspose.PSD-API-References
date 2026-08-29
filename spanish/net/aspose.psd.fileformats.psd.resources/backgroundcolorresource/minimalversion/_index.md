---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad BackgroundColorResource. Obtiene la versión mínima requerida de PSD"
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Obtiene la versión mínima requerida del PSD.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

La versión mínima de PSD.

## Ejemplos

El siguiente ejemplo demuestra el soporte del recurso BackgroundColorResource.

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
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


