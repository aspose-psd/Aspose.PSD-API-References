---
title: "BorderInformationResource.DataSize"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad BorderInformationResource. Obtiene el tamaño de los datos del recurso en bytes."
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
{{< psd/tize >}}
## BorderInformationResource.DataSize property

Obtiene el tamaño de los datos del recurso en bytes.

```csharp
public override int DataSize { get; }
```

### Property Value

El tamaño de los datos del recurso.

## Ejemplos

El siguiente ejemplo muestra el soporte del recurso BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // actualizar BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Ver también

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


