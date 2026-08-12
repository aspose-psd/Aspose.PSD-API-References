---
title: "BackgroundColorResource.DataSize"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad BackgroundColorResource. Obtiene el tamaño de los datos del recurso en bytes"
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

Obtiene el tamaño de los datos del recurso en bytes.

```csharp
public override int DataSize { get; }
```

### Property Value

El tamaño de los datos del recurso.

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


