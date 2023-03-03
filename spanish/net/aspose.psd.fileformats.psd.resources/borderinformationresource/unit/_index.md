---
title: BorderInformationResource.Unit
second_title: Referencia de API de Aspose.PSD para .NET
description: BorderInformationResource propiedad. Obtiene o establece las unidades del borde.
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

Obtiene o establece las unidades del borde.

```csharp
public PhysicalUnit Unit { get; set; }
```

### Ejemplos

El siguiente ejemplo demuestra la compatibilidad del recurso BorderInformationResource.

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

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* asamblea [Aspose.PSD](../../../)


